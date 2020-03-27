# Be The Hero

A Semana OmniStack é um workshop online produzido pela Rocketseat. Esta é a versão 11, onde o [Diego Fernandes](https://github.com/diego3g) nos ensina a desenvolver uma aplicação desde o backend até o frontend web e mobile com uma única linguagem, o Javascript. O nome da aplicação desenvolvida é Be The Hero, uma aplicação para cadastro de ONGs e casos cadastrados por elas para que outras pessoas possam ajudar a resolvê-los.

Para clonar o repositório, execute o seguinte comando no terminal:

```git clone https://github.com/pushline/Be-the-Hero.git```




# Back-End

API desenvolvida em [NodeJS](https://nodejs.org/en/) com acesso a banco de dados relacional. Esta API faz uso do [Knex](http://knexjs.org).
(Banco de dados SQLite, o usado).

Para executar a API na sua máquina e servir, execute no terminal:

```cd backend -> npm install --save -> npm run dev```

As rotas para acessar a API estão no arquivo [routes.js](https://github.com/pushline/Be-the-Hero/blob/master/backend/src/routes.js). Você pode testar as rotas antes de usar o frontend com o software [Insomnia](https://insomnia.rest/download/). Você só precisa baixar e instalar o Insomnia na sua máquina, e acessar as rotas da aplicação.

# Front-End (Web)

Frontend web, desenvolvido em [ReactJS](https://pt-br.reactjs.org). Nesta parte da aplicação, é possível entender diversos conceitos do React e do desenvolvimento web em geral. 

Além disso, é muito importante entender como a página WEB normalmente se comunica com a API por meio de requisições HTTP, as quais retornam ao frontend como um objeto JSON. Neste caso, foi utilizada a biblioteca axios para realizar a comunicação com a API.

Para executar o frontend web no navegador, basta executar os seguintes comandos no terminal:

```cd frontend -> npm install --save -> npm run start```

Com isso, a página da aplicação Be The Hero será aberta. Nela, uma ONG poderá se cadastrar e cadastrar seus incidentes. A ONG também poderá entrar em contato com outras ONGs para poder ajudar nos incidentes delas.

# Mobile

Em construção.

Atualmente um frontend mobile, desenvolvido com o framework [React Native](https://reactnative.dev) e com o [EXPO](https://expo.io).
