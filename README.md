![Seneca](http://senecajs.org/files/assets/seneca-logo.png)
> A [Seneca.js][] plugin

# @seneca/web-adapter-connect

[![npm version](https://img.shields.io/npm/v/seneca-web-adapter-connect.svg)](https://npmjs.com/package/seneca-web-adapter-connect)
[![build](https://github.com/senecajs/seneca-web-adapter-connect/actions/workflows/build.yml/badge.svg)](https://github.com/senecajs/seneca-web-adapter-connect/actions/workflows/build.yml)
[![Known Vulnerabilities](https://snyk.io/test/github/senecajs/seneca-web-adapter-connect/badge.svg)](https://snyk.io/test/github/senecajs/seneca-web-adapter-connect)

| ![Voxgig](https://www.voxgig.com/res/img/vgt01r.png) | This open source module is sponsored and supported by [Voxgig](https://www.voxgig.com). |
|---|---|

## Install

```sh
npm install seneca-web-adapter-connect
```

## Quick Example

```js
var SenecaWeb = require('seneca-web')
var connect = require('connect')
var app = connect()
require('seneca')()
  .use(SenecaWeb, { context: app, adapter: require('seneca-web-adapter-connect') })
```

## More Examples

See [test/](test/) for usage examples.

## Motivation

Connect adapter for [seneca-web](https://github.com/senecajs/seneca-web). Maps HTTP routes to Seneca actions.

## Support

If you're using this module and need help, you can:

- Post a [github issue](https://github.com/senecajs/seneca-web-adapter-connect/issues)
- Tweet to [@senecajs](http://twitter.com/senecajs)
- Ask on the [Gitter](https://gitter.im/senecajs/seneca)


## API

Configured via [seneca-web](https://github.com/senecajs/seneca-web) options.

## Contributing

The [Senecajs org][] encourages open participation. If you feel you can help in any way, be it with documentation, examples, extra testing, or new features please get in touch.

### Running tests

```sh
npm run test
```

## Background

Part of the [seneca-web](https://github.com/senecajs/seneca-web) adapter family.

