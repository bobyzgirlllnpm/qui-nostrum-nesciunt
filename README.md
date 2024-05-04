# @bobyzgirlllnpm/qui-nostrum-nesciunt <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@bobyzgirlllnpm/qui-nostrum-nesciunt');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/qui-nostrum-nesciunt
[npm-version-svg]: https://versionbadg.es/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt.svg
[deps-svg]: https://david-dm.org/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt.svg
[deps-url]: https://david-dm.org/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt
[dev-deps-svg]: https://david-dm.org/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/qui-nostrum-nesciunt.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/qui-nostrum-nesciunt.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/qui-nostrum-nesciunt.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/qui-nostrum-nesciunt
[codecov-image]: https://codecov.io/gh/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@bobyzgirlllnpm/qui-nostrum-nesciunt
[actions-url]: https://github.com/bobyzgirlllnpm/qui-nostrum-nesciunt/actions
