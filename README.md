![Logo](admin/musiccast.png)
# ioBroker.musiccast

[![NPM version](http://img.shields.io/npm/v/iobroker.musiccast.svg)](https://www.npmjs.com/package/iobroker.musiccast)
[![Downloads](https://img.shields.io/npm/dm/iobroker.musiccast.svg)](https://www.npmjs.com/package/iobroker.musiccast)
[![Build Status](https://travis-ci.org/foxthefox/ioBroker.musiccast.svg?branch=master)](https://travis-ci.org/foxthefox/ioBroker.musiccast)


[![NPM](https://nodei.co/npm/iobroker.musiccast.png?downloads=true)](https://nodei.co/npm/iobroker.musiccast/)

adapter for Yamaha MusicCast devices like WX-010/030, YSP-1600

## Installation:
Installation requires nodejs v4 at minimum

from npm
* npm install iobroker.musiccast

actual version from github
* npm install https://github.com/foxthefox/ioBroker.musiccast/tarball/master --production

## Settings
In admin settings the IP address and the type has to be configred.
The adapter currently does not support discovery function.

## available Objects
The following objects are currently implemented:

|Object|Value|settable|Description|
|--------|-------|:-:|--------|
|{zone}.power|boolean|x|true/false -> ON/Standby|
|{zone}.mute|boolean|x|true/false -> muted/ not muted|
|{zone}.volume|value|x|0...max (max depending on device)|
|system.api_version|value|-|API Version|
|system.system_version|value|-|System Version|

## Changelog

#### 0.0.3
* more objects implemented

#### 0.0.2
* minor corrections

#### 0.0.1
* initial release with setting of IP in config-page, 
* available commands power, mute, volume
