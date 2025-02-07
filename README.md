# Electron ChromeDriver

[![Linux and Mac Build Status](https://circleci.com/gh/electron/chromedriver/tree/main.svg?style=shield)](https://circleci.com/gh/electron/chromedriver/tree/main)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/43safb37jdlaeviw/branch/main?svg=true)](https://ci.appveyor.com/project/electron-bot/chromedriver/branch/main)
<br>
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)
[![devDependencies:?](https://img.shields.io/david/electron/chromedriver.svg)](https://david-dm.org/electron/chromedriver)
<br>
[![license:mit](https://img.shields.io/badge/license-mit-blue.svg)](https://opensource.org/licenses/MIT)
[![npm:](https://img.shields.io/npm/v/electron-chromedriver.svg)](https://www.npmjs.com/package/electron-chromedriver)
[![dependencies:?](https://img.shields.io/npm/dm/electron-chromedriver.svg)](https://www.npmjs.com/packages/electron-chromedriver)

Simple node module to download the [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver)
version for [Electron](http://electron.atom.io).

The major version of this library tracks the major version of the Electron
versions released. So if you are using Electron `2.0.x` you would want to use
an `electron-chromedriver` dependency of `~2.0.0` in your `package.json` file.

This library is used by [spectron](https://github.com/electron/spectron).

## Using

```sh
npm install --save-dev electron-chromedriver
chromedriver -h
```

## Custom Mirror

You can set the `ELECTRON_MIRROR` or [`NPM_CONFIG_ELECTRON_MIRROR`](https://docs.npmjs.com/misc/config#environment-variables)
environment variables to use a custom base URL for downloading ChromeDriver zips.

```sh
# Electron mirror for China
ELECTRON_MIRROR="https://npm.taobao.org/mirrors/electron/"

# Local mirror
# Example of requested URL: http://localhost:8080/1.2.0/chromedriver-v2.21-darwin-x64.zip
ELECTRON_MIRROR="http://localhost:8080/"
```

## Overriding the version downloaded

The version downloaded can be overriden by setting the `ELECTRON_CUSTOM_VERSION` environment variable.
