# @eadcodes/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@eadcodes/tiny.svg)](https://www.npmjs.com/package/@eadcodes/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@eadcodes/tiny.svg)](https://www.npmjs.com/package/@eadcodes/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
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
