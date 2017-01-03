# babel-preset-latest-node4 (DEPRECATED)
[![Dependency Status][depstat-image]][depstat-url]

> Babel preset including es2015, es2016, es2017 for Node.js 4.

**DEPRECATED: Use [babel-preset-env](https://github.com/babel/babel-preset-env)!**

## Install

```bash
$ npm install --save-dev babel-preset-latest-node4
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["latest-node4"]
}
```

### Via CLI

```bash
$ babel script.js --presets latest-node4
```

### Via Node API

```js
require('babel-core').transform('code', {
  presets: ['latest-node4']
});
```

## License

[MIT](LICENSE.md) © [Timofey Dergachev](https://exeto.me/)

[depstat-url]: https://david-dm.org/exeto/babel-preset-latest-node4#info=Dependencies
[depstat-image]: https://img.shields.io/david/exeto/babel-preset-latest-node4.svg?style=flat-square
