# system-font-i18n-css

_A modern native system font stack for consistent multi-lingual typesetting,
  optimized by unicode ranges._

`system-font-i18n` provides twelve variations for the Sans-serif family of
system font. This font stack provides more consistent character typesetting
across multiple languages and all modern operating systems.

`system-font-i18n` is optimized to select the best system font on a
per-character basis, based on the unicode range of that character.

## [Docs](https://mirai-audio.github.io/system-font-i18n-css/)

* [Documentation](https://mirai-audio.github.io/system-font-i18n-css/)
* [CODE_OF_CONDUCT](https://github.com/mirai-audio/mir/wiki/CODE_OF_CONDUCT)
* [CONTRIBUTING](https://github.com/mirai-audio/mir/blob/master/.github/CONTRIBUTING.md)

## Installation

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
