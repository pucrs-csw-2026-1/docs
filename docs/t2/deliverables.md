# Microsserviço

## Visão Geral

Na segunda entrega (T2), os grupos deverão desenvolver um **microsserviço funcional** responsável por um dos domínios da aplicação, com foco na lógica de negócio e na integração com o serviço de autenticação desenvolvido no T1.

Este componente deve demonstrar organização, independência e aderência a boas práticas de desenvolvimento de microsserviços.

---

## Entregáveis Obrigatórios

### Microsserviço
- Implementação de um microsserviço funcional
- Estruturado conforme boas práticas
- Executável em ambiente local

---

### Integração com Autenticação
- Consumo do serviço de autenticação/autorização do T1
- Proteção de endpoints com controle de acesso
- Validação de tokens e permissões

---

### Documento de Arquitetura (ADR)
- Registro das decisões arquiteturais
- Justificativa das tecnologias escolhidas
- Análise de trade-offs

---

### Documentação da API
- **Swagger/OpenAPI** para o microsserviço
- Instruções para setup e execução local
- Exemplos de uso dos endpoints

---

### CI/CD (Integração e Entrega Contínua)
- Pipeline configurado (GitHub Actions)
- Execução automática de:
  - Testes unitários
  - Build da aplicação
- Geração de releases

---

### IA
- Logs de uso da IA com a extensão [Cognitrace](https://marketplace.visualstudio.com/items?itemName=schardosim.cognitrace) do VSCode, ou os hooks disponíveis [neste repositório](https://github.com/simaoj/prompt-auto-log)