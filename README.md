Static html pages with Webpack 4
================================

[![GitHub issues](https://img.shields.io/github/issues/DominikGorecki/webpack-static-html-pages.svg)](https://github.com/ivarprudnikov/webpack-static-html-pages/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/DominikGorecki/webpack-static-html-pages.svg)](https://github.com/DominikGorecki/webpack-static-html-pages/commits/master)

--------------------------------

This is a forkable example of static site (plain html/css/javascript) 
assembled with webpack.

Article explaining how this example was created: https://www.ivarprudnikov.com/static-website-multiple-html-pages-using-webpack-plus-github-example/

## Build

### Prerequisites

- Node & NPM

### Run locally

- `npm i` - install dependencies
- `npm start` - start development server

#### Where are generated files?

In `development` mode `webpack` does not write generated files to disk, in order to change it 
switch `devServer.writeToDisk` to `true` in [webpack.dev.js](./webpack.dev.js)

#### Run production build

- `npm run preview` 

### Production

- `npm run build` to prepare `html`, `css`, `js` files in `dist/` directory

Preview deployed assets on [`gh-pages` branch](https://github.com/ivarprudnikov/webpack-static-html-pages/tree/gh-pages)

## Credits

- @lifenautjoe and his [webpack-starter-basic](https://github.com/lifenautjoe/webpack-starter-basic)
