📝 Blog Pessoal - NestJS API

API REST desenvolvida com NestJS para um Blog Pessoal, com autenticação JWT e documentação interativa utilizando Swagger.

🚀 Tecnologias Utilizadas

⚡ NestJS

🟢 Node.js

🗄️ TypeORM

🐘 MySQL / PostgreSQL

🔐 JWT (Autenticação)

📘 Swagger (Documentação da API)

🧪 Jest (Testes)

📌 Funcionalidades

✅ Cadastro de usuário

✅ Login com autenticação JWT

✅ CRUD de Postagens

✅ CRUD de Temas

✅ Relacionamento entre Usuário, Postagem e Tema

✅ Documentação automática com Swagger

✅ Proteção de rotas com Bearer Token

🔐 Autenticação

A autenticação é feita via JWT (Bearer Token).

Após realizar login, copie o token gerado e:

Clique em Authorize no Swagger

📚 Documentação Swagger

Após iniciar o projeto, acesse:

http://localhost:4000/

Lá você poderá testar todos os endpoints diretamente pelo navegador.

⚙️ Como Executar o Projeto

1️⃣ Clonar o repositório

git clone https://github.com/imgabrielimartins/blogpessoal-nest.git

2️⃣ Instalar dependências

npm install

3️⃣ Rodar a aplicação

npm run start:dev

🧪 Rodar Testes

npm run test:e2e

🗂️ Estrutura do Projeto

src/
 ├── auth/
 ├── usuario/
 ├── postagem/
 ├── tema/
 ├── config/
 └── main.ts

📡 Principais Endpoints

🔑 Auth

POST /auth/login

👤 Usuário

POST /usuarios

GET /usuarios

GET /usuarios/:id

PUT /usuarios

DELETE /usuarios/:id

📝 Postagem

POST /postagens

GET /postagens

GET /postagens/:id

PUT /postagens

DELETE /postagens/:id

🏷️ Tema

POST /temas

GET /temas

GET /temas/:id

PUT /temas

DELETE /temas/:id

📌 Status do Projeto

🚧 Projeto acadêmico para prática de API REST com NestJS.

👩‍💻 Desenvolvedora

Desenvolvido por Gabrieli Martins

Estudante de Análise e Desenvolvimento de Sistemas 💻