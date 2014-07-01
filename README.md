percent-encode
==============

Just one utility function for percent encoding strings as described in RFC 3986, Section 2.1
  
This can be used when creating OAuth signatures.

## Installation

  npm install percent-encode --save

## Usage

  var percentEncode = require('percent-encode');

  console.log('Percent encoding string "A message": ' +
      percentEncode('A message'));

## Tests

  npm test

## Author

  Mattias Erlo, <mattias.erlo@gmail.com>

## License

  BSD2-clause

## Release History

* 0.1.0 Initial release

