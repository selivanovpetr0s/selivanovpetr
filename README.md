# selivanovpetr

Selivanovpetr is a Node.js module that provides a collection of selivanovpetr utility functions.

## Installation

You can install this module via npm: `npm install selivanovpetr`

## Usage
```javascript

const cleverUtil = require('clever-util');

// Example usage of functions:
console.log(cleverUtil.generateRandomNumber(1, 100));
console.log(cleverUtil.capitalizeFirstLetter('hello'));
cleverUtil.fetchData('https://jsonplaceholder.typicode.com/posts/1')
  .then(data => console.log(data))
  .catch(err => console.error(err));
```


