# Using webpack 4 and babel to convert Vue to vanilla javascript
Running 
```
    npm install
    npm run dev (npm run prod)
```
will take the ./src/index.js file and it's transitive dependencies and convert it to vanilla JavaScript in the ./dist/main.js folder.

Note:
* Webpack 4 uses ./src/index.js as default entry and ./dist/main.js as default output. Can be overridden if you so wish.
* Make sure you have babel-core, babel-loader, babel-preset-env, vue-loader and vue-template-compiler as dev. dependencies in your package.json
* Configure the webpack.config.js as shown in the repository to enable the babel loader and the vue template compiler