# Bootstrap Sass & ESM JS

Include [Bootstrap](https://getbootstrap.com)'s source Sass and an ES Module version of our JavaScript plugins thanks to [`guybedford/es-module-shims`](https://github.com/guybedford/es-module-shims). Also includes the [Autoprefixer](https://github.com/postcss/autoprefixer) for cross-browser CSS, [Stylelint](https://stylelint.io) for Sass code quality, and [Popper](https://popper.js.org), a peer dependency of Bootstrap's JS used to position dropdowns, popovers, and tooltips.

## Edit in browser

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/twbs/examples/tree/main/packages/sass-js-esm?file=index.html)

## How to use

```sh
git clone https://github.com/twbs/examples.git
cd examples
npm install
npm start -w sass-js-esm
```