[![cover][cover-src]][cover-href]
[![npm version][npm-version-src]][npm-version-href] 
[![npm downloads][npm-downloads-src]][npm-downloads-href] 
[![bundle][bundle-src]][bundle-href] [![JSDocs][jsdocs-src]][jsdocs-href]
[![License][license-src]][license-href]

# 🛡️ cryptonyx

> 🔒 Unified API for cryptographic operations in web and runtime environments, supporting Node.js, browsers, and other platforms


This library provides a single api to use [web-crypto](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API) and [Subtle Crypto](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto) in both Node.js using [Crypto Module](https://nodejs.org/api/crypto.html#crypto) and Web targets using [Web Crypto API](https://nodejs.org/api/crypto.html#crypto) using [Conditional Exports](https://nodejs.org/api/packages.html#conditional-exports).

**Requirements:**

- **Node.js**: Version **15 and above** (this library provides no polyfills for older versions!) 📦🔒
- **Browser**: [Secure Context](https://developer.mozilla.org/en-US/docs/Web/Security/Secure_Contexts) (HTTPS/Localhost) in [Supported Browsers](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto#browser_compatibility) 🌐🔒
- **Other Runtimes:** Exposed `globalThis.crypto` and `globalThis.crypto.subtle`. (you can polyfill if needed) ⚙️🔒

## 📝 Usage

Install:

```sh
# nyxi 
nyxi cryptonyx

# pnpm
pnpm install cryptonyx

# npm
npm install cryptonyx

# yarn
yarn add cryptonyx
```

Import:

```ts
// ESM
import { getRandomValues, randomUUID, subtle } from 'cryptonyx'

// CommonJS
const { subtle, randomUUID, getRandomValues } = require('cryptonyx')
```

## 🌱 Development

- 🐙 Clone this repository
- 📥 Install latest LTS version of [Node.js](https://nodejs.org/en/)
- 🔧 Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable`
- 📦 Install dependencies using [nyxi](https://github.com/nyxblabs/nyxi) 🧙 Always right package manager
- 🏃 Run `nyxr dev`


## 📜 License

[MIT](./LICENSE) - Made with 💞

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/cryptonyx?style=flat&colorA=18181B&colorB=14F195
[npm-version-href]: https://npmjs.com/package/cryptonyx
[npm-downloads-src]: https://img.shields.io/npm/dm/cryptonyx?style=flat&colorA=18181B&colorB=14F195
[npm-downloads-href]: https://npmjs.com/package/cryptonyx
[bundle-src]: https://img.shields.io/bundlephobia/minzip/cryptonyx?style=flat&colorA=18181B&colorB=14F195
[bundle-href]: https://bundlephobia.com/result?p=cryptonyx
[jsdocs-src]: https://img.shields.io/badge/jsDocs.io-reference-18181B?style=flat&colorA=18181B&colorB=14F195
[jsdocs-href]: https://www.jsdocs.io/package/cryptonyx
[license-src]: https://img.shields.io/github/license/nyxblabs/cryptonyx.svg?style=flat&colorA=18181B&colorB=14F195
[license-href]: https://github.com/nyxblabs/cryptonyx/blob/main/LICENSE

<!-- Cover -->
[cover-src]: https://raw.githubusercontent.com/nyxblabs/cryptonyx/main/.github/assets/cover-github-cryptonyx.png
[cover-href]: https://💻nyxb.ws
