# Changelog


## v0.0.2


### 🚀 Enhancements

  - **crypto:** Add support for webcrypto and node crypto The code adds support for both webcrypto and node crypto. Two new files, crypto.node.ts and crypto.web.ts, are added to the project. The crypto.node.ts file exports the node crypto module, while the crypto.web.ts file exports the webcrypto module. The exported modules are then used in the main crypto.ts file to provide a consistent interface for both web and node environments. ([291db64](https://github.com/nyxblabs/cryptonyx/commit/291db64))

### 📖 Documentation

  - **README.md:** Add installation and usage instructions, requirements, and development section This commit adds installation and usage instructions for the cryptonyx library. It also adds a requirements section that outlines the necessary versions of Node.js and browser support. Finally, it adds a development section that outlines the steps to clone the repository, install dependencies, and run the development server. ([41a40d3](https://github.com/nyxblabs/cryptonyx/commit/41a40d3))

### 🏡 Chore

  - **.eslintrc): disable @next/next/no-html-link-for-pages rule and set React version to 18 ✅ test(index.test.ts): add tests for crypto.node and crypto.web 🔧 chore(polyfill.ts:** Add polyfill for globalThis.crypto to use webcrypto in node environment The commit disables the @next/next/no-html-link-for-pages rule in the .eslintrc file and sets the React version to 18. The commit also adds tests for crypto.node and crypto.web in the index.test.ts file. Finally, the commit adds a polyfill for globalThis.crypto to use webcrypto in node environment in the polyfill.ts file. ([1e3895e](https://github.com/nyxblabs/cryptonyx/commit/1e3895e))
  - **github-assets:** Add cover image for Cryptonyx repository A new cover image has been added to the .github/assets directory. This image will be used as the cover image for the Cryptonyx repository on GitHub. ([cf325a9](https://github.com/nyxblabs/cryptonyx/commit/cf325a9))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

