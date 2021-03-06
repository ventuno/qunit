<img src="/docs/img/QUnit-Logo-Large.png" width="250" height="auto">

[![Build Status](https://github.com/qunitjs/qunit/actions/workflows/CI.yaml/badge.svg)](https://github.com/qunitjs/qunit/actions/workflows/CI.yaml)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fqunitjs%2Fqunit.svg?type=shield)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fqunitjs%2Fqunit?ref=badge_shield)
[![Coverage Status](https://coveralls.io/repos/qunitjs/qunit/badge.svg)](https://coveralls.io/github/qunitjs/qunit)
[![Reproducible Builds](https://img.shields.io/badge/Reproducible_Builds-ok-success?labelColor=1e5b96)](https://reproducible-builds.org/)
[![Chat on Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/qunitjs/qunit?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![npm](https://img.shields.io/npm/v/qunit.svg?style=flat)](https://www.npmjs.com/package/qunit)

# [QUnit](https://qunitjs.com) - A JavaScript Unit Testing Framework.

QUnit is a powerful, easy-to-use, JavaScript unit testing framework. It's used by the jQuery
project to test its code and plugins but is capable of testing any generic
JavaScript code (and even capable of testing JavaScript code on the server-side).

QUnit is especially useful for regression testing: Whenever a bug is reported,
write a test that asserts the existence of that particular bug. Then fix it and
commit both. Every time you work on the code again, run the tests. If the bug
comes up again - a regression - you'll spot it immediately and know how to fix
it, because you know what code you just changed.

Having good unit test coverage makes safe refactoring easy and cheap. You can
run the tests after each small refactoring step and always know what change
broke something.

QUnit is similar to other unit testing frameworks like JUnit, but makes use of
the features JavaScript provides and helps with testing code in the browser, such
as built in support for asynchronicity and exception handling.

## Support

If you need help using QUnit, chat with us on [Gitter](https://gitter.im/qunitjs/qunit).

To report a bug or request a new feature, [open an issue](https://github.com/qunitjs/qunit/issues).

## Contribute

If you are interested in helping develop QUnit, check out our [contributing guide](./CONTRIBUTING.md).
