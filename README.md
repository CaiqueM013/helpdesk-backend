# Help Desk - Backend

Backend de sistema de gestão de chamados desenvolvido em Node.js, responsável pelo gerenciamento de usuários, chamados e autenticação.

---

## Tecnologias

- Node.js
- Express / NestJS (ajusta aqui)
- PostgreSQL
- Docker (se tiver)
- JavaScript / TypeScript

---

## Funcionalidades

- Autenticação de usuários  
- CRUD de chamados  
- Controle de status (aberto, em andamento, finalizado)  
- Gerenciamento de usuários  
- Integração com banco de dados relacional  
- Validação de dados  

---

## Arquitetura

A aplicação segue separação em camadas:

- Controller → entrada das requisições  
- Service → regras de negócio  
- Repository → acesso ao banco  

---

## Segurança

- Validação de dados  
- Controle de acesso  
- Estrutura preparada para autenticação JWT  

---

## Como rodar o projeto

```bash
npm install
npm start
