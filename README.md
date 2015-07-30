# Bootstrap Sass with Gulp

This is a simple Bootstrap framework with Sass.
Sass watch, livereload, dist build are all automated with Gulp


## Requirements
Basic set-up requirements

* [Node.js](https://nodejs.org/)
* [NPM](https://www.npmjs.com/)
* [Twitter Bootstrap](http://getbootstrap.com/)
* [FontAwesome](http://fortawesome.github.io/Font-Awesome/)

## Usage

1. download the package
2. download [bootstrap-sass](https://github.com/twbs/bootstrap-sass)
3. download [FontAwesome](http://fortawesome.github.io/Font-Awesome/)
4. run `npm install`
5. put entire bootstrap-sass and FontAwesome in `/src/vendors/` 
6. run `gulp` in console for development
7. run `gulp build` for final distribution

## To Be Done
* bootstrap sass and FontAwesome are located in `/vendors` folder, so gulp watch on `/scss` will not trigger the update of both scss files

* remove unnecessary `node_modules` from `package.json`




