# array-remove-by-value

A simple function for removing values from arrays. They say you're not supposed to monkey patch, but I don't care.

## Installation

```sh
npm install array-remove-by-value --save
```

## Usage

```js
Array.prototype.remove = require("array-remove-by-value")

var fruits = ['orange', 'apple', 'banana'];
fruits.remove('apple');
console.log(fruits)
// ['orange', 'banana']
```
