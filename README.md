# tsvtojson
> tsv <=> json

[![Build Status][travis]][travis-url]
[![npm][npm-download]][npm-dl-url]
[![contributions welcome][contri-badge]][contri-url]

## Installation
```shell
npm install --save tsvtojson
```

## Example
```javascript
const tsvtojson = require('tsvtojson');
tsvtojson('./file/path.ext',['header1','header2','header3'])
	.then(data=>{
		console.log(data);
	})
	.catch(err=>{
		console.log(err);
	})
```

## License
[MIT](./LICENSE)

[contri-badge]: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat
[contri-url]: https://github.com/AungMyoKyaw/tsvtojson/issues
[npm-download]: https://img.shields.io/npm/dt/tsvtojson.svg
[npm-dl-url]: https://www.npmjs.com/package/tsvtojson
[travis]: https://travis-ci.org/AungMyoKyaw/tsvtojson.svg?branch=master
[travis-url]: https://travis-ci.org/AungMyoKyaw/tsvtojson
