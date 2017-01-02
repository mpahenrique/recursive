# Recursive JS
Load and run modules recursively.
With recursive.js you'll can load modules and access them by a simple object.

### Dependencies
Recursive JS uses just one dependencie:
* [Underscore] - Underscore is a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects.

### Installation
```sh
$ npm install https://github.com/mpahenrique/recursive.git
```

### Usage
```js
var recursive = require('recursive')
,   modules   = recursive.require('./modules');

modules.someSubModule.doSomething('RecursiveJs');
```

[Underscore]: <https://www.npmjs.com/package/underscore>
