# [Sage](https://roots.io/sage/)
[![Packagist](https://img.shields.io/packagist/vpre/roots/sage-lib.svg?style=flat-square)](https://packagist.org/packages/lunar-build/sage-lib)
[![Build Status](https://img.shields.io/travis/roots/sage-lib.svg?style=flat-square)](https://travis-ci.org/roots/sage-lib)

Sage is a WordPress starter theme with a modern development workflow.

Sage Repo: [https://github.com/roots/sage](https://github.com/roots/sage)

# Lunar notes
## How to install

Install using the following command:

```bash
composer require lunar-build/sage-installer
```

# How to maintain and release updates to Packagist

* Amend source code
* Commit and push to main branch
* Tag the release, incrementing on the previous version `git tag <version>`
* Push the tag which triggers an update to packagist repository `git push origin <version>`