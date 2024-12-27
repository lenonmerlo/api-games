# API Games

Este é um projeto básico de API RESTful para manipular uma coleção de jogos. Ele utiliza o framework **Express** e demonstra operações CRUD e manipulação de dados relacionados a gêneros de jogos.

## 🚀 Funcionalidades

A API fornece os seguintes endpoints:

### Endpoints principais:

- **GET /games**: Retorna a lista de todos os jogos.
- **GET /games/:id**: Retorna informações de um jogo específico pelo seu `id`.
- **POST /games**: Adiciona um novo jogo à coleção.
- **PUT /games/:id**: Atualiza informações de um jogo existente (nome e ano).
- **DELETE /games/:id**: Remove um jogo da coleção.

### Manipulação de gêneros:

- **POST /games/:id/genres**: Adiciona um novo gênero ao jogo pelo `id`.
- **DELETE /games/:id/genres/:name**: Remove um gênero de um jogo específico pelo `id`.

## 📦 Tecnologias utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Body-parser](https://www.npmjs.com/package/body-parser)
- [Nodemon](https://www.npmjs.com/package/nodemon) (para desenvolvimento)

## 🛠️ Instalação e execução

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/lenonmerlo/api-games.git
   cd api-games
   npm start

