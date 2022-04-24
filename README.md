# ts-node-express-mongodb-auth

## Resources / Tutorials

- [How to set up TypeScript with Node.js and Express](https://blog.logrocket.com/how-to-set-up-node-typescript-express/)

- [TypeScript & Node.js best practices for large-scale applications](https://khalilstemmler.com/)

- Clean Code Tooling Series

  1. [x] [How to Setup a TypeScript + Node.js Project](https://khalilstemmler.com/blogs/typescript/node-starter-project/)

  2. [x] [How to use ESLint with TypeScript](https://khalilstemmler.com/blogs/typescript/eslint-for-typescript/)

  3. [x] [How to use Prettier with ESLint and TypeScript in VSCode](https://khalilstemmler.com/blogs/tooling/prettier/)

  4. [ ] [Enforcing Coding Conventions with Husky Pre-commit Hooks](https://khalilstemmler.com/blogs/tooling/enforcing-husky-precommit-hooks/)

- [OS specific operations in npm scripts](https://www.npmjs.com/package/run-script-os)

- [Jest](https://jestjs.io/fr/docs/getting-started)

- [How to configure Jest with TypeScript](https://swizec.com/blog/how-to-configure-jest-with-typescript/)

- [Husky](https://github.com/typicode/husky)

## Technology stack

- TypeScript
- Node.js
- Express.js
- MongoDB

## Features

- Minimal
- TypeScript v4
- Testing with Jest
- Linting with Eslint and Prettier
- Pre-commit hooks with Husky
- VS Code debugger scripts
- Local development with Nodemon

## Scripts

### `npm run start:dev`

Starts the application in development using `nodemon` and `ts-node` to do hot reloading.

### `npm run start`

Starts the app in production by first building the project with `npm run build`, and then executing
the compiled JavaScript at `build/index.js`.

### `npm run build`

Builds the app at `build`, cleaning the folder first.

### `npm run test`

Runs the `jest` tests once.

### `npm run test:dev`

Run the `jest` tests in watch mode, waiting for file changes.

### `npm run lint`

Lint your code.

### `npm run prettier-format`

Format your code.

### `npm run prettier-watch`

Format your code in watch mode, waiting for file changes.
