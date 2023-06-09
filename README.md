# simple-vdf3
----

> A Simple library for Text-based VDF (Valve Data Format) (de)serialization.

Based on Tom Shaver's [simple-vdf2](https://www.npmjs.com/package/simple-vdf2), which in turn is based on Rossen Georgiev's [simple-vdf](https://www.npmjs.com/package/simple-vdf).

### Installing
**Requires a minimum version of Node v13.2.0**

NPM:
```sh
npm install simple-vdf3
```
Yarn:
```sh
yarn add simple-vdf3
```

## Example

```js
import { parse, stringify } from 'simple-vdf3';

console.log(stringify(parse("VDF_CONTENT"), true))
```

## Methods

### parse(string)
Parse a string containing VDF and returns an object

### stringify(obj) / dump(obj)
Serializes an object to a string of VDF