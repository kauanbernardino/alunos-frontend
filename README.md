# Minha Escola: front-end (React)

Front-end em React para o cadastro de alunos e disciplinas, com telas de login e registro. Consome a API em C# do repositório [alunos-api](https://github.com/kauanbernardino/alunos-api).

## Funcionalidades

- Telas de **login** e **registro** de usuário
- **Alunos**: listar, incluir, editar e excluir (nome, e-mail e idade), com janelas modais
- **Disciplinas**: listar, incluir, editar e excluir
- Menu de navegação com rotas e botão **Sair**
- Configurado para publicação no **Vercel**

## Tecnologias

React 19 · React Router · Axios · Bootstrap e Reactstrap · Create React App

## Como rodar

Pré-requisito: Node.js.

```bash
git clone https://github.com/kauanbernardino/alunos-frontend.git
cd alunos-frontend/alunostat1-main
npm install
npm start
```

O app abre em http://localhost:3000.

As chamadas à API usam o endereço `https://api-escola-hroh.onrender.com`, escrito no código dos arquivos `src/Alunos.js`, `src/Disciplinas.js`, `src/Login.js` e `src/Register.js`. Para usar uma API local, troque esse endereço (por exemplo, para `http://localhost:5000`).

## Próximos passos

- Mover o endereço da API para uma variável de ambiente
- Mandar o token JWT nas requisições e proteger as telas por login
- Mover o projeto para a raiz do repositório (hoje está na pasta `alunostat1-main`)

## Sobre o projeto

Trabalho da faculdade, desenvolvido com apoio de ferramentas de IA.

## Autor

Kauan Bernardino da Silva
