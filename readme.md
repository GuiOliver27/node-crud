# API RESTful com Express.js e MongoDB

## 📖 Descrição

Este é um sistema de cadastro de usuários em Node.js que utiliza o framework Express.js
e a biblioteca Mongoose para criar uma API RESTful para operações CRUD (Create, Read, Update, Delete) em um banco de dados MongoDB.

## 🛠️ Rotas
- POST /person: Cria uma nova pessoa no banco de dados.
- GET /person: Retorna todas as pessoas no banco de dados.
- GET /person/:id: Retorna uma pessoa com um ID específico.
- PATCH /person/:id: Atualiza os dados de uma pessoa com base em seu ID.
- DELETE /person/:id: Exclui uma pessoa com base em seu ID.

## Executando Localmente

Clone o projeto

```bash
  git init
  git@github.com:GuiOliver27/node-crud.git
```

Entre no diretório do projeto

```bash
  cd node-crud
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm start
```

## Contribuições
Contribuições são bem-vindas! Se você encontrar um problema ou desejar adicionar novos recursos, sinta-se à vontade para criar um Pull Request.

## Licença
Este projeto está licenciado sob a Licença MIT.
