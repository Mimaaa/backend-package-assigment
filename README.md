# Backage

The ```index.js``` file contains functions who replace characters based on a pre-defined set of rules.

# Install...

...the project by running:

```$ npm install```

# Usage

```javascript
const vowel = require('vowel');

console.log(vowel('butt')); //=> 'b*tt'
console.log(vowel.vowel('butt')); //=> 'b*tt'
console.log(vowel.inner('butt')); //=> 'b**t'
console.log(vowel.grawlix('butt')); //=> '@#$%'
console.log(vowel.grawlix(7)); //=> '@#$%!&?'
```

# Utilities

[XO](https://github.com/xojs/xo) (for linting), [Prettier](https://github.com/prettier/prettier) (for formatting) and [Mocha](https://mochajs.org/) for unit testing are included as devDependencies. 

## Scripts

* XO: ```$ npm run lint```
* Prettier: ```$ npm run pretty```
* Mocha: ```$ npm run test```

All of them combined are executed by ```$ npm run magic```.

# Contributing

If you would like to [contribute](https://github.com/Mimaaa/backend-package-assigment/blob/master/CONTRIBUTING.md), you are welcome to do so.

# License

[MIT](https://github.com/Mimaaa/backend-package-assigment/blob/master/LICENSE.md) 
