# lgs-pages

[![NPM Downloads][downloads-image]][downloads-url]
[![NPM Version][version-image]][version-url]
[![License][license-image]][license-url]
[![Dependency Status][dependency-image]][dependency-url]
[![devDependency Status][devdependency-image]][devdependency-url]
[![Code Style][style-image]][style-url]

> static web app workflow

## Installation

```shell
$ yarn add lgs-pages

# or npm
$ npm install lgs-pages
```

## Usage

<!-- TODO: Introduction of API use -->

```javascript
const lgsPages = require('lgs-pages')
const result = lgsPages('lgs')
// result => 'lgs@lgs.me'
```

## API

<!-- TODO: Introduction of API -->

### lgsPages(name[, options])

#### name

- Type: `string`
- Details: name string

#### options

##### host

- Type: `string`
- Details: host string
- Default: `'lgs.me'`

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; lgs <w@lgs.me> (https://lgs.me)



[downloads-image]: https://img.shields.io/npm/dm/lgs-pages.svg
[downloads-url]: https://npmjs.org/package/lgs-pages
[version-image]: https://img.shields.io/npm/v/lgs-pages.svg
[version-url]: https://npmjs.org/package/lgs-pages
[license-image]: https://img.shields.io/github/license/lgs/lgs-pages.svg
[license-url]: https://github.com/lgs/lgs-pages/blob/master/LICENSE
[dependency-image]: https://img.shields.io/david/lgs/lgs-pages.svg
[dependency-url]: https://david-dm.org/lgs/lgs-pages
[devdependency-image]: https://img.shields.io/david/dev/lgs/lgs-pages.svg
[devdependency-url]: https://david-dm.org/lgs/lgs-pages?type=dev
[style-image]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[style-url]: https://standardjs.com
