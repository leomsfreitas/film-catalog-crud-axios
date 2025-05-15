# Film Catalog with React and AXIOS

Este repositório contém o projeto desenvolvido para o componente curricular **"Programação Web 2"**, com o objetivo de praticar operações CRUD (Create, Read, Update, Delete) utilizando a biblioteca Axios para comunicação com uma API pública.

## 📋 Descrição do Projeto

A aplicação é uma SPA (Single Page Application) construída com React, consumindo a API pública [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts) para realizar as seguintes operações:

- **Create**: Criação de um novo post.
- **Read**: Leitura de todos os posts existentes.
- **Update**: Atualização de posts existentes.
- **Delete**: Remoção de posts.

Essas operações são realizadas por meio de chamadas HTTP com Axios, e o estado da aplicação é gerenciado de forma eficiente utilizando os hooks do React `useState, useEffect`.

## 💻 Tecnologias Utilizadas

- React (Vite.js)
- [Axios](https://axios-http.com/)
- JavaScript (ES6+)
- HTML5
- CSS3

## 🚀 Funcionalidades

- Interface moderna para listagem e gerenciamento de posts.
- Formulário para criação e edição de posts com validação.
- Exclusão de posts com feedback visual imediato.
- Consumo de API pública com Axios.
- Manipulação do estado via React Hooks.

## 📁 Estrutura do Projeto
```
film-catalog-crud-axios/
├── public/
├── src/
│   ├── components/      # Componentes reutilizáveis
│   ├── pages/           # Páginas principais
│   ├── services/        # Configuração do Axios e chamadas à API
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── projeto.pdf          # Descrição do projeto
└── README.md
```

## 📌 Observações
A API JSONPlaceholder não persiste alterações — as operações de criação, atualização e exclusão são simuladas apenas no frontend.

Este projeto tem fins educacionais e é utilizado como base para o aprendizado de requisições HTTP e manipulação de DOM.

## 📚 Créditos
Projeto desenvolvido como parte da disciplina **PRW2**, sob orientação do professor responsável.