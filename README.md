# NLW 02

## 💻 Projeto
Projeto criado durante a NLW 02 da [Rocketseat](https://rocketseat.com.br/)

<h1 align="center">
    <img style="width:80%" alt="proffy" src="https://i.ibb.co/6s76mHD/2020-08-04-21-44-07-Proffy.png" />
    <br>
</h1>

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bookmark_tabs-dependencies">Dependencies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How To Use</a>
</p>

## :rocket: Technologies

This project was developed at the **Next Level Week #1** by [Rockseat](https://rocketseat.com.br/) using the following technologies:

-  [ReactJS](https://reactjs.org/)
-  [Node.js](nodejs)
-  [TypeScript](https://www.typescriptlang.org/)

## :bookmark_tabs: Dependencies

**Server (Node.js):**

<img alt="express" src="https://img.shields.io/badge/express-^4.17.1-brightgreen" />  
<img alt="cors" src="https://img.shields.io/badge/cors-^2.8.5-brightgreen" /> 
<img alt="knex" src="https://img.shields.io/badge/knex-^0.21.1-brightgreen" /> 
<img alt="sqlite3" src="https://img.shields.io/badge/sqlite3-^4.2.0-brightgreen" />

<br/>

**Web (ReactJS):**
  
<img alt="axios" src="https://img.shields.io/badge/react-^16.13.1-blue" /> 
<img alt="axios" src="https://img.shields.io/badge/react--dom-^16.13.1-blue" /> 
<img alt="axios" src="https://img.shields.io/badge/react--router--dom-^5.2.0-blue" /> 
<img alt="axios" src="https://img.shields.io/badge/react--scripts-3.4.1-blue" /> 
<img alt="axios" src="https://img.shields.io/badge/typescript-^3.7.5-blue" />

<br/>

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v12.14.1][nodejs] or higher and [npm v6.13.4] or higher installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/OLucasAlves/nlw-2.git

# For each folder (server, web and mobile) go into folder and install dependecies

# For server project (Node.js)
$ cd server
$ yarn install
$ yarn knex:migrate
$ yarn start

# For web project (ReactJS)
$ cd web
$ npm install
$ npm start

# For mobile project (React Native)
$ cd mobile
$ yarn install
$ yarn start

