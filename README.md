# ⚙️ Cadastro de Usuários - API (Backend)

Esta é a API REST responsável pelas regras de negócio e persistência de dados do sistema de cadastro de usuários.

A aplicação realiza operações completas de CRUD utilizando Node.js, Express, Prisma ORM e MongoDB Atlas.

---

## 🚀 Tecnologias Utilizadas

O backend foi desenvolvido utilizando as seguintes tecnologias:

- **Node.js** — Ambiente de execução JavaScript.
- **Express** — Framework para gerenciamento de rotas e middlewares.
- **Prisma ORM** — ORM moderno para integração com banco de dados.
- **MongoDB Atlas** — Banco de dados NoSQL hospedado na nuvem.
- **CORS** — Compartilhamento seguro entre diferentes origens.
- **Dotenv** — Gerenciamento de variáveis de ambiente.

---

## 📁 Estrutura do Projeto

```bash
cadastro-usuarios-backend/
│
├── generated/
├── node_modules/
├── prisma/
│   └── schema.prisma
│
├── .env
├── .gitignore
├── package.json
├── package-lock.json
├── README.md
└── server.js
```

---

## 🔌 Rotas da API

| Método | Rota | Descrição |
|--------|------|------------|
| GET | `/usuarios` | Lista todos os usuários |
| POST | `/usuarios` | Cria um novo usuário |
| PUT | `/usuarios/:id` | Atualiza um usuário pelo ID |
| DELETE | `/usuarios/:id` | Remove um usuário |

---

## ⚙️ Como Executar o Projeto Localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/JoaoDev-Pro/cadastro-usuarios-backend.git
```

---

### 2. Entrar na pasta do projeto

```bash
cd cadastro-usuarios-backend
```

---

### 3. Instalar as dependências

Com NPM:

```bash
npm install
```

Ou com Yarn:

```bash
yarn
```

---

### 4. Configurar as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto:

```env
DATABASE_URL="SUA_URL_DO_MONGODB"
```

---

### 5. Gerar o Prisma Client

```bash
npx prisma generate
```

---

### 6. Iniciar o servidor

Com NPM:

```bash
npm run dev
```

Ou com Yarn:

```bash
yarn dev
```

---

## 🌐 Funcionalidades

- ✅ CRUD completo de usuários
- ✅ Integração com MongoDB Atlas
- ✅ API REST
- ✅ Tratamento de rotas
- ✅ Integração com Prisma ORM
- ✅ Estrutura escalável

---

## 👨‍💻 Autor

Desenvolvido por João Victor.

🌐 Portfólio:  
https://joaodev-pro.vercel.app
