[![Build Status](https://travis-ci.org/r-park/react-redux-seed.svg?branch=master)](https://travis-ci.org/r-park/react-redux-seed)


# React Redux Seed

- React
- React-Router
- React-Router-Redux
- Redux
- React-Redux
- Redux-Thunk
- Babel
- ES6
- Jasmine
- Karma
- SASS
- Webpack
- Webpack Dev Server


Getting Started
---------------

#### Prerequisites
Node `>=5.10`

#### Installing dependencies
```shell
$ npm install
```


Usage
-----

|Script|Description|
|---|---|
|`npm start`|Start webpack development server @ `localhost:3000`|
|`npm run build`|Lint, test, and build the application to `./target`|
|`npm run dev`|Same as `npm start`|
|`npm run lint`|Lint the application using eslint|
|`npm run server`|Start express server @ `localhost:3000` to serve built artifacts from `./target` (must run `npm run build` first)|
|`npm test`|Run unit tests with Karma and Jasmine|
|`npm run test:watch`|Run unit tests with Karma and Jasmine; watch for changes to re-run tests|
|`npm version`|Bump package.json version, generate CHANGELOG.md, git commit and tag (see [npm version](https://docs.npmjs.com/cli/version))|
