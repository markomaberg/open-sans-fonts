[![github tag][github-tag-image]][github-tag-url]
[![npm version][npm-version-image]][npm-version-url]
[![npm downloads][npm-downloads-image]][npm-downloads-url]
[![License][license-image]][license-url]

***

# npm package of Open Sans

Open Sans is a humanist sans serif typeface designed by Steve Matteson.


## Installation

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i open-sans-fonts --save
```


## Usage

This a sample for usage in a LESS file:

```
# part of your LESS file
@import '../../../node_modules/open-sans-fonts/open-sans.less';
@FontPathOpenSans: "../fonts/open-sans";
```

First import the LESS file of the font and after this overwrite the default path. That's it ...

You can do the same with SCSS/SASS too ...

```
# part of your SCSS file
$FontPathOpenSans: "../fonts/open-sans";
@import '../../../node_modules/open-sans-fonts/open-sans.scss';
```

You can do the same with Stylus too ...

```
# part of your SCSS file
$FontPathOpenSans = "../fonts/open-sans";
@import '../../../node_modules/open-sans-fonts/open-sans.styl';
```


## Source of font files

[Open Sans at FontFaceKit](https://github.com/FontFaceKit/open-sans)


## License

Fonts: Licensed under [Apache 2.0](https://github.com/dasrick/open-sans-fonts/blob/master/LICENSE)

***

[github-tag-image]: https://img.shields.io/github/tag/dasrick/open-sans-fonts.svg?style=flat-square
[github-tag-url]: https://github.com/dasrick/open-sans-fonts

[npm-version-image]: https://img.shields.io/npm/v/open-sans-fonts.svg?style=flat-square
[npm-version-url]: https://www.npmjs.com/package/open-sans-fonts
[npm-downloads-image]: https://img.shields.io/npm/dm/open-sans-fonts.svg?style=flat-square
[npm-downloads-url]: https://www.npmjs.com/package/open-sans-fonts

[license-image]: https://img.shields.io/github/license/dasrick/open-sans-fonts.svg?style=flat-square
[license-url]: https://github.com/dasrick/open-sans-fonts/blob/master/LICENSE
