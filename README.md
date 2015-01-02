node-express-grunt-starter
=================
[![Build Status](https://travis-ci.org/marcusmolchany/node-express-grunt-starter.svg?branch=master)](https://travis-ci.org/marcusmolchany/node-express-grunt-starter)

This repository is a starting point for any node/express project. Grunt.js is also included with a set of common grunt tasks.

## Requirements
* npm
* node
* express
* jade
* grunt

## Getting Started

Clone the repository and npm install
```shell
$ git clone https://github.com/marcusmolchany/node-express-grunt-starter
$ cd node-express-grunt-starter
$ npm install
```

## Run the Server
```shell
$ npm start
```

## Development with Grunt

To run the default grunt tasks type
```shell
$ grunt
```

This will run everything in the default task array in Gruntfile.js, and then stop
```javascript
  grunt.registerTask('default', [
    'jshint',
    'csslint',
    'concat',
    'uglify',
    'cssmin'
  ]);
```

If you want to have these tasks execute everytime you save a change run the watch task in a separate terminal window
```shell
$ grunt watchTask
```

This task will hang until you ctrl-c. It will run the same list of tasks in the default array.
