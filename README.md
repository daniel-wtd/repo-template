<!--
reference: https://www.makeareadme.com/
-->

<!-- github shields -->
[![Github (tag)](https://img.shields.io/github/tag/while-true-do/repo-template?style=flat-square)](https://github.com/while-true-do/repo-template/tags)
[![Github (license)](https://img.shields.io/github/license/while-true-do/repo-template?style=flat-square)](https://github.com/while-true-do/repo-template/blob/master/LICENSE)
[![Github (issues)](https://img.shields.io/github/issues/while-true-do/repo-template?style=flat-square)](https://github.com/while-true-do/repo-template/issues)
[![Github (pull requests)](https://img.shields.io/github/issues-pr/while-true-do/repo-template?style=flat-square)](https://github.com/while-true-do/repo-template/pulls)

<!-- build shields -->
[![Travis (com)](https://img.shields.io/travis/com/while-true-do/repo-template?style=flat-square)](https://travis-ci.com/while-true-do/repo-template)

# While True Do: repo-template

<DESCRIPTION>

## Table of Contents

- [Motivation](#motivation)
- [Description](#description)
- [Requirements](#requirements)
- [Install](#install)
- [Usage](#usage)
- [Known Issues](#known-issues)
- [Changelog](#changelog)
- [Contribute](#contribute)
- [Develop](#develop)
- [License](#license)
- [Contact](#contact)

## Motivation

Creating new repositories is a very common task, but can be very annoying.
Having a template will ensure some standards and a nice boilerplate to enhance.

## Description

This repository contains some templates and helpers for new repositories. You
can use the content to create a new repository, if needed.

## Usage

Most Git server providers are offering to create a repository from a template.
If this does not fit your needs, please have a look at the manual usage.

A very simple, manual workflow would look like:

```
git clone https://github.com/while-true-do/repo-template.git
cd repo-template/
rm -rf .git
mv README-xxxx.md README.md
git init
# Now edit the files to your needs.
git add .
git commit -m "Initial commit"
```

## Known Issues

None.

## Contribute

Thank you so much for considering to contribute! We are happy, when someone is
joining the hard work. Please feel free to contribute, after having a look at
the [Contributor Conventions](https://github.com/while-true-do/.github/)

- [Bugs and Feature Requests](https://github.com/while-true-do/repo-template/issues)
- [Pull Requests](https://github.com/while-true-do/repo-template/pulls)

See who has contributed already in the [KUDOS.txt](KUDOS.txt).

## Test

Automatic Testing (CI/CD) is done via [Travis CI](https://travis-ci.com/). It is
documented [here](https://docs.travis-ci.com/). You should have a look in the
[.travis.yml](./.travis.yml) and reproduce the tests before pushing your code.

## License

Except where otherwise noted, all work is [licensed](LICENSE) under a
[BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Contact

Please feel free to get in touch with the developers and contributors.

- Site <https://while-true-do.io>
- Code <https://github.com/while-true-do/-x>
- Mail [hello@while-true-do.io](mailto:hello@while-true-do.io)
- Chat [@freenode #while-true-do](https://webchat.freenode.net/#while-true-do)
