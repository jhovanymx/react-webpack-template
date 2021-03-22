# webpack-template
Template for a Web App with WebPack, includes loaders for ES6 (Babel) and CSS/SCSS, plugins for generating on-fly HTML and Browser Sync, it uses Bootstrap

## First step: install required Node JS modules
`$ npm install`

## Second step: run using webpack-dev-server
webpack-dev-server provides live reloading, run fast because uses ram memory instead of physical files on disk, by default open port 3000

`$ npm run start`

## Explaning NodeJS modules
+ **@babel/cli & @babel/core**: Babel Core for transpiling to Java Script code that understand any browser
+ **@babel/preset-env**: Set of plugins that transforms ES6/ES2015+ to ES5
+ **webpack & webpack-cli**: Webpack core and command line utility
+ **webpack-dev-server**: Runs a web server that provides live reloading when any file changed, run fast because it uses ram memory instead of physical files on disk, by default open port 3000
+ **browser-sync & browser-sync-webpack-plugin**: Refresh browser's page when any file changed
+ **babel-loader**: Webpack loader for transpiling JS files, it invokes Babel
+ **style-loader & css-loader**: Webpack loaders for processing CSS, includes @import and url declarations
+ **sass-loader**: Webpack loader for transforming SCSS/SASS to CSS. it invokes node-sass
+ **node-sass**: SCSS/SASS to CSS conversor
+ **html-webpack-plugin**: Generates on-fly HTML index or main page, it incrusting tags for loading bundles of JS and CSS code
+ **mini-css-extract-plugin**: Generates static CSS bundle
+ **bootstrap**: CSS framework for desing Web Pages
