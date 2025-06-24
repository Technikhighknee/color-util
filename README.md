# color-utils for Bitburner

A lightweight, dependency-free color utility for formatting colored terminal output in Bitburner (or any ANSI-compatible JS console).

## Usage

```js
import { coloredString } from './libs/color-utils.js';

const output = coloredString('Hello Bitburner!', {
  text: 'a2a40f',
  background: '0fa2a4',
  bold: true,
  underline: true,
});
ns.tprint(output);
