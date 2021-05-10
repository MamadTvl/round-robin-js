# round-robin-js

[![build:?](https://travis-ci.org/eyas-ranjous/round-robin-js.svg?branch=master)](https://travis-ci.org/eyas-ranjous/round-robin-js) [![npm](https://img.shields.io/npm/v/round-robin-js.svg)](https://www.npmjs.com/package/round-robin-js) [![npm](https://img.shields.io/npm/dm/round-robin-js.svg)](https://www.npmjs.com/package/round-robin-js) [![npm](https://img.shields.io/badge/node-%3E=%206.0-blue.svg)](https://www.npmjs.com/package/round-robin-js)

An implementation of the round robin as a data structure.

# Table of Contents
* [Install](#install)
* [API](#api)
  * [import](#import)
  * [new](#new)
  * [add(item)](#start)
  * [delete(key)](#isstarted)
  * [next()](#isstarted)
  * [count()](#isstarted)
 * [Build](#build)
 * [License](#license)

## Install

```sh
npm install --save round-robin-js
```

### require

#### JS

```js
import { SequentialRoundRobin, RandomRoundRobin } from 'round-robin-js';
```

#### TS

```js
import {
  SequentialRoundRobin,
  RandomRoundRobin,
  RoundRobinOptions, // constructor options
  RoundRobinItem // the internal item type
} from 'round-robin-js';

// other types
import { RoundRobinOptions, RoundRobinItem } 
```

