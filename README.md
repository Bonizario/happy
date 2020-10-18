<p align="center">
  <img alt="happy" title="happy" src="./assets/banner.png" />
</p>

<h1 align="center">
  Leve felicidade para o mundo
</h1>

<p align="center">
  <a href="https://github.com/Bonizario/happy/">
    <img
      alt="GitHub language count"
      src="https://img.shields.io/github/languages/count/Bonizario/happy?color=29B6D1"
    />
  </a>

  <a href="https://github.com/Bonizario/happy/">
    <img
      alt="Repository size"
      src="https://img.shields.io/github/repo-size/bonizario/happy?color=29B6D1"
    />
  </a>

  <a href="https://www.linkedin.com/in/gabriel-bonizario/">
    <img
      alt="Linkedin"
      src="https://img.shields.io/badge/Linkedin-gabriel--bonizario-29B6D1?style=flat-square&logo=Linkedin&logoColor=white"
    />
  </a>

  <a href="https://github.com/bonizario/happy/commits/master">
    <img
      alt="GitHub last commit"
      src="https://img.shields.io/github/last-commit/bonizario/happy?color=29B6D1"
    />
  </a>

  <a href="https://github.com/Bonizario/happy/blob/master/LICENSE">
    <img
      alt="License"
      src="https://img.shields.io/github/license/bonizario/happy?color=FFD666"
    />
  </a>
</p>

## 🎉 Sobre

**happy** é uma plataforma que ajuda pessoas a encontrarem orfanatos próximos para levar felicidade a milhares de crianças.

Este projeto foi desenvolvido usando Node.js, ReactJS e React Native, durante a 3ª edição da Next Level Week ministrada pela [Rocketseat](https://rocketseat.com.br/).

<br />

## 💻 Features

- Localizar orfanatos próximos pelo mapa;
- Visualizar as informações e horários de visita de um orfanato;
- Ver rotas no Google Maps até um orfanato;
- Entrar em contato via _whatsapp_;
- Cadastrar novas instituições;

<br />

## 🎨 Layout

Os layouts da aplicação estão disponíveis no Figma: [Web](http://figma.com/file/X5vjP69Y0H9C8aa5QqorzH/Happy-Web), [Mobile](https://www.figma.com/file/5lunlSxDHchxU312BJntQL/Happy-Mobile).

<br />

## 🔌 Tecnologias

### Front-end
- [React](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Styled Components](https://styled-components.com/)
- [Typescript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)

### Back-end
- [Node.js](https://nodejs.org/pt-br/)
- [Express](https://github.com/expressjs/express)
- [Typescript](https://www.typescriptlang.org/)

### Ambiente de desenvolvimento
- [VS Code][vc] com [EditorConfig][vceditconfig], [ESLint][vceslint] e [Prettier][vcprettier]

<br />

## 🤔 Como executar

Para clonar esse repositório pelo terminal, é necessário possuir o [Git](https://git-scm.com/) instalado em sua máquina.

```bash
# Clone o repositório
$ git clone https://github.com/Bonizario/happy.git

# Entre na pasta do projeto
$ cd happy
```

<br />

Para instalar as dependências e executar o projeto, é necessário possuir o [Node.js](https://nodejs.org/pt-br/) instalado em sua máquina, bem como um gerenciador de pacotes: [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/).

### Usando Yarn
```bash
# Instale as dependências do back-end
$ cd backend && yarn

# Execute as migrations do TypeORM
$ yarn typeorm migration:run

# Execute a api em Node.js
$ yarn dev:server

# Instale as dependências do front-end web
$ cd ../web && yarn

# Execute o front-end em ReactJS
$ yarn start
```

<br />

### Usando npm
```bash
# Instale as dependências do back-end
$ cd backend && npm install

# Execute as migrations do TypeORM
$ npm run typeorm migration:run

# Execute a api em Node.js
$ npm run dev:server

# Instale as dependências do front-end web
$ cd ../web && npm install

# Execute o front-end em ReactJS
$ npm start
```

<br />

## 💭 Como contribuir

Caso queira contribuir, seja corrigindo bugs, adicionando comentários ou novas features, você pode seguir o seguinte tutorial:

- Faça um **[fork](https://help.github.com/pt/github/getting-started-with-github/fork-a-repo)** desse repositório
- **[Clone](https://help.github.com/pt/github/creating-cloning-and-archiving-repositories/cloning-a-repository)** o repositório que você fez o fork em seu computador
- Crie uma branch com a sua feature: `git checkout -b minha-alteracao`
- Envie suas alterações para a _staging area_: `git add .`
- Faça um commit contando o que você fez: `git commit -m "feat: minha nova alteracao!"`
- Faça um push para a sua branch: `git push origin minha-alteracao`
- Agora é só abrir uma _pull request_

_Caso tenha alguma dúvida, confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions/blob/master/translations/README.pt_br.md) :)_

<br />

## 📝 License

Esse projeto está sob a licença MIT. Consulte [LICENSE](https://github.com/Bonizario/happy/blob/master/LICENSE) para mais informações.

<br />

## 📮 Entre em contato

**Linkedin**: https://www.linkedin.com/in/gabriel-bonizario/

<br />

---

Desenvolvido por **Gabriel Bonizário** 👋🏻

[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[vcprettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
