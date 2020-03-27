# Be The Hero

A Semana OmniStack é um workshop online produzido pela Rocketseat. Esta é a versão 11, onde o [Diego Fernandes](https://github.com/diego3g) nos ensina a desenvolver uma aplicação desde o backend até o frontend web e mobile com uma única linguagem, o Javascript. O nome da aplicação desenvolvida é Be The Hero, uma aplicação para cadastro de ONGs e casos cadastrados por elas para que outras pessoas possam ajudar a resolvê-los.

Para clonar o repositório, execute o seguinte comando no terminal:

```git clone https://github.com/pushline/Be-the-Hero.git```




# Back-End

Api desenvolvida em NodeJS com acesso a banco de dados relacional = SQLite. Esta api faz uso do Knex.

As rotas para acessar a API estão no arquivo [routes.js](https://github.com/pushline/Be-the-Hero/blob/master/backend/src/routes.js). Você pode testar as rotas antes de usar o frontend com o software Insomnia. Você só precisa baixar e instalar o Insomnia na sua máquina, e acessar as rotas da aplicação.

# Front-End (Web)

Frontend web, desenvolvido em ReactJS. Nesta parte da aplicação, é possível entender diversos conceitos do React e do desenvolvimento web em geral. 

Além disso, é muito importante entender como a página web normalmente se comunica com a API por meio de requisições http, as quais retornam ao frontend como um objeto json. Neste caso, foi utilizada a lib axios para realizar a comunicação com a api.


Com isso, a página da aplicação Be The Hero será aberta. Nela, uma ong poderá se cadastrar e cadastrar seus incidentes. A ong também poderá entrar em contato com outras ONGs para poder ajudar nos incidentes delas.

# Mobile

Em construção.

Atualmente um frontend mobile, desenvolvido com o framework React Native e com o Expo.
