<h1 align="center">
    <img alt="ReactJS" src="cover-reactjs.png" width="100%"/>
    <br>Criando um hook de carrinho de compras<br/>
</h1>

<p align="center">
  <a href="#notebook_with_decorative_cover-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#dart-desafio">Desafios</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-executando">Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#page_facing_up-licença">Licença</a>
</p>

## :notebook_with_decorative_cover: Sobre
O WatchMe é uma aplicação desenvolvida em ReactJs que permite a listagem de filmes
em cartazes filtrados por seu gênero.

## :dart: Desafio
A aplicação já está totalmente funcional mas grande parte do seu código está diretamente no arquivo App.tsx. Para resolver isso da melhor forma, é necessário dividir a aplicação em pelo menos duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.

- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já deve começar como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.

## :computer: Tecnologias
- [Typescript](https://www.typescriptlang.org/)
- [ReactJS](https://reactjs.org/)
- [Fake API com JSON Server](https://github.com/typicode/json-server)

## :rocket: Executando

- ### **Pré-requisitos**
  - **[Git](https://git-scm.com/)**
  - Um gerenciador de Pacotes: **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.

1. Faça um clone do repositório:
```sh
  git clone https://github.com/denilsondsousa/02-desafio-componetizando-a-aplicacao
```

2. Para executar a aplicação:
```sh
  # Primeiro: instale as dependências do projeto
  $ yarn # ou npm install

  # Segundo: Inicializa a Fake API
  $ yarn server # ou npm server
  
  # Inicializando a aplicação:
  $ yarn dev # ou npm start
```

## :page_facing_up: Licença
Esse projeto está sob a licença MIT.