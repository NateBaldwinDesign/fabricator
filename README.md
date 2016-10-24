<!-- [![GitHub release](https://img.shields.io/github/release/fbrctr/fabricator.svg)]()
[![Build Status](https://travis-ci.org/fbrctr/fabricator.svg)](https://travis-ci.org/fbrctr/fabricator) [![devDependency Status](https://david-dm.org/fbrctr/fabricator/dev-status.svg)](https://david-dm.org/fbrctr/fabricator#info=devDependencies) [![Join the chat at https://gitter.im/fbrctr/fabricator](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fbrctr/fabricator?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<p align="center">
  <img src="http://fbrctr.github.io/assets/toolkit/images/logo.svg" width="500">
</p>
 -->
# Fabricator + Dragoman

> _fabricate_ - to make by assembling parts or sections.

> _dragoman_ - a professional interpreter.

Fabricator is a tool for building website UI toolkits - _think ["Tiny Bootstraps, for Every Client"](http://daverupert.com/2013/04/responsive-deliverables/#tiny-bootstraps-for-every-client)_

Dragoman is a plugin for creating applications with a token-based design systems. Using gulp with yaml "tokens", Dragoman generates multi-platform assets for core design attributes. This allows you build unified & consistent applications with a core set of *cross-platform variables*

## Quick Start

```shell
$ git clone (this repo)
$ npm start
```

#### Hack the Data
You need to point to Dragoman's tokens in order to make your Fabricator site pull the tokens into the documentation. In order to do that, find:

```
node_modules/fabricator-assemble/index.js
```

Then replace the `data` line with this:

```js
data: ['Dragoman/_tokens/**/*.{json,yml}']
```

## Documentation

#### [Read the docs →](http://fbrctr.github.io/docs)

## Demo

#### [Default Fabricator Instance →](http://fbrctr.github.io/demo)

## Credits

Created by [Luke Askew](http://twitter.com/lukeaskew).

Logo by [Abby Putinski](https://abbyputinski.com/)

## License

[The MIT License (MIT)](http://opensource.org/licenses/mit-license.php)
