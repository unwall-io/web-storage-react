<a href="https://github.com/unwall/web-storage-react" target="__blank"><img alt="web storage react" src="https://raw.githubusercontent.com/unwall/web-storage-react/master/logo.png" width="100" /></a>

# web-storage-react

[![npm (scoped)](https://img.shields.io/npm/v/@unwall/web-storage-react)](https://www.npmjs.com/package/@unwall/web-storage-react)
[![CircleCI Status](https://img.shields.io/circleci/build/github/unwall/web-storage-react)](https://circleci.com/gh/unwall/web-storage-react)
[![Coverage Status](https://coveralls.io/repos/github/unwall/web-storage-react/badge.svg)](https://coveralls.io/github/unwall/web-storage-react)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

web-storage-react provides hooks that can be consumed by React libraries or applications. These hooks provides access to <a href="https://developers.google.com/web/fundamentals/instant-and-offline/web-storage">web storage</a> in modern web browsers as persistant storage for data that is used by React application.

## Motivation

web-storage-react is created with the ideas to provide the following:

1. Encapsulate code implementing access browser storage through from React using hooks.

Note: web-storage-react does not provide error handling when accessing web storage since the idea is that the consumer or application is the interface to the user. And is the best location to handle errors, so web-storage-react allows the errors to bubble up instead of swallowing the error.

## Quick Start Guide

### Installation

#### Using npm

`npm install --save @unwall/web-storage-react`

#### Using yarn

`yarn add @unwall/web-storage-react`

### Implemented Hooks

1. How to use useLocalStorage [useLocalStorage](/src/useLocalStorage/README.md)
2. How to use useSessionStorage (To be implemented)
3. How to use useCookies (To be implemented)
4. How to use useIndexedDb (To be implemented)
5. How to use useCacheApi (To be implemented)

## License

[MIT](LICENSE.md)
