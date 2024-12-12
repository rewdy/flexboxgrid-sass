# Flexbox Grid Sass

This work is an adaptation from the original [Flexbox Grid](http://flexboxgrid.com/) created by @kristoferjoseph.

Grid based on the flexbox model.

* [Learn about Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Check the documentation](http://rewdy.github.io/flexboxgrid-sass)

## About

By trying the [Flexbox Grid](http://flexboxgrid.com/) we saw the internal need to a SASS version of it. Thanks to the good work of Kristopher Joseph, we forked his project and sassified it.

**This version** is a fork of the [hugeinc/flexboxgrid-sass](https://github.com/hugeinc/flexboxgrid-sass) project. It has been updated here ~~to use the correct SCSS syntax for division~~ fully comply with the Dart SASS 3.x api and the now unnecessary browser prefixing has been removed. If you still need browser prefixes for your project, you can still use this library and just run your compiled CSS through PostCSS/autoprefixer to handle it in your build.

## Install

```bash
# npm
npm add -D @rewdy/flexboxgrid-sass

# yarn
yarn add -D @rewdy/flexboxgrid-sass

# pnpm
pnpm add -D @rewdy/flexboxgrid-sass

# ...you get the idea...
```

## Use

To modify your flexbox-based grid, declare the following variables on your layout .scss

### Set the number of columns you want to use on your layout

`$flexboxgrid-grid-columns: 12;`

### Set the gutter between columns

`$flexboxgrid-gutter-width: 1rem;`

### Set a margin for the container sides

`$flexboxgrid-outer-margin: 1rem;`

### Create or remove breakpoints for your project

You can modify, remove or create breakpoints before generate the final CSS.

```scss
$flexboxgrid-breakpoints:
  sm 48rem,
  md 64rem,
  lg 80rem,
  xlg 90rem,
  newbreakpoint 120rem;
```
