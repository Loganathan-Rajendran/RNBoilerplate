React Native Boilerplate
=======================

[![React Native](https://img.shields.io/badge/React%20Native-v0.43-blue.svg)](https://facebook.github.io/react-native/)

React Native Boilerplate is a starting point for React Native application.

## Features

* [Redux](http://redux.js.org/)
* [Eslint](http://eslint.org/) ([Airbnb config](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb))

## Prerequisites

* [Node](https://nodejs.org) v6.10 (it is recommended to install it via [NVM](https://github.com/creationix/nvm))
* [Yarn](https://yarnpkg.com/)
* A development machine set up for React Native by following [these instructions](https://facebook.github.io/react-native/docs/getting-started.html)

## Installation

See
[Getting Started](https://facebook.github.io/react-native/docs/getting-started.html)
to install requirement tools.

```bash
$ npm install -g react-native-cli
$ npm install
```

## Getting Started

1. Clone this repo, `git@github.com:Loganathan-Rajendran/RNBoilerplate.git'
2. Go to project's root directory, `cd <your project name>`
3. Run `yarn` to install dependencies

### iOS

Run command to open iOS simulator and run app:
```bash
$ yarn ios
```
### Android (5.0+)

Open Android emulator (recommended [Genymotion](https://www.genymotion.com)) and
run command: (Or connect real device via USB)``
```bash
$ yarn android
```

## How To

### Run Tests

* Linter: `yarn lint`
* Unit tests: `yarn test`
* Unit tests (watch mode): `yarn test:watch`
* Code coverage: `yarn test:coverage`

### To Make Android DebugBuild and ReleaseBuild

* Go to project's directory, `cd android`
* Run `./gradlew clean` to clean android build folder
* Run `./gradlew assembleDebug` to make dedug build

## Contributing

**Never** commit directly on master, instead use branches and pull requests.

### You must use the following Style Guides :

* [Airbnb React/JSX Style Guide](https://github.com/airbnb/javascript/tree/master/react)
* [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

This project contains a linting config, you should setup `eslint` into your IDE with `.eslintrc.js`.# RNBoilerplate
