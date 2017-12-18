# Stylelint Config Readable<br/>[![Sponsored by][sponsor-img]][sponsor] [![Version][npm-img]][npm] [![Dependencies][deps-img]][deps] [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

[sponsor-img]: https://img.shields.io/badge/Sponsored%20by-Sebastian%20Software-692446.svg
[sponsor]: https://www.sebastian-software.de
[deps]: https://david-dm.org/sebastian-software/stylelint-config-readable
[deps-img]: https://david-dm.org/sebastian-software/stylelint-config-readable/status.svg
[npm]: https://www.npmjs.com/package/stylelint-config-readable
[npm-img]: https://badge.fury.io/js/stylelint-config-readable.svg


> "If you want your code to be easy to write, make it easy to read." -- Robert C. Martin


## Features

- Blocks usage of `!important`.
- Correctly supports typical *Sass* dialects like `@mixin`.
- Tolerates `normalize` PostCSS plugin for automatically cherry-pick required normalization features.
- Tolerates CSS Modules `composes` feature.
- Tolerates Lost Grid features.
- Checks CSS animation/transition for performance issues.

## Formatting

- Use 2 spaces for indention
- 80 characters max line length
- Use lowercase properties, selectors, mixin names, etc. only
- Requires property splitting between layout (position, margin, padding, size) and visuals (appearance, colors, animation)


## Copyright

<img src="https://github.com/sebastian-software/sebastian-software-brand/raw/master/sebastiansoftware-en.svg?sanitize=true" alt="Sebastian Software GmbH Logo" width="250" />

Copyright 2015-2018<br/>[Sebastian Software GmbH](http://www.sebastian-software.de)
