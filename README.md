# connect-html-minifier
[![Build Status](https://travis-ci.org/neoziro/connect-html-minifier.svg?branch=master)](https://travis-ci.org/neoziro/connect-html-minifier)
[![Dependency Status](https://david-dm.org/neoziro/connect-html-minifier.svg?theme=shields.io)](https://david-dm.org/neoziro/connect-html-minifier)
[![devDependency Status](https://david-dm.org/neoziro/connect-html-minifier/dev-status.svg?theme=shields.io)](https://david-dm.org/neoziro/connect-html-minifier#info=devDependencies)

HTML minifier middleware for connect.

## Installing

````
npm install connect-html-minifier
````

## How to use ?

````javascript
var connect = require('connect'),
    htmlMinifier = require('connect-html-minifier');

connect()
.use(htmlMinifier({removeComments: true})
.listen(8080);
````

## Options

Options allowed are the same as options allowed in [kangax/html-minifier](https://github.com/kangax/html-minifier/).

## License

Copyright (c) 2012 Bergé Greg

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
