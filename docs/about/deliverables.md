# Entregas

O sistema será composto por três componentes principais.

## 1. Serviço de Autenticação e Autorização (T1)

Na primeira etapa, iremos desenvolver uma **API responsável pela autenticação e autorização de usuários**.

Este serviço deverá permitir:

- Cadastro de usuários
- Autenticação (login)
- Emissão de tokens de acesso
- Validação de permissões

O objetivo desta etapa é construir um **serviço reutilizável**, que poderá ser utilizado por outros sistemas ou microsserviços.

Esse serviço será utilizado pelos demais componentes do projeto.

---

## 2. Microsserviço (T2)

Na segunda etapa, iremos desenvolver um **microsserviço responsável por um dos domínios da aplicação**, ou seja, pela lógica de negócio relacionada aos eventos.

Esse serviço deverá utilizar o sistema de autenticação desenvolvido no **T1** de outro grupo para proteger seus endpoints.

Nesta etapa os iremos praticar conceitos como:

- Design de APIs
- Separação de responsabilidades
- Integração entre serviços
- Desenvolvimento de microsserviços

---

## 3. Cliente (T3)

Na terceira etapa, iremos desenvolver um **cliente web** que consumirá as APIs construídas nas etapas anteriores.

Esta etapa tem como objetivo explorar:

- Construção de interfaces com componentes reutilizáveis
- Integração com APIs REST
- Organização de aplicações frontend
