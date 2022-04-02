<h1 align="center">
  <br>
  <img src="https://reactnative.dev/img/header_logo.svg" alt="React Native Boilerplate" width="200">
  <br>
    React Boilerplate with Vite
  <br>
</h1>

<h4 align="center">A React Boilerplate built to Scale</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#application-structure">Application Structure</a> •
  <a href="#license">License</a>
</p>

## Key Features

- :fire: Built with [Vite](https://vitejs.dev/). Blazing fast :rocket:
- :hugs: [Typescript](https://www.typescriptlang.org/) support default.

- :cop: Eslint and Prettier configured

  - Eslint and prettier configured together for auto save format and error checks

- :dog: [husky](https://typicode.github.io/husky/) for git hooks.
  - No commit is allowed with errors in code.
  - [lint-staged](https://github.com/okonet/lint-staged) will only check errors in staged files.
- :angel: [Commitizen](https://github.com/commitizen/cz-cli) for pretty commit message.
- :tea: Kept very minimal. Only the App and Main file.

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. Recommended to use [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable) for the project.

Setup the environtment based on your OS following instruactions from [here](https://reactnative.dev/docs/environment-setup)

From your command line:

```bash
# Clone this repository
$ git clone repo-link

# Go into the repository
$ cd react-vite

# Install dependencies
$ yarn install or npm i

# Run the app
$ yarn dev



```

## Application structure

> The directory layout of this boilerplate

    .
    ├── .vscode                 # Vscode config, for autoformat on save.
    ├── node_modules            # NPM dependency folder
    ├── src                     # Source directory for the React Application
    ├── index.html              # The main html file
    ├── tsconfig.json           # Configure typescript
    ├── tsconfig.node.json      # Configure typescript for node and vite
    ├── package.json            # The NPM config file for all the packages installed and scripts and more
    ├── .eslintrc               # Configure Eslint
    ├── .gitignore              # ignore certain files for git (example: .env)
    ├── .prettierrc             # Configure prettier (example: .env)
    ├── vite.config.ts          # Configure vite

## Credits

This software uses the following open source packages:

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [eslint](https://eslint.org/)
- [prettier](https://prettier.io/)
- [husky](https://typicode.github.io/husky/)
- [commitizen](https://github.com/commitizen/cz-cli)
- And more..

## License

MIT
