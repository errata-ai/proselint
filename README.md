# proselint [![Build Status](https://travis-ci.org/errata-ai/proselint.svg?branch=master)](https://travis-ci.org/errata-ai/proselint) ![Vale version](https://img.shields.io/badge/vale-%3E%3D%20v1.7.0-blue.svg) ![license](https://img.shields.io/github/license/mashape/apistatus.svg)

> [`proselint`](https://github.com/amperser/proselint/) places the world’s greatest writers and editors by your side, where they whisper suggestions on how to improve your prose.

This repository contains a [Vale-compatible](https://github.com/errata-ai/vale) implementation of the guidelines enforced by the `proselint` ([LICENSE](https://github.com/amperser/proselint/blob/master/LICENSE.md)) linter.

## Getting Started

To get started, add the package to your configuration file (as shown below) and then run `vale sync`.

```ini
StylesPath = styles
MinAlertLevel = suggestion

Packages = proselint

[*]
BasedOnStyles = proselint
```
