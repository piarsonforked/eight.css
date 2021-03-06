![eight.css](https://raw.githubusercontent.com/zuck/eight.css/master/docs/art/logo.png "eight.css")

# eight.css

> A micro (and modular) CSS framework based on 8pt grid

[![npm version](https://badge.fury.io/js/eight.css.svg)](https://www.npmjs.com/package/eight.css)

## Demo

You can take a look of all **eight.css** features on demo page: [try it!](https://zuck.github.io/eight.css/)

## Usage

**Eight.css** is a modular CSS framework, so you can use it as a single bundle
or importing only the modules you need.

All **eight.css**'s CSS files are minimized but source maps are provided
for reach one of them.

### As a single bundle

You can simply link to the main CSS file in your HTML page:

```html
<link rel="stylesheet" href="eight.css">
```

### As separated modules

You can import each **eight.css**'s module as a separated CSS file.

> **IMPORTANT:** please, note that by default **eight.css** imports
**Normalize.css** and **Source Sans Pro** font when used as single bundle.
When you import separated modules, instead, they are **not** included!
This means you have to include them manually *BEFORE* importing **eight.css**
modules.

```html
<!-- Not included by default -->
<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Source+Sans+Pro">
<link rel="stylesheet" href="normalize.css">

<!-- Now you can import eight.css modules -->
<link rel="stylesheet" href="eight.grid.css">
<link rel="stylesheet" href="eight.typography.css">
<link rel="stylesheet" href="eight.images.css">
<link rel="stylesheet" href="eight.tables.css">
<link rel="stylesheet" href="eight.forms.css">
<link rel="stylesheet" href="eight.buttons.css">
```

### As a package

You can also install **eight.css** using **npm**:

```bash
$ npm install eight.css
```

## Compile CSS from scratch

You can (re)compile CSS from **Stylus** source files:

```bash
git clone git@github.com:zuck/eight.css.git
cd eight.css
npm install
npm run build
```

All (minimized) CSS files and source maps will be compiled in `lib/`.

## Reference

* https://builttoadapt.io/intro-to-the-8-point-grid-system-d2573cde8632
* https://material.io/guidelines/layout/metrics-keylines.html
* https://spec.fm/specifics/8-pt-grid

## License

The MIT License (MIT)

[Read more...](./LICENSE)

Copyright (c) 2017 Emanuele Bertoldi
