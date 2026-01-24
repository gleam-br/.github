# Guia de Arquitetura e Estilo

> O guia técnico "Lei" para quem for codificar.

## Minimalismo Radical
- **Camadas:** Evite abstrações desnecessárias. Se o OTP resolve, não adicione uma biblioteca externa.
- **Protocolos:** Tudo é mensagem. O motor do nosso sistema é o protocolo binário (Bert-Gleam).
- **Imutabilidade:** O estado é uma projeção de um log de eventos. Tratamos o dado como uma corrente (feeds) em vez de tabelas estáticas.

## Padrões de Código
- **Gleam Puro:** Lógica de negócio sempre em `gbr_shared`.
- **FFI Seguro:** Interoperabilidade com Erlang e JS deve ser tratada como uma fronteira de risco, protegida por tipos `Result`.
- **Sufixos de Domínio:** Respeite rigorosamente a nomenclatura `_web`, `_srv`, `_svc`, `_app` para identificar o contexto tecnológico.
