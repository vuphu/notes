# JavaScript Note

## Setup Project

### Using `npm`

`npm init -y`

`npm install --save express`

`npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/node`

- .babelrc

```json
{
  "presets": ["@babel/preset-env"]
}
```

- src/index.js

```js
import express from "express";

console.log("Hello, World!");
```

- package.json

```json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "nodemon src/index.js --exec babel-node"
}
```

`npm install`

`npm start`

### You can using `yarn` instead of `npm`
`yarn init -y`

`yarn add express`

`yarn add --save-dev @babel/core @babel/cli @babel/preset-env @babel/node`

`yarn install`

`yarn start`

I usually using `yarn` instead of `npm`, you can search comparision of `npm` and `yarn`

## Development Enviroment
I recommend you using Visual Studio Code. 

Happy coding 😄
