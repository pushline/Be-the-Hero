# Be The Hero

A Semana OmniStack é um workshop online produzido pela Rocketseat. Esta é a versão 11, onde o [Diego Fernandes](https://github.com/diego3g) nos ensina a desenvolver uma aplicação desde o backend até o frontend web e mobile com uma única linguagem, o Javascript. O nome da aplicação desenvolvida é Be The Hero, uma aplicação para cadastro de ONGs e casos cadastrados por elas para que outras pessoas possam ajudar a resolvê-los.

Para clonar o repositório, execute o seguinte comando no terminal:

```git clone https://github.com/pushline/Be-the-Hero.git```

# Instalação

## Pré-Requisitos 

```git, node, express, knex, sqlite, react, react-native, expo```

Clone o repositório, utilizando git clone ou faça o download do repositório.

Para iniciar o **Backend** do React utilize os comandos:
```
cd backend
yarn install
yarn start
```

Para iniciar o **Frontend** do React utilize os comandos:

```
cd frontend
yarn install
yarn start
```

Assim que o processo terminar, automaticamente será aberta no seu navegador a página ``localhost:3000`` contendo o Projeto.

Pro mobile, é o seguinte:

Para testar o **Mobile** do React Native, primeiro coloque o endereço do seu servidor (ou computador) no arquivo src/services/api.js, e depois execute os comandos:

```
# NÃO é preciso executar a linha de baixo caso ja tenha o Expo (CLI) instalado!
yarn global add install expo-cli
cd mobile
yarn install
expo start
```
Assim que o processo terminar, automaticamente será aberta no seu navegador a página ``localhost:19002``. Conecte seu emulador, ou teste o aplicativo por ``LAN``: baixe o aplicativo *Expo* da Play Store ou App Store e em seguida escaneie o código QR. (Se não for por lan, tente por tunnel, espere aparecer no Metro Blunder(informações do Expo sobre o app) a mensagem *Tunnel Ready* então clique em tunnel e escaneie o código QR.

# Projeto


![](https://github.com/pushline/Be-the-Hero/blob/master/frontend/77811449-13935d80-7079-11ea-9123-4c8ff90a696b.png)


# Back-End

Api desenvolvida em NodeJS com acesso a banco de dados relacional = SQLite. Esta api faz uso do Knex.

As rotas para acessar a API estão no arquivo [routes.js](https://github.com/pushline/Be-the-Hero/blob/master/backend/src/routes.js). Você pode testar as rotas antes de usar o frontend com o software Insomnia. Você só precisa baixar e instalar o Insomnia na sua máquina, e acessar as rotas da aplicação.

# Front-End (Web e Mobile)

Frontend web, desenvolvido em ReactJS. Nesta parte da aplicação, é possível entender diversos conceitos do React e do desenvolvimento web em geral. 

Além disso, é muito importante entender como a página web normalmente se comunica com a API por meio de requisições http, as quais retornam ao frontend como um objeto json. Neste caso, foi utilizada a lib axios para realizar a comunicação com a api.


Com isso, a página da aplicação Be The Hero será aberta. Nela, uma ong poderá se cadastrar e cadastrar seus incidentes. A ong também poderá entrar em contato com outras ONGs para poder ajudar nos incidentes delas.


💻Versão Web
 
![](https://github.com/pushline/Be-the-Hero/blob/master/frontend/77805427-9c51cf80-7060-11ea-88a1-ff3014ffe8ce.gif)
  
:iphone:Versão Mobile

![](https://github.com/pushline/Be-the-Hero/blob/master/frontend/77805360-72001200-7060-11ea-9bc3-dd313a195bf8.gif)



# Mobile

Desenvolvido com o framework React Native e com o Expo.
