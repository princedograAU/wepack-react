# React + Webpack + Babel + SCSS/SASS

This file contains step by step guide to setup react project from scratch with the help of webpack and babel

### Steps to install dependencies

* create a directory <app-name> eg. webpack-react
* inside the directory run command to initialize it as a node project
#### \t npm init
* install dev dependencies
    * webpack
        npm install --save-dev webpack webpack-cli webpack-dev-server 
    * react
        npm install --save-dev react react-dom
    * babel
        npm install --save-dev @babel/core babel-loader @babel/preset-env @babel/preset-env @babel/plugin-syntax-jsx
    * css/sass loader
        npm install --save-dev css-loader style-loader sass sass-loader
    * image loader
        npm install --save-dev file-loader url-loader
    * plugins
        npm install --save-dev html-webpack-plugin

### react                       - package that contains only functionalities necessary to define react components
### react-dom                   - run in parallel to react to render dom
### webpack                     - is a static module bundler for modern JavaScript applications
### webpack-cli                 - to configure and interact with build
### webpack-dev-server          - used to quickly deploy an application
### @babel/core                 - the core babel library. 
### @babel/preset-env           - allows dev to write latest js without worrying about syntax transformation
### @babel/preset-react         - 
### @babel/plugin-syntax-jsx    - 
### babel-loader                - package that transpiles JS files using Babel and Webpack
### css-loader                  - interprets @import and url() like import/require() and will resolve them
### style-loader                - injects css into the DOM
### sass                        - Dart SASS is used as per the recommendation by docs
### sass-loader                 - Chain sass-loader with style-loader and css-loader
### file-loader                 - resolves import/require() on a file into a url and emits the file into the output directory.
### url-loader                  - A loader for webpack which transforms files into base64 URIs.
### html-webpack-plugin         - simplifies creation of HTML files to serve your webpack bundles