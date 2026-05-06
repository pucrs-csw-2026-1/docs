# Serviço de Autenticação e Autorização

## Visão Geral

Na primeira entrega (T1), os grupos deverão desenvolver uma **API responsável pela autenticação e autorização de usuários**.

Este serviço deverá permitir não apenas atender aos requisitos funcionais, mas também praticar conceitos fundamentais de engenharia de software, arquitetura e operação de sistemas.

---

## Funcionalidades Obrigatórias

### Autenticação
- Cadastro de usuários
- Autenticação (login)
- Emissão de tokens de acesso

---

### Autorização
- Validação de permissões
- Controle de acesso (ex: JWT, RBAC, etc.)

---

## Requisitos Técnicos

### Arquitetura
- Serviço reutilizável, independente
- Estruturado conforme boas práticas de design
- Executável em ambiente local
- Documento de Arquitetura (ADR) justificando decisões

---

### Implementação
- Desenvolvido com tecnologias adequadas para API
- Testes unitários para funcionalidades críticas
- Estrutura de código clara e manutenível

---

### Documentação
- **Swagger/OpenAPI** especificando todos os endpoints
- Instruções para setup e execução local
- Exemplos de uso

---

### CI/CD
- Pipeline configurado (GitHub Actions)
- Execução automática de testes
- Build automatizado da aplicação

---

### IA
- Logs de uso da IA com a extensão [Cognitrace](https://marketplace.visualstudio.com/items?itemName=schardosim.cognitrace) do VSCode, ou os hooks disponíveis [neste repositório](https://github.com/simaoj/prompt-auto-log)
