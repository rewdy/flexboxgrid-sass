Flexbox Grid Sass
===========
This work is an adaptation from the original Flexbox Grid created by @kristoferjoseph. This project aims to provide the benefits of the SASS pre-processor to the original grid, initially written in plain CSS.

Grid based on the `flex` display property.

http://hugeinc.github.io/flexboxgrid-sass

Install
---------
### npm
`npm i flexboxgrid-sass --save`

### bower
`bower install --save flexboxgrid-sass`

Use
---------
To modify the Flexbox grid, declare the following variables on your layout .scss

#### Set the number of columns you want to use on your layout.
`$grid-columns: 12;`

#### Set the gutter between columns.

`$gutter-width: 1rem;`

#### Set a margin for the container sides.

`$outer-margin: 1rem;`

####  Create or remove breakpoints for your project
You can modify, remove or create breakpoints before generate the final CSS.

```
$breakpoints:
  sm 48rem,
  md 64rem,
  lg 80rem,
  xlg 90rem,
  newbreakpoint 120rem;
```
