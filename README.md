# @osjwnpm/repellat-saepe-perspiciatis <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has `Symbol.toStringTag` support. Supports spec, or shams.

## Example

```js
var hasSymbolToStringTag = require('@osjwnpm/repellat-saepe-perspiciatis');

hasSymbolToStringTag() === true; // if the environment has native Symbol.toStringTag support. Not polyfillable, not forgeable.

var hasSymbolToStringTagKinda = require('@osjwnpm/repellat-saepe-perspiciatis/shams');
hasSymbolToStringTagKinda() === true; // if the environment has a Symbol.toStringTag sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@osjwnpm/repellat-saepe-perspiciatis
[2]: https://versionbadg.es/inspect-js/@osjwnpm/repellat-saepe-perspiciatis.svg
[5]: https://david-dm.org/inspect-js/@osjwnpm/repellat-saepe-perspiciatis.svg
[6]: https://david-dm.org/inspect-js/@osjwnpm/repellat-saepe-perspiciatis
[7]: https://david-dm.org/inspect-js/@osjwnpm/repellat-saepe-perspiciatis/dev-status.svg
[8]: https://david-dm.org/inspect-js/@osjwnpm/repellat-saepe-perspiciatis#info=devDependencies
[11]: https://nodei.co/npm/@osjwnpm/repellat-saepe-perspiciatis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@osjwnpm/repellat-saepe-perspiciatis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@osjwnpm/repellat-saepe-perspiciatis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@osjwnpm/repellat-saepe-perspiciatis
[codecov-image]: https://codecov.io/gh/inspect-js/@osjwnpm/repellat-saepe-perspiciatis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@osjwnpm/repellat-saepe-perspiciatis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@osjwnpm/repellat-saepe-perspiciatis
[actions-url]: https://github.com/osjwnpm/repellat-saepe-perspiciatis/actions
