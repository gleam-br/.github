# Roadmap Gleam-BR: Sistemas Lúcidos

Este roteiro define a transição das nossas bibliotecas base para o ecossistema de SaaS robusto (BPM + KVM).

## 🟢 Fase 1: Fundação & Infraestrutura (Atual)
*Foco: Ferramentas de desenvolvimento e bibliotecas base testadas em consultoria real.*

- [x] **vite-plugin-gleam:** Integração nativa com o ecossistema Vite.
- [x] **create-vite-lustre:** Scaffolding padronizado para a fundação.
- [ ] **gbr_shared / gbr_js / gbr_erl:** Consolidação das pontas de interoperabilidade.
- [ ] **gbr_ui:** Finalização do Design System inicial (Lustre + Tailwind).

## 🟡 Fase 2: Identidade & Conteúdo (Próximos Passos)
*Foco: Provar a stack no nosso próprio "quintal".*

- [ ] **Blog Gleam-BR:** Migração do design *Journal* para Gleam/Lustre.
- [ ] **Documentação:** Criação de guias técnicos sobre FFI e interoperabilidade BEAM/JS.
- [ ] **Comunidade:** Lançamento oficial da Licença Ética (baseada na Dharma License).

## 🟠 Fase 3: Os Pilares (BPM + KVM)
*Foco: O "Fosso Tecnológico" da Freunde Von Ideen.*

### BPM (Business Process Manager)
- [ ] **Core:** Motor de estados baseado em atores OTP.
- [ ] **Engine:** Execução síncrona/assíncrona de processos definidos em código.
- [ ] **Distribuído:** Orquestração across-nodes via N2O-Gleam.

### KVM (Key Value Manager)
- [ ] **Abstração:** Interface unificada para múltiplos backends de dados.
- [ ] **CQRS:** Implementação de projeções automáticas para o "Lado da Consulta".
- [ ] **SaaS Layer:** Multi-tenancy e isolamento de instâncias (YugabyteDB/ScyllaDB).

## 🔴 Fase 4: O SaaS Comercial (Gleam-lang.com.br)
*Foco: Monetização, suporte e infraestrutura gerenciada.*

- [ ] **Cloud:** Oferta de instâncias BPM/KVM como serviço.
- [ ] **Enterprise Support:** Consultoria especializada via FVideen.
- [ ] **Java Interop:** SDKs de integração para o mercado corporativo brasileiro.
