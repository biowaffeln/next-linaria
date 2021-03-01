# next-linaria

Linaria@3 configuration for Next.js projects. Fixes an [issue with global styles](https://github.com/callstack/linaria/issues/724#issuecomment-775643517), credit goes to [@cdebutton](https://github.com/cdebotton).

## Installation

```
npm install @biowaffeln/next-linaria @linaria/webpack-loader
```

## Setup

In your `next.config.js`:

```js
const withLinaria = require("@biowaffeln/next-linaria");

module.exports = withLinaria(/* webpack config here */);
```
