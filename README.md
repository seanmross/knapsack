# knapsack
Knapsack is a lean and simple Javascript starter app built with Nodejs, Babel, Express, & Webpack.

Knapsack was designed to be a light-weight kit containing only the necessary plugins to transpile, bundle, and serve up ES6 Javascript code. I found this most useful for creating small scale Node apps that required a web server for static files or for testing JS libraries in an easily customizable dev environment.  

### Features
+ [Babel](https://github.com/babel/babel/tree/master/packages/babel-cli) - `babel-preset-env` module for ES2017/ES2016 -> ES2015 javascript transpilation.
+ [Express](https://github.com/expressjs/express) - `express` module for building a minimal and easily configurable web server.
+ [Webpack](https://github.com/webpack/webpack) - use `webpack` to bundle your source code into one file. In conjunction with `webpack-dev-middleware` module, webpack will automatically emit files it processes to a server.

### Get started
+ clone the repo
+ `cd knapsack`
+ `npm i`
+ `npm run server`
+ navigate to `localhost:3000` in your browser
+ get started building your app in the `src` directory
+ update and save JavaScript source files and the knapsack web server will automatically compile and reload
