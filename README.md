<h1 align="center">
<br>
  MW Boilerplate
  <br>
</h1>

<h4 align="center">Express RESTful API Boilerplate Using TypeScript</h4>

## Quick Start

### Install with the npm Global Package

```bash
$ npm install -g nmw
```

### Run npx to Install The Package

npx is a tool in the JavaScript package management module, npm.

This is a tool that allows you to run the npm package on a single run without installing the package.

If you do not enter a project name, it defaults to _mw_boilerplate_.

```bash
$ npx mw "project name"
```

### Select a Templates

Start your mw_boilerplate app in development mode at `http://localhost:3000/`

#### Template Type

| Name                                                                                     | Description                                                                                                                                                |
| :--------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default                                                                                  | Express Default                                                                                                                                            |
| [Sequelize](https://github.com/sequelize/sequelize)                                      | Easy to use multi SQL dialect ORM for Node.js                                                                                                              |
| [Mongoose](https://github.com/Automattic/mongoose)                                       | MongoDB Object Modeling(ODM) designed to work in an asynchronous environment                                                                               |
| [Prisma](https://github.com/prisma/prisma)                                               | Modern Database Access for TypeScript & Node.js                                                                                                            |

## Available Commands for the Server

- Run the Server in production mode : `npm run start` or `Start mw_boilerplate` in VS Code
- Run the Server in development mode : `npm run dev` or `Dev mw_boilerplate` in VS Code
- Run all unit-tests : `npm test` or `Test mw_boilerplate` in VS Code
- Check for linting errors : `npm run lint` or `Lint mw_boilerplate` in VS Code
- Fix for linting : `npm run lint:fix` or `Lint:Fix mw_boilerplate` in VS Code


### ESLint, Prettier :: Code Formatter

[Prettier](https://prettier.io/) is an opinionated code formatter.

[ESLint](https://eslint.org/), Find and fix problems in your JavaScript code

It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

1. Install [VSCode](https://code.visualstudio.com/) Extension [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

2. `CMD` + `Shift` + `P` (Mac Os) or `Ctrl` + `Shift` + `P` (Windows)

3. Format Selection With

4. Configure Default Formatter...

5. Prettier - Code formatter

<img src="https://user-images.githubusercontent.com/42952358/126604937-4ef50b61-b7e4-4635-b3c9-3c94dd6b06fa.png" alt="Formatter Setting" />

> Palantir, the backers behind TSLint announced in 2019 that they would be deprecating TSLint in favor of supporting typescript-eslint in order to benefit the community.
> So, migration from TSLint to ESLint.

### Swagger :: API Document

[Swagger](https://swagger.io/) is Simplify API development for users, teams, and enterprises with the Swagger open source and professional toolset.

Easily used by Swagger to design and document APIs at scale.

Start your app in development mode at `http://localhost:3000/api-docs`

Modify `swagger.yaml` file to your source code.

### REST Client :: HTTP Client Tools

REST Client allows you to send HTTP request and view the response in Visual Studio Code directly.

VSCode Extension [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) Install.

Modify `*.http` file in src/http folder to your source code.


## 💳 License

[MIT](LICENSE)
و
