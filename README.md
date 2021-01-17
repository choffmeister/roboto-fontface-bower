# Roboto fontface

**This repository has been archived. Please visit https://github.com/fontsource/fontsource for a better, actively maintained alternative that also provides many more open source fonts.**

## Installing

Assuming you have [NodeJS](http://nodejs.org/), [NPM](https://www.npmjs.com/) and [Bower](http://bower.io/) installed globally just open up a terminal, navigate to your projects root directory and then execute

```
# install via NPM
$ npm install roboto-fontface --save

# install via Bower
$ bower install roboto-fontface --save
```


## Usage

There're several files in the `css/` subdirectory. Import them in your project
to have access to "Roboto" font face:

* `css/roboto/roboto-fontface.css` - whole font family compiled to CSS
* `css/roboto/sass/roboto-fontface.scss` - whole font family in SCSS
* `css/roboto/less/roboto-fontface.less` - whole font family in LESS

* `css/roboto-condensed/roboto-condensed-fontface.css` - whole font family compiled to CSS
* `css/roboto-condensed/sass/roboto-condensed-fontface.scss` - whole font family in SCSS
* `css/roboto-condensed/less/roboto-condensed-fontface.less` - whole font family in LESS

* `css/roboto-slab/roboto-slab-fontface.css` - whole font family compiled to CSS
* `css/roboto-slab/sass/roboto-slab-fontface.scss` - whole font family in SCSS
* `css/roboto-slab/less/roboto-slab-fontface.less` - whole font family in LESS

Importing whole family may be unnecessary and lead to huge build, so if you are
using SCSS or LESS, you can import only individual weights by importing for example:

* `css/roboto/sass/roboto-fontface-black.scss`
* `css/roboto/sass/roboto-fontface-black-italic.scss`

With Sass/Less, you can adjust the font path to your needs with the `$roboto-font-path` variable. For example (Sass):

```sass
$roboto-font-path: 'path/where/you/put/fonts'
@import 'node_modules/roboto-fontface/css/roboto/sass/roboto-fontface.scss'
```

## Hinting

Some of the included font files have [hinting](http://en.wikipedia.org/wiki/Font_hinting).

| Files    | Hinting |
|----------|---------|
| `.woff`  | yes     |
| `.woff2` | ?       |
