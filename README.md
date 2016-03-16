# generator-node-bahmutov

[![NPM][generator-node-bahmutov-icon] ][generator-node-bahmutov-url]

[![Build status][generator-node-bahmutov-ci-image] ][generator-node-bahmutov-ci-url]
[![semantic-release][semantic-image] ][semantic-url]

Goal: replace the questions and answers from `npm init` with values collected from
the environment.

Following [the instructions](http://yeoman.io/authoring/index.html)

## Test

Change into an empty folder, for example

    cd /tmp
    mkdir test-generator
    cd test-generator
    yo node-bahmutov

## Debugging

Run the generator with environment variable DEBUG set to "gen"

    DEBUG=gen yo node-bahmutov

## Development

## Goal

Trying to recreate all the information asked for during `npm init` command (plus a few good
defaults)

```json
{
  "name": "test-generator",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "dependencies": {},
  "devDependencies": {},
  "scripts": {
    "test": "mocha"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```

### Small print

Author: Gleb Bahmutov &copy; 2016

* [@bahmutov](https://twitter.com/bahmutov)
* [glebbahmutov.com](http://glebbahmutov.com)
* [blog](http://glebbahmutov.com/blog/)

License: MIT - do anything with the code, but don't blame me if it does not work.

Spread the word: tweet, star on github, etc.

Support: if you find any problems with this module, email / tweet /
[open issue](https://github.com/bahmutov/generator-node-bahmutov/issues) on Github

## MIT License

Copyright (c) 2016 Gleb Bahmutov

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

[generator-node-bahmutov-icon]: https://nodei.co/npm/generator-node-bahmutov.png?downloads=true
[generator-node-bahmutov-url]: https://npmjs.org/package/generator-node-bahmutov
[generator-node-bahmutov-ci-image]: https://travis-ci.org/bahmutov/generator-node-bahmutov.png?branch=master
[generator-node-bahmutov-ci-url]: https://travis-ci.org/bahmutov/generator-node-bahmutov
[semantic-image]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-url]: https://github.com/semantic-release/semantic-release
