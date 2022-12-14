# Battle City Remake

## Brief Intro

The remake version of the classic Battle City, based on the original material, uses React to encapsulate various materials into corresponding components. The material is rendered with SVG to show the pixel style of the game. You can adjust the browser zoom before playing the game. It is best to use 200% zoom under the 1080P screen. This game is developed using web front-end technology, mainly using React for page display, using Immutable.js as a data structure tool library, using redux to manage game state, and using redux-saga/little-saga to handle complex game logic.

## Game Play

[Play at this Page](https://ldr426.github.io/BattleCity-React/0.3.0/index.html#/)

## Local Development

1. Clone the project to local
2. Run `yarn install` to install dependencies (or use `npm install`)
3. Run `yarn start` to start webpack-dev-server and open `localhost:8080` in your browser
4. Run `yarn build` to package the production version, the package output is in the `dist/` folder

`devConfig.js` contains some configuration items for development. Note that you need to restart webpack-dev-server after modifying the configuration in this file
