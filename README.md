# react-factory
[![NPM version][npm-image]][npm-url]
[![Downloads][downloads-image]][downloads-url]

`react.createFactory` wrapper because we hate long names. You need to provide
your own version of react though, we're not bundling any in here for you.

## Installation
```bash
npm install react-factory
```

## Usage
```js
var factory = require('react-factory');
var myComponent = factory(require('./path/to/myComponent'));
```

## Why?
`0.12` introduced breaking changes for us non-jsx users, and we don't like long
names so that's why.

## See also
- [The source of eternal grief](http://facebook.github.io/react/docs/glossary.html)

## License
[MIT](https://tldrlegal.com/license/mit-license)

[npm-image]: https://img.shields.io/npm/v/react-factory.svg?style=flat-square
[npm-url]: https://npmjs.org/package/react-factory
[downloads-image]: http://img.shields.io/npm/dm/react-factory.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/react-factory
