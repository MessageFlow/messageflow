<div align="center" style="text-align: center;">
  <h1 style="border-bottom: none;">messageflow</h1>

  <p>Better greeting message</p>
</div>

<hr />

[![NPM][nodei-badge]][nodei-url]

[![Build Status][travis-badge]][travis-url]
[![Version][version-badge]][version-url]
[![Downloads][downloads-badge]][downloads-url]
[![MIT License][mit-license-badge]][mit-license-url]
[![Dependency Status][daviddm-badge]][daviddm-url]
[![NSP Status][nsp-badge]][nsp-url]

[![Code of Conduct][coc-badge]][coc-url]

[![codebeat-badge]][codebeat-url]
[![codacy-badge]][codacy-url]
[![inch-badge]][inch-url]

> Messageflow

## Table of contents

- [Pre-requisite](#pre-requisite)
- [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
    - [Node.js](#nodejs)
    - [Native ES modules or TypeScript](#native-es-modules-or-typescript)
- [API Reference](#api-reference)
  - [greeting(name)](#greetingname)
  - [greetingSync(name)](#greetingsyncname)
- [License](#license)

## Pre-requisites

- [Node.js][node-js-url] >= 8.9.0
- [NPM][npm-url] >= 5.5.1 ([NPM][npm-url] comes with [Node.js][node-js-url] so there is no need to install separately.)

## Setup

### Install

```sh
# Install via NPM
$ npm install --save messageflow
```

### Usage

#### Node.js

```js
const greeting = require('messageflow');
```

#### Native ES modules or TypeScript

```ts
import greeting from 'messageflow';
```

## API Reference

### greeting(name)

  - name <[string][string-mdn-url]> Name of the person to greet at.
  - returns: <[Promise][promise-mdn-url]<[string][string-mdn-url]>> Promise which resolves with a greeting message.

### greetingSync(name)

This methods works the same as `greeting(name)` except that this is the synchronous version.

## License

[MIT License](https://Messageflow.mit-license.org/) © Rong Sen Ng



[typescript-url]: https://github.com/Microsoft/TypeScript
[node-js-url]: https://nodejs.org
[npm-url]: https://www.npmjs.com
[node-releases-url]: https://nodejs.org/en/download/releases
[string-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String
[promise-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise



[nodei-badge]: https://nodei.co/npm/messageflow.png?downloads=true&downloadRank=true&stars=true

[travis-badge]: https://img.shields.io/travis/Messageflow/messageflow.svg?style=flat-square

[version-badge]: https://img.shields.io/npm/v/messageflow.svg?style=flat-square
[downloads-badge]: https://img.shields.io/npm/dm/messageflow.svg?style=flat-square
[mit-license-badge]: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
[nsp-badge]: https://nodesecurity.io/orgs/Messageflow/projects/a1c57ec8-9c17-4912-932b-f1ff6284e2ae/badge
[daviddm-badge]: https://img.shields.io/david/expressjs/express.svg?style=flat-square

[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square

[codebeat-badge]: https://codebeat.co/badges/e486e791-12b7-4198-b834-0fa5bd04e1c3
[codacy-badge]: https://api.codacy.com/project/badge/Grade/a70d1556b4e74711a162c4fd4dbb68a1
[inch-badge]: http://inch-ci.org/github/Messageflow/messageflow.svg?branch=master



[nodei-url]: https://nodei.co/npm/messageflow

[travis-url]: https://travis-ci.org/Messageflow/messageflow
[version-url]: https://npmjs.org/package/messageflow
[downloads-url]: http://www.npmtrends.com/messageflow
[mit-license-url]: https://github.com/Messageflow/messageflow/blob/master/LICENSE
[nsp-url]: https://nodesecurity.io/orgs/Messageflow/projects/a1c57ec8-9c17-4912-932b-f1ff6284e2ae
[daviddm-url]: https://david-dm.org/Messageflow/messageflow

[coc-url]: https://github.com/Messageflow/messageflow/blob/master/CODE_OF_CONDUCT.md

[codebeat-url]: https://codebeat.co/projects/github-com-Messageflow-messageflow-master
[codacy-url]: https://www.codacy.com/app/Messageflow/messageflow?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Messageflow/messageflow&amp;utm_campaign=Badge_Grade
[inch-url]: http://inch-ci.org/github/Messageflow/messageflow
