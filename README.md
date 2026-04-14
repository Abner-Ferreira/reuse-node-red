# 🛡️ Painel Administrativo - ReUse (Node-RED)

Este projeto consiste em um painel administrativo desenvolvido com Node-RED Dashboard para gerenciamento de produtos.

⚠️ **Importante:** Este painel depende da API do projeto ReUse (Next.js).  
Sem a API rodando, o painel não funcionará corretamente.

---

## 🚀 Funcionalidades

- Listagem de produtos via API
- Atualização manual e automática
- Exclusão de produtos com confirmação
- Feedback visual com notificações (toasts)

---

## 🧩 Tecnologias

- Node-RED
- Node-RED Dashboard
- Next.js (API externa)
- Prisma ORM

---

## 🔗 Integração com API

Este painel consome a API do projeto ReUse:

- GET /api/products → lista produtos
- DELETE /api/products/:id → remove produto

📌 **Projeto da API (Next.js):**
👉 https://github.com/Abner-Ferreira/reuse

---

## ▶️ Como rodar o projeto completo

### 1. Rodar a API (Next.js)

Clone o projeto ReUse:

```
git clone https://github.com/Abner-Ferreira/reuse
cd reuse
npm install
npm run dev
```

A API estará disponível em:
```
http://localhost:3000
```

---

### 2. Rodar o Node-RED

Instale e execute:

```
npm install -g node-red
node-red
```

Acesse:
```
http://localhost:1880
```

---

### 3. Importar o fluxo

- Menu ☰ → Import
- Selecione `flows.json`

---
