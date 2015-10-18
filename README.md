# Electron ChromeDriver

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)
[![Build Status](https://travis-ci.org/kevinsawicki/electron-chromedriver.svg?branch=master)](https://travis-ci.org/kevinsawicki/electron-chromedriver)
[![devDependencies:?](https://img.shields.io/david/kevinsawicki/electron-chromedriver.svg)](https://david-dm.org/kevinsawicki/electron-chromedriver)
<br>
[![license:mit](https://img.shields.io/badge/license-mit-blue.svg)](https://opensource.org/licenses/MIT)
[![npm:](https://img.shields.io/npm/v/electron-chromedriver.svg)](https://www.npmjs.com/packages/electron-chromedriver)
[![dependencies:?](https://img.shields.io/npm/dm/electron-chromedriver.svg)](https://www.npmjs.com/packages/electron-chromedriver)

Simple node module to download the [ChromeDriver](https://code.google.com/p/selenium/wiki/ChromeDriver)
version for [Electron](http://electron.atom.io).

This minor version of this library tracks the minor version of the Electron
versions released. So if you are using Electron `0.34.x` you would want to use
a `electron-chromedriver` dependency of `^0.34` in your `package.json` file.

This library is used by [spectron](https://github.com/kevinsawicki/spectron).

## Using

```sh
npm install --save-dev electron-chromedriver
chromedriver -h
```
