# JavaScript Note

## Setup Project

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

Happy coding 😄
