* npm init -y
*
    * git init
* npm install react react-dom
* npm install @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev .babelrc

      {
        "presets": [
        ["@babel/preset-env",{ "targets":{ "node":"current" } }],
        "@babel/preset-react"
        ]
      }
* npm install webpack webpack-cli html-webpack-plugin html-loader --save-dev

      ver el archivo webpack.config.js
* npm install --save-dev webpack-dev-server
* npm install --save-dev mini-css-extract-plugin css-loader node-sass sass-loader
* npm install --save-dev eslint babel-eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y
* npm install --save-dev file-loader
* sudo npm install json-server -g