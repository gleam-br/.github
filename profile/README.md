## Seja bem-vindo ao GleamBR 👋

🎉 GleamBR é uma comunidade brasileira sobre a linguagem de programação [gleam-lang](https://gleam.run).

⚗️ Podemos também considerar uma plataforma de produção e curadoria de conteúdo, em português, voltada para a comunidade [gleam-lang](https://gleam.run).

- [gleam.dev.br](https://gleam.dev.br): 🚧 Blog sobre tudo o que é possível na BEAM, com foco no Gleam.
- [gleam-lang.com.br](https://gleam-lang.com.br): 🚧 Empresa de ferramentas desenvolvidas em Gleam, com foco no mercado brasileiro.

## ⭐ Pronto para começar sua jornada Gleam?

Confira o [tour da linguagem](https://tour.gleam.run/) e [a documentção](https://gleam.run/documentation) aqui.

Já está usando em produção? [Compartilhe sua história conosco](https://gleam.run/community), adoraríamos saber mais!

## 👩‍💻 Por quê utilizar o gleam?

> Ref. https://lozdev.com/why-gleam-deserves-a-spot-in-your-2025-toolkit-beyond-the-syntax/

### 1. A Tipagem Estática e a Experiência de Desenvolvimento (DX)

Destacando a tipagem estática do Gleam, um recurso que o diferencia de outras linguagens da BEAM como Erlang e Elixir.

* **Tipos Expressivos, Sem Anotações Excessivas:** O Gleam tem um sistema de inferência de tipos muito inteligente. Isso significa que, na maioria das vezes, o compilador consegue descobrir o tipo das variáveis e funções automaticamente. Você só precisa declarar os tipos em pontos estratégicos (como na assinatura de funções públicas), o que resulta em código mais limpo e conciso, sem perder a segurança.
* **A "Segurança" da Tipagem:** A tipagem estática não é apenas sobre capturar erros óbvios. Ela serve como uma forma de documentação viva, facilitando a compreensão do código. Para um desenvolvedor com sua experiência em Java, isso é uma grande vantagem. O sistema de tipos do Gleam atua como um "contrato" entre as partes do seu código, garantindo que tudo funcione como esperado antes mesmo de você rodar o programa.
* **Experiência de Desenvolvimento (DX) Aprimorada:** O compilador do Gleam é rápido, e os erros de tipo são reportados de forma clara e amigável. Isso agiliza o ciclo de desenvolvimento, permitindo que você encontre e corrija problemas rapidamente. Além disso, a tipagem estática melhora o suporte para ferramentas de desenvolvimento (IDEs), oferecendo recursos como autocompletar e refatoração mais precisos.

### 2. O Poder da Imutabilidade e da Programação Funcional

O Gleam abraça totalmente os princípios da programação funcional, com foco na **imutabilidade**.

* **Estado Imutável:** Diferente de linguagens orientadas a objetos como Java, onde o estado pode ser alterado a qualquer momento, o Gleam foca na imutabilidade. Isso significa que uma vez que uma variável é criada, seu valor não pode ser alterado. Em vez disso, você cria uma nova variável com o novo valor. Essa abordagem evita muitos bugs relacionados a concorrência e estado compartilhado, tornando o código mais previsível e seguro.
* **O `|> `(Pipe Operator):** O operador `|> ` (pipe), permite encadear chamadas de função de forma clara e legível. Ele faz a saída de uma função ser a entrada da próxima. Isso transforma o código em uma sequência lógica de transformações, fácil de ler da esquerda para a direita.

### 3. Concorrência e Tolerância a Falhas na BEAM

O Gleam se destaca ao rodar na Erlang Virtual Machine (BEAM), uma plataforma conhecida por sua robustez.

* **Não é "Só" a Sintaxe:** A principal mensagem é que o Gleam não é apenas uma "sintaxe bonita" para a BEAM. Ele é uma porta de entrada para um ecossistema completo de concorrência e tolerância a falhas que é fundamental para a construção de sistemas distribuídos e de alta disponibilidade.
* **Processos Leves (Lightweight Processes):** O Gleam se beneficia do modelo de concorrência baseado em atores da BEAM. Em vez de usar threads complexas, a BEAM usa "processos" leves e isolados que se comunicam por mensagens. Isso torna a concorrência muito mais fácil de gerenciar e entender, eliminando os problemas comuns de bloqueio de threads.
* **Supervisores e Resiliência:** Os **supervisisor**s, que são um dos pilares do OTP (Open Telecom Platform) do Erlang. Supervisores são "guardiões" que monitoram outros processos. Se um processo falha, o supervisor pode reiniciá-lo automaticamente, garantindo que o sistema continue funcionando sem interrupções. O Gleam oferece uma forma simples de aproveitar esse recurso, permitindo a construção de aplicações que se recuperam automaticamente de falhas.

### 4. Interoperabilidade e Flexibilidade

A flexibilidade do Gleam em se integrar com outros ecossistemas.

* **BEAM e JavaScript:** A capacidade do Gleam de compilar para a BEAM **e** para JavaScript. Isso significa que você pode usar a mesma linguagem para construir o seu backend robusto e tolerante a falhas na BEAM e o seu frontend no navegador, ou um backend em Node.js.
* **Acesso a Ecossistemas Maduros:** Graças à sua interoperabilidade, o Gleam não precisa "reinventar a roda". Ele pode facilmente chamar bibliotecas e funções de ecossistemas já maduros, como os de Erlang, Elixir e JavaScript, permitindo que você aproveite milhares de bibliotecas já existentes para suas necessidades.

o Gleam é muito mais do que uma sintaxe elegante. Seus pontos fortes estão na combinação de:

* **Segurança de tipagem estática** que aprimora a experiência de desenvolvimento.
* **A elegância da programação funcional** e a segurança da imutabilidade.
* **O poder e a resiliência da Erlang Virtual Machine (BEAM)** para concorrência e tolerância a falhas.
* **A flexibilidade de compilar para a BEAM e JavaScript**, permitindo sua utilização em diferentes partes de uma aplicação.

O Gleam se posiciona, não como um substituto para Erlang ou Elixir, mas como uma adição valiosa ao kit de ferramentas de um desenvolvedor, especialmente para aqueles que valorizam a segurança de tipos e a clareza do código.

## 🍿 Mais sobre

- [Gleam oficial](https://gleam.run).
- [Gleam e seu criador](https://devtalk.com/t/the-gleam-programming-language-and-its-creator-louis-pilfold/10038).
- [Introdução básica](https://news.ycombinator.com/item?id=41812336).
- [SPA Fullstack em Gleam](https://keii.dev/posts/the-basics-for-a-fullstack-spa-in-gleam)
- [App em Wisp e Lustre](https://gleaming.dev/articles/building-your-first-gleam-web-app/).
- Sobre ['primeiras impressões'](https://news.ycombinator.com/item?id=45231852)
  - https://mtlynch.io/notes/gleam-first-impressions/ 

## 🧙 Alguns recursos

- [Tour Gleam](https://tour.gleam.run/): Faça um tour pela linguagem usando o playground on-line.
- [Gleam javascript](https://github.com/gleam-lang/javascript): Tipo e funções p/ programas rodando em javascript.
- [Gleam erlang](https://github.com/gleam-lang/erlang/): Tipo e funções p/ programas rodando em erlang.
- [Gleam http](https://github.com/gleam-lang/http/): Tipos e funções p/ clientes http e servidores.
- [lutre.build](https://lustre.build): Uma estrutura para criar aplicativos Web no Gleam!
- [rsvp](https://github.com/hayleigh-dot-dev/rsvp): Envie solicitações HTTP de aplicativos em Lustre ou web-components.
- [Wisp](https://hexdocs.pm/wisp/): Web framework simples em gleam.
- [Mist](https://hexdocs.pm/mist/): Web server baseado no mist http server.
- [Gleam Tools](https://github.com/Enderchief/gleam-tools): Ferramentas p/ integrar o gleam ao vue usando Vite.js.
- [create-gleam](https://github.com/Enderchief/create-gleam): Criar projeto na estrutura Vite.js utilizando o plugin p/ gleam.
- [Cigone](https://github.com/Billuc/cigogne): Migrações p/ banco de dados.
- [Job Processing](https://github.com/Pevensie/m25): Processamento de jobs.
- [Gausy](https://github.com/leonqadirie/gauzy): Filtro probabilístico de Gausy.
- [Tempo](https://github.com/jrstrunk/tempo): Data e hora em gleam.
- [Spotless](https://github.com/CrowdHailer/gleam_spotless): OAuth em gleam.
- [Data validator](https://github.com/Enderchief/apollo): Validação de dados.
- [Pevensie](https://github.com/Pevensie/pevensie): Framework p/ backend.

## ⬇️ Instalando o Gleam

- [Guia oficial](https://gleam.run/getting-started/installing/)

Para preparar seu computador para o desenvolvimento com Gleam, você precisará instalar o Gleam, o Erlang e, opcionalmente, instalar quaisquer plugins do Gleam para o seu editor.

### Pré-compilado para Linux, Windows e macOS

A maneira mais fácil de instalar o Gleam no Linux, Windows e Apple macOS é baixar uma versão pré-compilada do compilador da [página de lançamentos do GitHub](https://github.com/gleam-lang/gleam/releases).

### Compilar a partir do código-fonte

O compilador é escrito na linguagem de programação Rust e, portanto, se desejar compilar o Gleam a partir do código-fonte, você precisará instalar o [compilador Rust](https://www.rust-lang.org/tools/install).

```shell
# Baixe o repositório de código-fonte do Gleam
cd /tmp
git clone https://github.com/gleam-lang/gleam.git --branch $THE_LATEST_VERSION
cd gleam

# Compile o compilador do Gleam. Isso levará algum tempo!
make install

# Verifique se o compilador está instalado
# Imprime "gleam $VERSION"
gleam --version
```

### Instalando o Erlang

O Gleam compila para código Erlang, então o Erlang precisa ser instalado para executar o código Gleam. Alguns dos gerenciadores de pacotes acima (por exemplo, Homebrew) instalarão o Erlang junto com o Gleam automaticamente.

Versões pré-compiladas para muitos sistemas operacionais populares podem ser baixadas do site [Erlang Solutions](https://www.erlang-solutions.com/downloads/).

Depois que o Erlang for instalado, você pode verificar se está funcionando digitando `erl -version` no terminal do seu computador. Você verá informações de versão como esta se tudo estiver bem:

```shell
erl -version
Erlang (SMP,ASYNC_THREADS) (BEAM) emulator version 12.1.5
```

### Instalando o rebar3

Ao usar dependências baseadas em Erlang (como seus servidores web e clientes HTTP), a ferramenta de compilação Erlang `rebar3` pode precisar ser instalada. Instale o `rebar3` seguindo as [instruções oficiais de instalação do rebar3](https://rebar3.org/docs/getting-started/).

### macOS

#### Usando o Homebrew

Com o Homebrew instalado, execute o seguinte:

```shell
brew update
brew install gleam
```

#### Usando o MacPorts

Com o MacPorts instalado, execute o seguinte:

```shell
sudo port install gleam
```

### Linux

#### Usando o Homebrew

Com o Homebrew instalado, execute o seguinte:

```shell
brew update
brew install gleam
```

#### gerenciador de versões asdf

O asdf é uma ferramenta para instalar e gerenciar várias versões de linguagens de programação ao mesmo tempo. Instale o [plugin asdf-gleam](https://github.com/asdf-community/asdf-gleam) para gerenciar o Gleam com o asdf.

#### Alpine Linux

O Gleam está disponível no repositório `Community` do Alpine Linux como um pacote `gleam`. Instale-o com:

```shell
apk add gleam
```

#### Arch Linux

O Gleam está disponível através do Arch User Repository como pacote `gleam`. Você pode usar seu auxiliar preferido para instalá-lo ou cloná-lo para compilação manual de `https://aur.archlinux.org/packages/gleam-git`.

```shell
yay -S gleam
```

#### Gentoo Linux

O Gleam está disponível no gerenciador de pacotes oficial, mas pode precisar ser desbloqueado. Instale-o com:

```shell
sudo echo "dev-lang/gleam ~amd64" >> /etc/portage/package.accept_keywords
emerge --ask dev-lang/gleam
```

#### Void Linux

O Gleam está disponível como parte do repositório de pacotes oficial. Instale-o com:

```shell
sudo xbps-install gleam
```

#### Fedora

Você pode instalar o Gleam no Fedora usando o gerenciador de pacotes DNF. Execute o seguinte comando:

```shell
sudo dnf copr enable frostyx/gleam
sudo dnf install gleam
```

#### FreeBSD

O Gleam está disponível nos ports e também em pacotes binários. Pode ser necessário usar o repositório de pacotes mais recente, altere conforme as instruções em `/etc/pkg/FreeBSD.conf`. Veja abaixo como ajustar seu `PATH` para usar o tempo de execução Erlang/OTP mais recente e não apenas o OTP21 padrão:

```shell
$ pkg install -r FreeBSD lang/gleam lang/erlang-runtime23
$ export PATH=/usr/local/lib/erlang23/bin:$PATH
```

#### OpenBSD

O Gleam está disponível como um pacote binário. Você pode instalá-lo com:

```shell
doas pkg_add gleam
```

#### openSUSE

O Gleam está disponível como parte do repositório de pacotes oficial. Instale-o com:

```shell
zypper install gleam
```

### Android

#### Termux

O Gleam está disponível como parte do repositório de pacotes oficial. Instale-o com:

```shell
pkg install gleam
```

### Windows

#### Usando o Scoop

Com o Scoop instalado em seu computador, execute o seguinte:

```shell
scoop install gleam
```

### Plugins de Editor

Plugins do Gleam estão disponíveis para vários editores populares. Se existir um para o seu editor de preferência, considere instalá-lo para realce de sintaxe e outras conveniências.

  * **Vim** - `https://github.com/gleam-lang/gleam.vim`
  * **Emacs** - `https://github.com/gleam-lang/gleam-mode`
  * **Visual Studio Code** - `https://github.com/gleam-lang/vscode-gleam`
  * **Sublime Text** - `https://github.com/digitalcora/sublime-text-gleam`
  * **Atom** - `https://github.com/itsgreggreg/language-gleam`
  * **Gedit** - `https://github.com/DannyLettuce/gleam_gedit`

## Strand: Gleam em produção

Ref. https://gleam.run/case-studies/strand/

Otimizando para manutenibilidade
Um estudo de caso da Gleam em produção na Strand

[A Strand](https://www.strand-uk.com/) é uma agência de marketing sediada em Londres, Reino Unido. A empresa é especializada em redação publicitária e criação de conteúdo para muitas das maiores empresas de tecnologia empresarial do mundo, executando programas de marketing que produzem centenas de white papers, estudos de caso, postagens de blog e artigos todos os anos.

### Desafio

Por muitos anos, a Strand utilizou um sistema de gerenciamento de projetos personalizado para dar suporte aos aspectos operacionais de seus negócios — criação de projetos, acompanhamento de atividades e gerenciamento de documentos. No entanto, gerenciar os aspectos financeiros do gerenciamento de projetos sempre foi um processo mais manual, com o uso de planilhas para garantir que o trabalho faturável fosse atribuído aos pedidos de compra e faturas corretos.

“Pouco antes da pandemia, decidimos criar um novo sistema de gestão financeira”, lembra Ed Kelly, Diretor de Tecnologia da Strand. “Acabou sendo uma decisão muito oportuna. Quando tivemos que migrar para o trabalho remoto, o fato de todos poderem acompanhar seu trabalho faturável em um sistema centralizado nos ajudou a manter o negócio nos trilhos.”

O novo sistema rapidamente se tornou parte integrante do fluxo de trabalho diário da Strand, e os usuários começaram a solicitar novos recursos. À medida que o aplicativo se tornava gradualmente maior e mais complexo, a pequena equipe de desenvolvimento da empresa queria garantir que o sistema permanecesse confiável, sustentável e escalável.

“Quase por acidente, o que lançamos como protótipo se tornou um aplicativo crítico para os negócios”, diz Ed Kelly. “Nossos recursos de desenvolvimento são limitados, então nossa principal prioridade era garantir que o sistema funcionasse para sempre, sem precisar de manutenção constante. Ao mesmo tempo, queríamos manter a base de código simples e acessível, para que fosse fácil para os desenvolvedores voltarem a usá-la quando precisassem fazer alguma alteração. O desafio para nós era construir e manter esse sistema crítico para os negócios de forma econômica, com nossa equipe de desenvolvimento enxuta.”

### Solução

Como uma pequena empresa, a Strand não tem medo de inovar. "Temos sistemas escritos em linguagens de programação tradicionais, como Python e JavaScript, mas nossa estratégia é escolher a melhor ferramenta para o trabalho, não apenas a mais popular", explica Ed Kelly. "O Gleam atendeu perfeitamente às nossas necessidades."

Os recursos do Gleam que atraíram Strand foram sua robustez e facilidade de manutenção, sua combinação de recursos de linguagem modernos com acesso a um amplo ecossistema de bibliotecas testadas em campo e de nível de produção, e seu forte foco na experiência do desenvolvedor.

#### Segurança e confiabilidade

“Gleam é uma linguagem segura”, explica Ed Kelly. “Em termos gerais, se você escrever um programa em Gleam puro, ele certamente não travará. E nos casos em que você precisa interagir com código escrito em outras linguagens menos seguras, há uma segunda camada de proteção fornecida pela plataforma de tempo de execução do Gleam, a BEAM.”

O BEAM foi desenvolvido pela Ericsson na década de 1980 como uma plataforma tolerante a falhas para gerenciar grandes centrais telefônicas que precisam lidar com milhares de chamadas simultaneamente e nunca podem ser desconectadas para manutenção. A ideia central é que a plataforma seja capaz de dividir aplicações em milhares ou até milhões de processos leves. Cada processo é executado de forma independente e pode se comunicar enviando mensagens entre si. Se um processo individual falhar, ele pode ser reiniciado automaticamente sem afetar nenhum dos outros processos.

“O aplicativo que criamos é composto por vários serviços que interagem com o mundo externo”, explica Ed Kelly. “Por exemplo, temos um serviço que baixa periodicamente as taxas de câmbio do site do governo do Reino Unido e outro que sincroniza os dados com o nosso sistema de gerenciamento de projetos. O BEAM garante que, se houver algum problema imprevisto com qualquer um desses serviços externos, ele não travará o nosso aplicativo.”

#### Modernidade e pragmatismo

O Gleam foi projetado para ser uma linguagem simples que oferece recursos poderosos, mas permanece resolutamente prática. "Ele nos dá acesso a recursos de linguagens de programação mais acadêmicas, mas as torna acessíveis", diz Ed Kelly. "A linguagem é pequena — um desenvolvedor experiente pode aprendê-la em uma tarde — e há um forte foco em ter apenas uma maneira de fazer as coisas. Isso significa que você pode integrar novos desenvolvedores a uma base de código do Gleam rapidamente."

Como o código do Gleam roda no BEAM, os desenvolvedores também têm fácil acesso a milhares de bibliotecas de software de alta qualidade. "O ecossistema de bibliotecas do Gleam cresce rapidamente a cada ano", afirma Ed Kelly. "E, quando necessário, também podemos recorrer a 40 anos de bibliotecas testadas em outras linguagens BEAM, como Erlang e Elixir. A linguagem prioriza o pragmatismo em vez da pureza, o que nos ajuda a realizar as tarefas."

#### Experiência do desenvolvedor

Na experiência de Strand, as ferramentas de desenvolvedor do Gleam são inigualáveis. "Ao baixar o Gleam, você obtém todas as ferramentas em um único pacote", diz Ed Kelly. "Ele se integra ao seu editor de código para fornecer recursos como formatação, sugestões e preenchimento automático. As mensagens de erro são muito amigáveis ​​e úteis — quando você comete um erro, o Gleam frequentemente informa o que você deveria ter escrito. E é muito rápido — os dias de fazer uma pausa para o café enquanto espera a compilação do seu código acabaram."

Ele acrescenta: “Estamos entrando em uma nova era de codificação assistida por IA e, no momento, é difícil prever como isso se desenrolará. Mas, se eu tivesse que apostar, diria que, a longo prazo, as IAs têm mais probabilidade de gerar código de alta qualidade em uma linguagem como o Gleam. O Gleam torna rápido e fácil para as IAs verificarem seu código, obterem feedback instantâneo e iterarem. Isso deve ser uma vantagem em comparação com linguagens que são lentas para construir, têm mensagens de erro enigmáticas e não conseguem detectar erros em tempo de construção.”

#### Adoção incremental

Para a Strand, a introdução do Gleam em sua base de código foi um processo incremental e de baixo risco. "Começamos com apenas um serviço: nossa integração com a API de taxas de câmbio do governo do Reino Unido", diz Ed Kelly. "Ficamos tão satisfeitos com o resultado que reescrevemos alguns de nossos outros serviços no Gleam. E, recentemente, decidimos dar ao Gleam um papel ainda mais importante, substituindo toda a parte do backend que se comunica com nosso banco de dados. Estamos muito confiantes de que isso nos proporcionará uma base de código mais segura e de fácil manutenção em geral."

#### Resultados

Como uma das primeiras empresas do mundo a usar o Gleam em produção, a Strand assumiu o risco. Dois anos depois, a equipe de desenvolvimento está muito feliz com a decisão. "Desde que começamos, a linguagem amadureceu bastante e atingiu um estado estável", diz Ed Kelly. "A comunidade cresceu enormemente e há um verdadeiro burburinho em torno da linguagem. Ela está até começando a ser reconhecida por analistas tradicionais do setor, como a Thoughtworks, em seu Technology Radar . Acredito que, hoje, o Gleam é uma escolha segura e sólida para empresas usarem em produção."

Desde o lançamento, o código do Gleam no aplicativo da Strand tem se mostrado extremamente sólido. "Não tivemos nenhuma falha relacionada ao Gleam e, mesmo quando houve problemas com outras partes do sistema, o BEAM manteve tudo funcionando", diz Ed Kelly. "Conseguimos corrigir problemas sem que nossos usuários percebessem que havia algo errado."

A simplicidade da linguagem e a sofisticação das ferramentas de desenvolvimento também ajudam a manter a base de código sustentável. "Mesmo quando não olhamos a base de código por algumas semanas, é fácil voltar a ela", diz Ed Kelly. "A linguagem e as ferramentas nos incentivam gentilmente a usar um estilo consistente e idiomático, e a escrever de forma clara e simples, sem tentar ser muito inteligentes. Assim, não precisamos perder tempo tentando entender o que nós mesmos do passado estávamos tentando fazer com o código que escrevemos seis meses atrás."

Ele conclui: “Adotar uma nova linguagem é sempre uma aposta, mas o Gleam valeu a pena. A abordagem de segurança e tolerância a falhas, com todos os cuidados necessários, nos proporcionou um sistema que funciona de forma confiável, dia após dia, sem supervisão e manutenção constantes. Para uma equipe como a nossa, com muitas outras prioridades e projetos nos quais precisamos trabalhar, a confiança que o Gleam nos dá vale ouro.”

## 🌈 Mascote

"Lúcia"(pt_BR) -> ["Lucy"(en_US)](https://github.com/gleam-lang/gleam/blob/main/images/lucy.png)
> Ambos os nomes têm a mesma origem latina, vindo de "Lux", que significa "luz"

![Lúcia](https://github.com/user-attachments/assets/07c159af-d72d-47d1-8b1f-b5f8a64f451b)

![Lúcia sorrindo](https://github.com/user-attachments/assets/e34b6475-8f5c-408e-a893-283fb350ab28)

![Lúcia sorrindo rotacionado](https://github.com/user-attachments/assets/90ea6373-4c13-4b50-b1cc-a66a31ac5686)

