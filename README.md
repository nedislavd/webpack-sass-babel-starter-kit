### Requirements
 - Latest NodeJS & NPM | [get here](https://nodejs.org/en/download/)

### Installation
 - Open a command prompt and navigate inside the main repository directory, where `package.json` resides
 
 
 - Run the following command:
 
    ```
    npm install
    ```

### Start Dev Server

```
npm start
```
### Build Prod Version

```
npm run build
```

### Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build` the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) moves the minified css to a separate file. The css file gets included in the head of the `index.html`.
