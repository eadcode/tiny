# @eadcodes/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@eadcode/tiny.svg)](https://www.npmjs.com/package/@eadcodes/tiny)
[![npm bundle size](https://img.shields.io/bundlephobia/min/@eadcodes/tiny)](https://www.npmjs.com/package/@eadcodes/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@eadcode/tiny.svg)](https://www.npmjs.com/package/@eadcodes/tiny)
[![install size](https://packagephobia.com/badge?p=@eadcodes/tiny)](https://packagephobia.com/result?p=@eadcodes/tiny)(https://www.npmjs.com/package/@eadcodes/tiny)

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
