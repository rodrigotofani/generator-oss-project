# <%= project %>

[![Travis Status][travis-badge]][travis-url]
[![AppVeyor Status][appveyor-badge]][appveyor-url]
[![CircleCI Status][circleci-badge]][circleci-url]
[![Coveralls Status][coveralls-badge]][coveralls-url]
[![NPM Version][npm-badge]][npm-url]
[![License][license-badge]][license-url]

> <%= description %>

Long description.

## Installation

Install package

```bash
$ npm install --save <%= project %>
```

## Usage

Say `It works!`

```js
const lib = require('<%= project %>');

lib.hello((err, message) => {
  if (err) return console.error(err);
  
  console.log(message);
});
```

## Development

* Cloning the repo

```bash
$ git clone https://github.com/<%= username %>/<%= project %>.git
```

* Installing dependencies

```bash
$ npm install
```

* Running scripts

Action | Usage
---    | ---
Starting development mode                | `npm start`
Linting code                             | `npm run lint`
Running unit tests                       | `npm run jest`
Running code coverage                    | `npm run coverage`
Running lint + tests                     | `npm test`
Sending coverage results to Coveralls.io | `npm run coveralls`

## Author
[<%= name%>](https://twitter.com/<%= username %>)

## License
[MIT](https://github.com/<%= username %>/<%= project %>/blob/master/LICENSE)

[travis-badge]: https://travis-ci.org/<%= username %>/<%= project %>.svg?branch=master
[travis-url]: https://travis-ci.org/<%= username %>/<%= project %>

[appveyor-badge]: https://ci.appveyor.com/api/projects/status/github/<%= username %>/<%= project %>?branch=master&svg=true
[appveyor-url]: https://ci.appveyor.com/project/<%= username %>/<%= project %>

[circleci-badge]: https://circleci.com/gh/<%= username %>/<%= project %>/tree/master.svg?style=shield
[circleci-url]: https://circleci.com/gh/<%= username %>/<%= project %>

[coveralls-badge]: https://coveralls.io/repos/github/<%= username %>/<%= project %>/badge.svg?branch=master
[coveralls-url]: https://coveralls.io/github/<%= username %>/<%= project %>?branch=master

[npm-badge]: https://img.shields.io/npm/v/<%= project %>.svg
[npm-url]: https://www.npmjs.com/package/<%= project %>

[license-badge]: https://img.shields.io/github/license/<%= username %>/<%= project %>.svg
[license-url]: https://opensource.org/licenses/MIT