[<img width="110" src="https://avatars3.githubusercontent.com/u/38539999?s=200&v=4g" />](https://picuscreative.com)

# testcafe-reporter-html

PICUS' HTML reporter generator for TestCafe automated tests. It provides an HTML report of a TestCafe task(s) execution, as well as feedback on the errors, if these occurred.

[<img src="https://img.shields.io/david/picuscreative/testcafe-reporter-html.svg" />](https://david-dm.org/picuscreative/testcafe-reporter-html)
[<img src="https://img.shields.io/david/dev/picuscreative/testcafe-reporter-html.svg" />](https://david-dm.org/picuscreative/testcafe-reporter-html?type=dev)
[![Build Status](https://travis-ci.org/picuscreative/testcafe-reporter-html.svg?branch=master)](https://travis-ci.org/picuscreative/testcafe-reporter-html)

## Table of Contents

- [Installation and setup](#installation-and-setup)
- [Contributing](#installation-and-setup)


## Installation and setup

### 1. Install package

```sh
$ npm install test-reporter-html
```

### 2. Configure

If no configuration is specified the report file is called `report.html` in the current project's path.
A configuration file `tcr-html.config.js` can be used to specify any of those values:

```js
// tcr-html.config.js
module.exports = {
  fileName: 'test.html',
  outputPath: 'public',
};
```

### 3. Add the reporter flag to your test task runner

```sh
$ testcafe chrome test_folder/ --reporter html
```

## Contributing

If you'd like to contribute a feature or bugfix: Thanks! To make sure your
fix/feature has a high chance of being included, please read the following
guidelines:

1. Post a [pull request](https://github.com/picuscreative/testcafe-reporter-html/compare/).
2. Make sure there are tests! We will not accept any patch that is not tested.
   It's a rare time when explicit tests aren't needed. If you have questions
   about writing tests for testcafe-reporter-html, please open a
   [GitHub issue](https://github.com/picuscreative/testcafe-reporter-html/issues/new).

Please see [`CONTRIBUTING.md`](./CONTRIBUTING.md) for more details on contributing and running test.

Thank you to all [the contributors](https://github.com/picuscreative/testcafe-reporter-html/graphs/contributors)!

By participating in this project, you agree to abide by the PICUS [code of conduct](https://picuscreative.com/code-of-conduct).

## LICENSE

[MIT License](https://opensource.org/licenses/MIT) - [PICUS](https://picuscreative.com)
