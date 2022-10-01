[![JaneOri](https://img.shields.io/badge/JaneOri%20%F0%9F%91%BD-I%20made%20a%20thing!-blueviolet.svg?labelColor=222222)](https://twitter.com/Jane0ri)

# css-badge
css-only badge component

Install: `$ npm install css-badge`

Then include the `/node_modules/css-badge/css-badge.css file in your project.

## Links

<a href="https://propjockey.github.io/css-badge/">Documentation</a><br>
<a href="https://github.com/propjockey/css-badge">GitHub</a><br>
<a href="https://www.npmjs.com/package/css-badge">NPM</a><br>
<a href="https://twitter.com/Jane0ri">Jane Ori</a><br>

## How?

This is using a [new CSS trick](https://twitter.com/Jane0ri/status/1575494158604996609) I came up with that enables an api like `--badge-size: lg;` in vanilla CSS.
No JS, no container queries, no build step. Just CSS. And only one single class name!

## Browser Support

Chromium Only, for now

The limiting factor for browser support is the ability to use specific syntaxes for CSS's @property's `syntax`'s syntax, including:

* [the `|` combinator](https://drafts.css-houdini.org/css-properties-values-api/#combinator),
* `"<integer>"` syntax,
* and custom-ident keywords (such as `"big | bigger | BIGGER"` from the [spec's examples](https://drafts.css-houdini.org/css-properties-values-api/#example-624a132d))

The current global user support is 72.77% [according to caniuse](https://caniuse.com/mdn-css_at-rules_property_syntax).
