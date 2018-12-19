# @kanpou0108/tiny
[![](https://img.shields.io/npm/v/@kanpou0108/tiny.svg)](https://www.npmjs.com/package/@kanpou0108/tiny)
[![](https://img.shields.io/bundlephobia/min/@kanpou0108/tiny.svg)](https://www.npmjs.com/package/@kanpou0108/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @kanpou0108/tiny
```

## Usage

```js
const tiny = require("@kanpou0108/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
