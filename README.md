# Shades
A library for generating shades of a given color.

## Installation

`npm install @constellates/shades`

## Usage
```javascript
const shades = require('shades');
const grey = shades({ r: 10, g: 10, b: 10 }, 50);

console.log(grey[0]); // 'rgb(0,0,0)'
console.log(grey[1]); // 'rgb(5, 5, 5)'