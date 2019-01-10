# React Training

## Table of Contents <!-- omit in toc -->
1. [Introduction to React](#introduction-to-react)
2. [Prerequisites](#prerequisites)
   1. [ECMAScript 2015+](#ecmascript-2015)
   2. [Node.js and npm](#nodejs-and-npm)
3. [Getting Started](#getting-started)
4. [Overview of package.json](#overview-of-packagejson)
   1. [Dependencies](#dependencies)
   2. [Scripts](#scripts)
      1. [start](#start)
      2. [build](#build)
      3. [test](#test)
      4. [eject](#eject)

## Introduction to React
React is a javascript library for building component-based user interfaces. [More Details](training/Introduction.md)

## Prerequisites
Before getting started with React, there are a few technologies one might need to be familiar with.

### ECMAScript 2015+
You need a good understanding of ES6 and beyond since most of React based development is done in ES6+.

### Node.js and npm
You need to be familiar with the node.js and npm ecosystem in order to run and build react apps.

## Getting Started
To get started, get the `create-react-app` package from the npm registry:
```
$ npm install -g create-react-app
```

Once installed, use the package to initialize your react app.
```
$ create-react-app my-react-app
```
**Note:** `my-react-app` is the name of your app. This is also the name of the folder that gets created in the directory where you ran the `create-react-app` command.

To run the app, go to the app directory and run the `start` script
```
cd my-react-app
npm start
```
If you have `yarn` installed, use that instead.
```
yarn start
```

## Overview of package.json
Let's take a look at the `package.json` file.

### Dependencies
The base `create-react-app` uses only three dependencies, namely `react`, `react-dom` and `react-scripts`.

### Scripts
The app comes with four scripts, namely `start`, `build`, `test` and `eject`.

#### start
The `start` script runs a development server in port `3000`. The development server is based on `webpack` and supports hot reloading.

#### build
The `build` script generates a production build in the `build` directory of the root folder of the app.

#### test
The `test` script uses `jest` to test all files in the `src` folder. The test files have a suffix of `name.spec.js` or `name.test.js`

#### eject
The `eject` script extracts all the configuration files of the app into the root directory. This includes `scripts`, build `webpack` configs and `dependencies` and `devDependencies` in the `package.json` file. Note that this operation is **permanent**.
