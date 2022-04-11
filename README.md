# @bagus-dev/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@bagus-dev/tiny.svg)](https://www.npmjs.com/package/@bagus-dev/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@bagus-dev/tiny.svg)](https://www.npmjs.com/package/@bagus-dev/tiny)

Hello Everyone! <br/>
This is my first npm package, I'm so excited! <br/>
Removes all spaces from a string.

## Install

```
$ npm install @bagus-dev/tiny
```

## Usage

```js
const tiny = require("@bagus-dev/tiny");
tiny("So much space!");
//=> "Somuchspace!"
tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```