# React Starter

A basic template that consists of the essential elements that are required to start building a React application.

The template consists of:

  * a typcial project layout structure
  * babel setup and configuration
  * webpack setup and configuration
  * eslint setup and configuration
  * SCSS setup and configuration
  * the main React components to get started

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The following software is required to be installed on your system:

  * Node 8.x
  * Npm 3.x

Type the following commands in the terminal to verify your node and npm versions

  ```
  node -v
  npm -v
  ```

### Install

Follow the following steps to get development environment running.

* Clone _'react-starter'_ repository from GitHub

  ```
  git clone https://github.com/drminnaar/react-starter.git
  ```

   _OR USING SSH_

  ```
  git clone git@github.com:drminnaar/react-starter.git
  ```

* Install node modules

   ```
   cd react-starter
   npm install
   npm dedupe
   ```

### Build

* Build application

  This command will also run ESLint as part of build process.
   
  ```
  npm run build
  ```

* Build application and start watching for changes
   
  This command will also run ESLint as part of build process.

  ```
  npm run build:watch
  ```  

### Run ESlint

* Lint project using ESLint

  ```
  npm run lint
  ```

* Lint project using ESLint, and autofix

  ```
  npm run lint:fix
  ```

### Run

* Run start

  This will run the _'serve'_ npm task

  ```
  npm start
  ```

* Run webpack dev server

  ```
  npm run serve:dev
  ```

* Alternatively run live-server (simple development http server with live reload capability)

  ```
  npm run serve
  ```

## Developed With

* [Node.js](https://nodejs.org/en/) - Javascript runtime
* [React](https://reactjs.org/) - A javascript library for building user interfaces
* [Babel](https://babeljs.io/) - A transpiler for javascript
* [Webpack](https://webpack.js.org/) - A module bundler
* [SCSS](http://sass-lang.com/) - A css metalanguage

## Versioning

I use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/codesaucerer/react-starter/tags).

## Authors

* **Douglas Minnaar** - *Initial work* - [drminnaar](https://github.com/drminnaar)