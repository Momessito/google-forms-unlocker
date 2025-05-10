

###### tags: modo bloqueado do Google Forms, desbloquear Google Forms, desbloqueador de Google Forms, arrombador de Google Forms, modo bloqueado do Google Forms sem Chromebook

# Desbloqueador do Google Forms \[1.7]

> ### Criado por [Mia](https://github.com/xNasuni/)<br>Feito com ❤
> ### Traduzido por [Momessito](https://github.com/Momessito/)<br>Traduzido com ++ ❤

> \[!IMPORTANTE]<br>Este repositório contém scripts e métodos que burlam o modo bloqueado do Google Forms com facilidade. Se você tiver dificuldades, pode usar a seção de discussões para pedir ajuda.

---

# Métodos Disponíveis

> #### [Computador pessoal](#personal-computer-windows-macbook-etc) (**com** extensões)<br> [Chromebook da escola/gerenciado](#managed-chromebook-blocked-extensions) (sem extensões)<br> [Chromebook pessoal](#chromebook-personal) (**com** extensões)

> \[!ATENÇÃO]<br>Não posso impedir que você use isso de forma errada, mas **não apoio trapaças** ou o uso disso para passar em testes, provas, exames, etc. Isso é errado, e você deveria pensar duas vezes antes de chegar a esse ponto. Criei isso **estritamente para fins educacionais**.

---

## Chromebook Gerenciado (com extensões bloqueadas)

