# KsVueScrollmagic

[![npm](https://img.shields.io/npm/v/ks-vue-scrollmagic.svg)](https://www.npmjs.com/package/ks-vue-scrollmagic) [![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

> Not ready yet, starting project ;)

## Installation

```bash
npm install --save ks-vue-scrollmagic
```

## Usage

### Bundler (Webpack, Rollup)

```js
import Vue from 'vue'
import KsVueScrollmagic from 'ks-vue-scrollmagic'
// You need a specific loader for CSS files like https://github.com/webpack/css-loader
import 'ks-vue-scrollmagic/dist/ks-vue-scrollmagic.css'

Vue.use(KsVueScrollmagic)
```

### Browser

```html
<!-- Include after Vue -->
<!-- Local files -->
<link rel="stylesheet" href="ks-vue-scrollmagic/dist/ks-vue-scrollmagic.css"></link>
<script src="ks-vue-scrollmagic/dist/ks-vue-scrollmagic.js"></script>

<!-- From CDN -->
<link rel="stylesheet" href="https://unpkg.com/ks-vue-scrollmagic/dist/ks-vue-scrollmagic.css"></link>
<script src="https://unpkg.com/ks-vue-scrollmagic"></script>
```

## Development

### Launch visual tests

```bash
npm run dev
```

### Launch Karma with coverage

```bash
npm run dev:coverage
```

### Build

Bundle the js and css of to the `dist` folder:

```bash
npm run build
```


## Publishing

The `prepublish` hook will ensure dist files are created before publishing. This
way you don't need to commit them in your repository.

```bash
# Bump the version first
# It'll also commit it and create a tag
npm version
# Push the bumped package and tags
git push --follow-tags
# Ship it 🚀
npm publish
```

## License

[MIT](http://opensource.org/licenses/MIT)
