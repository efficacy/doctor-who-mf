# doctor-who-mf

[![NPM](https://nodei.co/npm/doctor-who-mf.png?downloads=true)](https://nodei.co/npm/doctor-who-mf/)

A Doctor Who [quote-mf](https://www.npmjs.com/package/quote-mf) module.

## Installation
```bash
npm install quote-mf doctor-who-mf
```

## Usage
```js
var quote = require('quote-mf').quote
var doctor = require('doctor-who-mf')

var quotation = quote(doctor, ['Tenth Doctor', 'shutdown'])
console.log('%s: %s', quotation.who, quotation.text)
```

## Output
```
Tenth Doctor: I don’t want to go!
```