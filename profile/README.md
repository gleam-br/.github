## Seja bem-vindo ao GleamBR 👋

:tada: GleamBR é uma comunidade brasileira sobre a linguagem de programação [gleam-lang](https://gleam.run).
Podemos também considerar uma plataforma de produção e curadoria de conteúdo, em português, voltada para a comunidade [gleam-lang](https://gleam.run).

- [gleam.dev.br](https://gleam.dev.br)
- [gleam-lang.com.br](https://gleam-lang.com.br)

## 🌈 Mascote

"Lúcia"(pt_BR) -> ["Lucy"(en_US)](https://github.com/gleam-lang/gleam/blob/main/images/lucy.png)
> Ambos os nomes têm a mesma origem latina, vindo de "Lux", que significa "luz"

![Lúcia](https://github.com/user-attachments/assets/07c159af-d72d-47d1-8b1f-b5f8a64f451b)

![Lúcia sorrindo](https://github.com/user-attachments/assets/e34b6475-8f5c-408e-a893-283fb350ab28)

![Lúcia sorrindo rotacionado](https://github.com/user-attachments/assets/90ea6373-4c13-4b50-b1cc-a66a31ac5686)

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

## 🍿 Algumas bibliotecas

- [lutre.build](https://lustre.build): Uma estrutura para criar aplicativos Web no Gleam!
- [rsvp](https://github.com/hayleigh-dot-dev/rsvp): Envie solicitações HTTP de aplicativos em Lustre ou web-components.
- [Cigone](https://github.com/Billuc/cigogne): Migrações p/ banco de dados.
- [Job Processing](https://github.com/Pevensie/m25): Processamento de jobs.
- [Gausy](https://github.com/leonqadirie/gauzy): Filtro probabilístico de Gausy.
- [Tempo](https://github.com/jrstrunk/tempo): Data e hora em gleam.
- [Spotless](https://github.com/CrowdHailer/gleam_spotless): OAuth em gleam.

## 🧙 Blog posts

- https://keii.dev/posts/the-basics-for-a-fullstack-spa-in-gleam
