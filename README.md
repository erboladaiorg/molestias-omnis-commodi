# @erboladaiorg/molestias-omnis-commodi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@erboladaiorg/molestias-omnis-commodi');
const Eval = require('@erboladaiorg/molestias-omnis-commodi/eval');
const Range = require('@erboladaiorg/molestias-omnis-commodi/range');
const Ref = require('@erboladaiorg/molestias-omnis-commodi/ref');
const Syntax = require('@erboladaiorg/molestias-omnis-commodi/syntax');
const Type = require('@erboladaiorg/molestias-omnis-commodi/type');
const URI = require('@erboladaiorg/molestias-omnis-commodi/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@erboladaiorg/molestias-omnis-commodi
[npm-version-svg]: https://versionbadg.es/ljharb/@erboladaiorg/molestias-omnis-commodi.svg
[deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/molestias-omnis-commodi.svg
[deps-url]: https://david-dm.org/ljharb/@erboladaiorg/molestias-omnis-commodi
[dev-deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/molestias-omnis-commodi/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@erboladaiorg/molestias-omnis-commodi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/molestias-omnis-commodi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/molestias-omnis-commodi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/molestias-omnis-commodi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/molestias-omnis-commodi
[codecov-image]: https://codecov.io/gh/ljharb/@erboladaiorg/molestias-omnis-commodi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@erboladaiorg/molestias-omnis-commodi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@erboladaiorg/molestias-omnis-commodi
[actions-url]: https://github.com/erboladaiorg/molestias-omnis-commodi/actions
