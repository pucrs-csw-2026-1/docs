# Cliente Web

## Visão Geral

Na terceira entrega (T3), os grupos deverão desenvolver um **cliente web** responsável por consumir as APIs construídas nas etapas anteriores (T1 e T2), oferecendo uma interface para os usuários finais interagirem com o sistema de gestão de eventos.

Este cliente deverá permitir não apenas atender aos requisitos funcionais, mas também praticar conceitos fundamentais de construção de interfaces, integração com APIs REST e organização de aplicações frontend.

---


### Domínio do Microsserviço (T2)

As telas e fluxos desta seção variam de acordo com o domínio do microsserviço/microfrontend desenvolvido por cada grupo no T2. Independentemente do domínio escolhido, o cliente deverá oferecer:

- Telas que consumam os principais endpoints do microsserviço desenvolvido no T2
- Fluxos principais do domínio (ex: listagem, criação, edição e exclusão dos recursos, conforme o que o microsserviço expõe)
- Tratamento de regras de autorização específicas do domínio (ex: ações restritas por papel/permissão do usuário)

---

## Requisitos Técnicos

### Arquitetura
- Aplicação client-side que reutiliza os serviços de T1 e T2 desenvolvidos pelo grupo
- Estruturada conforme boas práticas de design (componentização, separação de responsabilidades)
- Executável em ambiente local
- Documento de Arquitetura (ADR) justificando decisões

---

### Implementação
- Desenvolvido com tecnologias adequadas para construção de SPAs (ex: React, Angular, Next.js, Vite)
- Consumo das APIs do T1 (autenticação/autorização) e T2 (microsserviço) via REST
- Tratamento de estados de carregamento, erro e sessão/token expirado
- Testes para funcionalidades críticas

---

### Documentação
- Instruções para setup e execução local
- Exemplos de uso cobrindo os principais fluxos da aplicação

---

### CI/CD
- Pipeline configurado (GitHub Actions)
- Execução automática de testes
- Build automatizado da aplicação

---

### IA
- Logs de uso da IA com a extensão [Cognitrace](https://marketplace.visualstudio.com/items?itemName=schardosim.cognitrace) do VSCode, ou os hooks disponíveis [neste repositório](https://github.com/simaoj/prompt-auto-log)
