# grunt-hello-world

> Says Hello on the console to a specified subject. For tutorial purposes.

## Getting Started
This plugin requires Grunt `~0.4.5`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-hello-world --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-hello-world');
```

## The "hello_world" task

### Overview
In your project's Gruntfile, add a section named `hello_world` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  hello_world: {
     world: {
        name: "world"
     },
     other: {
        name: "name"
     }
  },
});
```

### Options

#### name
Type: `String`
Default value: `',  '`

A string value that is used greeted to.


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
_(Nothing yet)_
