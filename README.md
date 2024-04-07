# [CSS Reset](https://github.com/LeBryere/css_reset)

## Preview

# ⏪ CSS Reset

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-green?&style=plastic)](https://github.com/LeBryere/css_reset/blob/master/LICENSE)

## Usage

### Basic Usage

This code is a CSS reset that targets several HTML elements. It resets margins, paddings, borders, font sizes, and vertical alignment to their default values. It also resets list styles, text decorations, and quotes. Additionally, it sets table borders to collapse, and ensures that images do not exceed their parent container's width. Lastly, it includes a clearfix hack to clear floats.

## How to get started?
**Run ```npm i the-new-css-reset``` OR [Download the Latest Version](https://github.com/LeBryere/css_reset/blob/master/css/reset.css).**

**Once installed, you can use it in two different ways:**

1) Import ```/css/reset.css``` before the regular styles of the project.
2) Include the following snippet in one of the JavaScript/TypeScript entry files:
```js
import "css/reset.css";
```

```
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
   margin: 0;
   padding: 0;
   border: 0;
   font-size: 100%;
   font: inherit;
   vertical-align: baseline;
   margin-block-start: 0em;
   margin-block-end: 0em;
   margin-inline-start: 0px;
   margin-inline-end: 0px;
}

/* This comment explains that these elements had
different default display values in older versions of HTML,
and this CSS rule sets them to display as blocks in HTML5. */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
   display: block;
}

/* Sets the line-height of the body element to 1. */
body {
   line-height: 1;
}

/* Removes the default list-style from ordered and unordered lists. */
ol,
ul {
   list-style: none;
}

/* Removes the default text-decoration from anchor links. */
a {
   text-decoration: none;
}

/* Removes the default quotation marks from blockquote and q elements. */
blockquote,
q {
   quotes: none;
}

/* This rule removes the quotation marks by setting the
content of the pseudo-elements to an empty string. */
blockquote:before,
blockquote:after,
q:before,
q:after {
   content: '';
   content: none;
   position: absolute;
}

/* Sets border-collapse to collapse and border-spacing to 0 for tables. */
table {
   border-collapse: collapse;
   border-spacing: 0;
}

/* Sets the maximum width of images to 100%. */
img {
   max-width: 100%;
}

/* This creates a new block formatting context for elements
with the class "clearfix" by using the :before and :after
pseudo-elements to add an empty space. */
.clearfix:before,
.clearfix:after {
   content: " ";
   display: table;
}

.clearfix:after {
   clear: both;
}

.clearfix {
   *zoom: 1;
}

/* Sets display to grid for elements with the class "grid-container" */
.grid-container {
   display: grid;
}

/* Adds grid gap support for grid containers */
.grid-container {
   gap: 10px;
}

/* Adds grid column support for grid items */
.grid-item {
   grid-column: span 2;
}

/* Sets display to flex for elements with the class "flex-container" */
.flex-container {
   display: flex;
}

/* Sets the default flex direction to row for flex containers */
.flex-container {
   flex-direction: row;
}

/* Adds flexbox support for flex items */
.flex-item {
   flex: 1;
}
```

## Copyright and License

Copyright 2023 Lebryere. Code released under the [MIT](https://github.com/LeBryere/css_reset/blob/master/LICENSE) license.

## Browser Support

![Chrome](https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Firefox](https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Samsung Internet](https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png)
--- | --- | --- | --- | --- | --- |
88+ ✔ | 88+ ✔ | 84+ ✔ | 14+ ✔ | 75+ ✔ | 15+ ✔ |
