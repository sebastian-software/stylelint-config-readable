# Stylelint Config Readable<br/>[![Sponsored by][sponsor-img]][sponsor] [![Version][npm-img]][npm] [![Dependencies][deps-img]][deps]

[sponsor-img]: https://img.shields.io/badge/Sponsored%20by-Sebastian%20Software-692446.svg
[sponsor]: https://www.sebastian-software.de
[deps]: https://david-dm.org/sebastian-software/stylelint-config-readable
[deps-img]: https://david-dm.org/sebastian-software/stylelint-config-readable/status.svg
[npm]: https://www.npmjs.com/package/stylelint-config-readable
[npm-img]: https://badge.fury.io/js/stylelint-config-readable.svg

> "If you want your code to be easy to write, make it easy to read." — Robert C. Martin

The aim of this configuration is to achieve optimal readable code for a large number of projects. In many cases, the easing of the code's looseness in comparison to its compactness is an advantage for this. The idea is that code is much more read than written. Clear and structured code is therefore valuable for each additional author.

The code should appear uniform no matter how many authors are involved. But of course, it is not only about formatting (which could be fully solved with new tools like [Prettier](https://prettier.io/)) but also about avoiding errors and mentoring developers. As you will see the chosen infrastructure with ESLint as a backbone offers so much more.

There is also the matching [ESLint Configuration](https://www.npmjs.com/package/eslint-config-readable) available.


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


## Usage

Installation with `npm`:

```bash
npm install --save-dev stylelint-config-readable stylelint
```

Installation with `yarn`:

```bash
yarn add --dev stylelint-config-readable stylelint
```

Add the preset to your stylelint config e.g. `.stylelintrc.yml`

```yaml
extends:
  - stylelint-config-readable
```

Though this configuration is meant to be usable without any further configuration you are naturally free to extend it and place overrides into your configuration e.g. by extending the `rules` section:

```yaml
extends:
  - stylelint-config-readable
rules:
  indentation: 4
```


## Copyright

<img src="https://cdn.rawgit.com/sebastian-software/sebastian-software-brand/0d4ec9d6/sebastiansoftware-en.svg" alt="Logo of Sebastian Software GmbH, Mainz, Germany" width="460" height="160"/>

Copyright 2015-2018<br/>[Sebastian Software GmbH](http://www.sebastian-software.de)
