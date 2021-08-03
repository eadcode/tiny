# @eadcodes/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@eadcodes/tiny.svg?style=flat-square)](https://www.npmjs.com/package/@eadcodes/tiny)
[![npm bundle size](https://img.shields.io/bundlephobia/min/@eadcodes/tiny?style=flat-square)](https://www.npmjs.com/package/@eadcodes/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @eadcodes/tiny
```

## Usage

```js
const tiny = require("@eadcodes/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
