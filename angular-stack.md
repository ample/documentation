# Angular Stack

## Yeoman Generators

### Yeoman Angular
  * https://github.com/yeoman/generator-angular
  * developed by yeoman
  * supports task runners: grunt, gulp
  * angular: 1.4.8
  * initial structure by type: `controller`, `views`, `service`
  * CON: needs both npm and bower


### gulp-angular
  * https://github.com/swiip/generator-gulp-angular
  * supports gulp
  * angular: 1.4.8
  * initial structure by feature
  * CON: needs both npm and bower


# Other Solutions

## Browserify
Solution to having both NPM and Bower for management. Can utilize CommonJS to pack `node_modules` files for use cleanly on the front-end

## Webpack
Similar to Browserify but is a configuration based system that can run without a task runner
