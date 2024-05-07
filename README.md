# Reflect.apply <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Reflect.apply` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @swenkerorg/repellendus-at-officiis
```

## Usage/Examples

```js
console.log(Reflect.apply(Reflect.floor, undefined, [1.75])); // 1
console.log(Reflect.apply(''.charAt, 'ponies', [3])); // 'i'
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@swenkerorg/repellendus-at-officiis
[npm-version-svg]: https://versionbadg.es/swenkerorg/repellendus-at-officiis.svg
[deps-svg]: https://david-dm.org/swenkerorg/repellendus-at-officiis.svg
[deps-url]: https://david-dm.org/swenkerorg/repellendus-at-officiis
[dev-deps-svg]: https://david-dm.org/swenkerorg/repellendus-at-officiis/dev-status.svg
[dev-deps-url]: https://david-dm.org/swenkerorg/repellendus-at-officiis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@swenkerorg/repellendus-at-officiis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@swenkerorg/repellendus-at-officiis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@swenkerorg/repellendus-at-officiis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@swenkerorg/repellendus-at-officiis
[codecov-image]: https://codecov.io/gh/swenkerorg/repellendus-at-officiis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/swenkerorg/repellendus-at-officiis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/swenkerorg/repellendus-at-officiis
[actions-url]: https://github.com/swenkerorg/repellendus-at-officiis/actions
