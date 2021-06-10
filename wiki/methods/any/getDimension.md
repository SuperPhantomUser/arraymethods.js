# GetDimension

The `getDimension` method returns the dimension of an array.
Any arrays with 4 or more dimensions will return 3.

**Works with:** 1d+ arrays
**Returns:** integer

**Parameters:**
- Array

**Examples:**
```js
const array = ["apple", "orange", "lemon", "pear"];
console.log(Arrays.getDimension(array));
// Returns: 1
```
```js
const array = [
  ["apple", "orange"],
  ["lemon", "pear"]
];
console.log(Arrays.getDimension(array));
// Returns: 2
```
```js
const array = [
  [
    ["apple", "orange"],
    ["lemon", "pear"]
  ],
  [
    ["banana", "avocado"],
    ["peach", "grape"]
  ]
];
console.log(Arrays.getDimension(array));
// Returns: 3
```
