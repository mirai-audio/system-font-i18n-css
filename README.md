# system-font-i18n-css

[![CircleCI](https://img.shields.io/circleci/project/github/mirai-audio/system-font-i18n-css.svg?style=flat-square)](https://circleci.com/gh/mirai-audio/system-font-i18n-css)
[![David](https://img.shields.io/david/dev/mirai-audio/system-font-i18n-css.svg?style=flat-square)](https://david-dm.org/mirai-audio/system-font-i18n-css?type=dev)
[![npm](https://img.shields.io/npm/v/system-font-i18n-css.svg)](https://www.npmjs.com/package/system-font-i18n-css)
[![npm](https://img.shields.io/npm/dm/system-font-i18n-css.svg)](https://www.npmjs.com/package/system-font-i18n-css)

_A modern system font stack for consistent multi-lingual typesetting across
platforms, optimized by unicode ranges._


`system-font-i18n` provides twelve variations for the Sans-serif family of
system font. This font stack provides more consistent character typesetting
across multiple languages and all modern operating systems.

`system-font-i18n` is optimized to select the best system font on a
per-character basis, based on the unicode range of that character.

## [Docs](https://mirai-audio.github.io/system-font-i18n-css/)

* [Documentation](https://mirai-audio.github.io/system-font-i18n-css/)
* [CODE_OF_CONDUCT](https://github.com/mirai-audio/mir/wiki/CODE_OF_CONDUCT)
* [CONTRIBUTING](.github/CONTRIBUTING.md)

## Installation

### General

The robust and preferred method is to reference the `system-font-i18n.css`
stylesheet in the `<head>` of the `html` document.  Then add the utility
helper class to the `body` `class`.

```html
<!DOCTYPE html>
<html lang=en>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <link rel="stylesheet" href="system-font-i18n.css">
</head>
<body class="system-font-i18n-sans">
  <p>this is now using the system font!</p>
</body>
```

### Ember

Use `yarn` or `npm` to install the package.

```bash
yarn add system-font-i18n-css -D
```

Add the include path to your `ember-cli-build.js` file.

```javascript
var app = new EmberApp(defaults, {
    // …
    sassOptions: {
      includePaths: [
        // …
        'node_modules/system-font-i18n-css',
        // …
      ],
    },
    // …
});
```

Import the CSS into your Ember project.

```scss
@import "system-font-i18n-css";  /* This should be AT or near the top */
/* … other imports */
```

Add the `system-font-i18n-sans` CSS classname to the element to be styled, e.g.:

```html
<!--- HTML head -->
<body class="system-font-i18n-sans">
<!-- body -->
```

## LICENSE

[MIT](LICENSE)

A product of <ruby>
  <ruby>
    青<rp>(</rp><rt>せい</rt><rp>)</rp>
    心<rp>(</rp><rt>しん</rt><rp>)</rp>
    工<rp>(</rp><rt>こう</rt><rp>)</rp>
    機<rp>(</rp><rt>き</rt><rp>)</rp>
  </ruby>
  <rp>(</rp><rt>seishinkouki</rt><rp>)</rp>
</ruby> Co., Ltd
