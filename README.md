# API REST

This project is an example of a simple EXPRESS server basic configuration that is prepared to be the start of a REST API using only ExpressJS, NodeJS Framework and MongoDB as database. 

## BUT...

This project has another part, another branch called `feature/typescript-version` which prepares a complete environment with a scalable typescript configuration.

## Requirements

- [Node.js](https://nodejs.org/en/), **v12.18.3**
- [NPM](https://www.npmjs.com/get-npm), **v6.14.6**
- [MongoDB](https://www.mongodb.com/), **v4.2.9**
- [TypeScript](https://www.typescriptlang.org/), **v4.0.3**

## Core Dependencies

- [Express.js](https://expressjs.com/), **v4.17.1**
- [Mongoose](https://mongoosejs.com/), **v5.10.0**
- [Cors](https://www.npmjs.com/package/cors), **v2.8.5**

## Dev Dependencies

- [Morgan](https://www.npmjs.com/package/morgan), **v4.17.1.** Used to register/log HTTP methods of the API
- [Nodemon](https://www.npmjs.com/package/nodemon), **v5.10.0.** Used to watch changes of server code
- [Dotenv](https://www.npmjs.com/package/dotenv), **v5.10.0.** Used to loads enviroment variables
- [Cross-env](https://mongoosejs.com/), **v5.10.0.** Used to have a single command without worrying about setting or using the environment variable properly for the platform
- [EsLint](https://eslint.org/), **7.10.0**, used to code analyze code quality and stylistic rules.
- [Prettier](https://prettier.io/), **2.1.2**, used to formatting your code.
- [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier), **6.12.0**, Turns off all rules that are unnecessary or might conflict with Prettier.
- [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier), **3.1.4**, Run Prettier as if it was a linter rule.

## First Steps

### Installation

Clone this repo

```
git clone https://github.com/OscarEHF/simple-express-server.git
cd simple-express-server
```

### Run this project:

All dependencies will be installed automatically.

```sh
npm install # install all the dependecies
# or
yarn install

npm start # start application
# or
yarn start
```

Your server is now available at `http://localhost:3000`

### Environment Variables

This app needs the following environment Variables

- `MONGODB_HOST` This is the Mongodb URI string
- `MONGODB_DATABASE` Mongodb database name
- `PORT` This is the HTTP port of the server by default is `3000`

### Run Development Server

```sh
npm run dev # development
# or
yarn dev
```

## Further help

To get more help on the Express Server go check out the [Express.js README](https://github.com/expressjs/express/blob/master/Readme.md) or the [Express.js Doc](http://expressjs.com/)
