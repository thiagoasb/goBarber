<h1 align="center">
  <img src="./web/src/assets/logo.svg" alt="logo" width="200">
</h1>

<p align="center">
    <img alt="autor thiagoasb" src="https://img.shields.io/badge/author-thiagoasb-orange">
    <img alt="license MIT" src="https://img.shields.io/badge/license-MIT-orange">
  
<p>

# Indice

- [About](#-about)
- [REST API](#-REST-API)
    - [Technologies](#-technologies)
    - [How to run](#-how-to-run)
- [Web client](#-web-client)
    - [Demonstration](#-demonstration)
    - [Technologies](#-technologies)
    - [How to run](#-how-to-run)
- [Mobile client](#-front-end-mobile)
    - [Demonstration](#-demonstration)
    - [Technologies](#-technologies)
    - [How to run](#-how-to-run)
- [License](#-license)

## ✂️ About

This project is divided into three parts: API , web client and mobile client. 

Project that helps users make appointments with barbers (mobile) and allows barbers to view their schedule each day (web).

---

## 🌐 REST API
### 🚀 Technologies
This project was developed using the following technologies:

- [NodeJS](https://nodejs.org/en/download/)
- [TypeScript](https://www.typescriptlang.org/docs/home)
- [Express](https://www.typescriptlang.org/docs/home)
- [Multer](https://www.typescriptlang.org/docs/home)
- [TypeORM](https://www.typescriptlang.org/docs/home)
- [JWT-token](https://www.typescriptlang.org/docs/home)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)
- [Redis](https://redis.io/)
- [date-fns](https://date-fns.org/)
- [Jest](https://jestjs.io/)
- [Yup](https://github.com/jquense/yup)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)

### ⚙️ Requirements:
 - Click in the button below and import the file .json on [Insomnia App](https://insomnia.rest/)
 - [Node.js](https://nodejs.org/en/download/)
 - [yarn](https://classic.yarnpkg.com/en/docs/install/#debian-stable) or [npm](https://www.npmjs.com/get-npm)
 - One instance of PostgreSQL, MongoDB and Redis (suggestion: in docker)

 <p align="center">
  <a href="./Insomnia_goBarber.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

### 🏁 How to run
```bash

  # clonar o repositório
  $ git clone https://github.com/thiagoasb/goBarber.git

  # Enter in reposi
  $ cd goBarber

  # Instalar as dependências
  $ yarn install

  # Iniciar o projeto
  $ yarn dev:server

  # This application is running on port 3333 - acess <http://localhost:3333>

```
```bash
 #Para rodar os testes
 $ yarn test
```
---

## 💻 Web client
### 🎥 Demonstration


### 🚀 Technologies
This project was developed using the following technologies:
- [ReactJS](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/docs/home)
- [Styled-components](https://styled-components.com/)
- [Unform](https://github.com/Rocketseat/unform/blob/master/README.md)

### 🏁 How to run
```bash

  # clonar o repositório
  $ git clone https://github.com/thiagoasb/goBarber.git

  # Enter in reposi
  $ cd goBarber

  # Instalar as dependências
  $ yarn install

  # Iniciar o projeto
  $ yarn start

  # This application is running on port 3000 - acess <http://localhost:3000>

```
```bash
 #Para rodar os testes
 $ yarn test
```

---

## 📱 Mobile client
<h4 align="center"> 
	🚧  In construction...  🚧
</h4>

### 🎥 Demonstration

### 🚀 Technologies
This project was developed using the following technologies:
- [React-Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/docs/home)
- [Styled-components](https://styled-components.com/)
- [Unform](https://github.com/Rocketseat/unform/blob/master/README.md)

### 🏁 How to run
```bash

  # clonar o repositório
  $ git clone https://github.com/thiagoasb/goBarber.git

  # Enter in reposi
  $ cd goBarber

  # Instalar as dependências
  $ yarn install
  
  # Iniciar o projeto
  $ yarn start

  # This application is running on port 3000 - acess <http://localhost:3000>
  # necessary to have an emulator or physical device to run the project, I used Android Studio for development
```
```bash
 #Para rodar os testes
 $ yarn test
```

---
## 📝 License