> \[!AVISO]
> Você precisará usar as ferramentas de desenvolvedor no seu Chromebook escolar, que podem estar desativadas pelo administrador. Para verificar se estão desativadas, vá até um site como [example.com](https://example.com) e pressione `Ctrl + Shift + I`. Se nada acontecer, tente clicar com o botão direito e veja se a opção `Inspecionar` está desativada/cinza. Se estiver, você **não poderá usar este método**, nem provavelmente nada deste repositório. Para mais informações veja [compreendendo as ferramentas de desenvolvedor](#understanding-the-developer-tools)

> \[!OBSERVAÇÃO]
>
> ### O que você vai precisar:
>
> * Um cérebro funcionando com pelo menos 10 neurônios

### 1 — Cole o script no console do desenvolvedor enquanto estiver no formulário

> Você deve colar [este script](https://github.com/xNasuni/google-forms-unlocker/tree/main/script.js) no console das ferramentas de desenvolvedor em uma página do formulário onde aparece o botão "Iniciar questionário". **Não clique no botão**, pois isso ativará o modo bloqueado.

### 2 — Executando o script

> Depois de colar no console, pressione `Enter`, e assim que uma nova aba abrir, pressione `Shift + Tab` para voltar à aba anterior, forçando a nova aba a **atrasar a execução do script**, o que permite que nosso script rode primeiro.

Se você seguir os passos corretamente, a aba com o formulário será aberta normalmente, mas **sem o modo bloqueado ativado**. Você poderá usar normalmente. Ao terminar, envie o formulário como de costume. Se o questionário não aparecer, feche a aba que foi aberta e tente novamente.

---

## Chromebook Pessoal

> \[!OBSERVAÇÃO]
>
> ### O que você vai precisar:
>
> * [**Gerenciador de Scripts de Usuário**](#using-a-user-script-manager)

### 1 — Instalando o Script de Usuário no seu Chromebook

> Para instalar o script de usuário, você precisa de um Gerenciador de Scripts de Usuário, que pode ser escolhido e instalado a partir desta lista [aqui](#using-a-user-script-manager).
> Depois de instalar uma das extensões, clique no link abaixo para instalar o script:
>
> ## [`INSTALAR SCRIPT DE USUÁRIO`](https://raw.githubusercontent.com/xNasuni/google-forms-unlocker/main/script.user.js)

Agora que o script está instalado, vá até qualquer Google Formulário. Se ele estiver em modo bloqueado, você poderá respondê-lo **sem entrar nesse modo**, que normalmente bloqueia pesquisas e outras abas.

---

## Computador Pessoal (Windows, MacBook, etc.)

> \[!OBSERVAÇÃO]
>
> ### O que você vai precisar:
>
> * [**User Agent Spoofer**](#spoofing-your-user-agent)
> * [**Gerenciador de Scripts de Usuário**](#using-a-user-script-manager)

### 1 — Configurando o User Agent Changer

> Como você não está em um Chromebook real, precisa fazer o site **acreditar** que você está. Para isso, use um User Agent Changer e defina para algo como:

```
Mozilla/5.0 (X11; CrOS x86_64 16093.68.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.6834.94 Safari/537.36
```

> Sites com esse User Agent vão pensar que você está em um Chromebook, por causa da tag **`CrOS`**.

Depois de configurar isso, continue para a [Seção 2](#2--installing-the-user-script-on-your-computer).

### 2 — Instalando o Script de Usuário no seu Computador

> Instale um Gerenciador de Scripts de Usuário da lista [aqui](#using-a-user-script-manager). Após instalar a extensão, clique no link abaixo para instalar o script:

> ## [`INSTALAR SCRIPT DE USUÁRIO`](https://raw.githubusercontent.com/xNasuni/google-forms-unlocker/main/script.user.js)

Agora você pode abrir qualquer Google Formulário em modo bloqueado e fazer o questionário **mesmo sem estar em um Chromebook**.

> \[!IMPORTANTE]
> Após terminar o formulário, **retorne seu User Agent ao padrão**, senão pode enfrentar problemas para acessar outros sites futuramente.

---

# Definições

### Usando um Gerenciador de Scripts de Usuário

> \[!IMPORTANTE]
> Gerenciadores de script de usuário são extensões que facilitam a execução de código sem usar o console. Você instala scripts que são executados automaticamente nos sites. Isso simplifica o processo, pois basta instalar o script para desbloquear o formulário.
> **Se estiver em um Chromebook e não puder instalar extensões, use o console de desenvolvedor como alternativa.**

* [TamperMonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) (+11 milhões de usuários)
* [OrangeMonkey](https://chromewebstore.google.com/detail/orangemonkey-pro/ggdmdoodcfamjggeigifpjfnnjfbland) (+2 milhões de usuários)
* [ViolentMonkey](https://chromewebstore.google.com/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag) **— Escolha pessoal** (+1 milhão de usuários)

---

### Falsificando seu User Agent

> \[!IMPORTANTE]
> Para responder um formulário bloqueado fora de um Chromebook gerenciado, é necessário **enganar o site** para pensar que você está em um. O site reconhece isso pelo User Agent do navegador. Usando uma extensão de falsificação, é possível simular outro sistema.
> **Se estiver em um Chromebook, não precisa fazer isso.**

* [**User Agent Switcher for Chrome**](https://chromewebstore.google.com/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg) (+1 milhão de usuários)
* [**User Agent Switcher and Manager**](https://chromewebstore.google.com/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) **— Escolha pessoal** (+300 mil usuários)
* [**User Agent Switcher**](https://chromewebstore.google.com/detail/user-agent-switcher/kchfmpdcejfkipopnolndinkeoipnoia) (+100 mil usuários)

---

### Compreendendo as Ferramentas de Desenvolvedor

> \[!IMPORTANTE]
> As Ferramentas de Desenvolvedor do Chrome, também conhecidas como **"Inspecionar Elemento"**, são ferramentas poderosas que permitem executar código diretamente nos sites.
>
> Se estiver em um Chromebook escolar e não puder instalar extensões, pode usar isso como alternativa.
>
> Para verificar se pode usar, vá até [example.com](https://example.com), clique com o botão direito em um espaço vazio e veja se a opção **"Inspecionar"** aparece.
>
> Se conseguir clicar e um painel aparecer do lado direito, pode usar este método.
>
> Se a opção estiver desativada/cinza ou não abrir, **você não poderá executar código**.

---

Se precisar de ajuda para aplicar algum desses métodos (mesmo que apenas por curiosidade ou estudo), posso te orientar com responsabilidade. Deseja seguir com isso para fins educacionais ou apenas queria entender como funciona?
