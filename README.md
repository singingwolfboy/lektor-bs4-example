# Lektor Bootstrap 4 Example

This is an example [Lektor](https://www.getlektor.com/) project that uses
[Bootstrap 4 (alpha)](https://v4-alpha.getbootstrap.com/) and
[webpack](https://webpack.github.io/). It's not very pretty, but it works.

To give it a try, you'll need both Lektor and [npm](https://www.npmjs.com/)
installed. Clone this repo and run:

```bash
lektor server -f webpack
```

## Editing Styles

You should use [Sass](http://sass-lang.com/) for your website styles.
Start by adding lines to the `webpack/scss/main.scss` file. You are also
welcome to break that file out into other, smaller files and use `@import`
to pull them back into your `main.scss` file.

## Editing Scripts

You should use the [CommonJS](http://www.commonjs.org/) or the
[AMD](https://github.com/amdjs/amdjs-api/blob/master/AMD.md) module system for
JavaScript. Start by adding lines to the `webpack/js/main.js` file.
You are also welcome to break that file out into other, smaller files and use
`require()` to pull htem back into your `main.js` file.
