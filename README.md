# amp-module

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Circle CI][circle-ci-src]][circle-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![Dependencies][david-dm-src]][david-dm-href]
[![Standard JS][standard-js-src]][standard-js-href]

> 

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add the `amp-module` dependency with `yarn` or `npm` to your project
2. Add `amp-module` to the `modules` section of `nuxt.config.js`
3. Configure it:

```js
{
  modules: [
    // Simple usage
    'amp-module',

    // With options
    ['amp-module', { /* module options */ }]
  ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Ahad Birang <farnabaz@gmail.com>

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/dt/amp-module.svg?style=flat-square
[npm-version-href]: https://npmjs.com/package/amp-module

[npm-downloads-src]: https://img.shields.io/npm/v/amp-module/latest.svg?style=flat-square
[npm-downloads-href]: https://npmjs.com/package/amp-module

[circle-ci-src]: https://img.shields.io/circleci/project/github/nuxt-community/amp-module.svg?style=flat-square
[circle-ci-href]: https://circleci.com/gh/nuxt-community/amp-module

[codecov-src]: https://img.shields.io/codecov/c/github/nuxt-community/amp-module.svg?style=flat-square
[codecov-href]: https://codecov.io/gh/nuxt-community/amp-module

[david-dm-src]: https://david-dm.org/nuxt-community/amp-module/status.svg?style=flat-square
[david-dm-href]: https://david-dm.org/nuxt-community/amp-module

[standard-js-src]: https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square
[standard-js-href]: https://standardjs.com
