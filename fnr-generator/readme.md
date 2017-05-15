# fnr-generator
[![travis][travis-image]][travis-url]
[![npm][npm-image]][npm-url]

[travis-image]: https://img.shields.io/travis/laat/fnr.js.svg?style=flat
[travis-url]: https://travis-ci.org/laat/fnr.js
[npm-image]: https://img.shields.io/npm/v/fnr-generator.svg?style=flat
[npm-url]: https://npmjs.org/package/fnr-generator

## Install

```
$ npm install --save fnr-generator
```

## Usage

```javascript test
import generator from 'fnr-generator'

var gen = generator(new Date('2015-03-24'))

gen.next()
//=> { done: false, value: '24031550005' }

gen.next()
//=> { done: false, value: '24031550196' }
```

## Contributing

### Build

```js
npm run build
```

### Test

```js
npm test
```

## License

MIT © [Sigurd Fosseng](https://github.com/laat)
<!-- test-main: "./src/fnr-generator" -->
