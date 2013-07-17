# tpl-cli

Project template for the command line [COA](https://github.com/veged/coa)-based applications.

## What's inside?

- [mocha](http://visionmedia.github.com/mocha/) as a test framework
- [istanbul](https://github.com/gotwarlost/istanbul) as a code coverage tool
- `GNUmakefile`
  - run tests by executing `make test`
  - produce code coverage report by executing `make coverage`
- Preconfigured [Travis CI](http://travis-ci.org) integration
- Contributing Guide in CONTRIBUTING.md
- ChangeLog stub in ChangeLog.md

## How to use

Install [volo](http://volojs.org/)

    npm -g install volo

Create project using template

    volo create your-project-name arikon/tpl-cli
