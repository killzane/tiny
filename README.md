# @killzane/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@killzane/tiny.svg)](https://www.npmjs.com/package/@killzane/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@killzane/tiny.svg)](https://www.npmjs.com/package/@killzane/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @killzane/tiny
```

## Usage

```js
const tiny = require("@killzane/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```