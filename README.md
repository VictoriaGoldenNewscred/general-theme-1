# general-theme-1
General Theme version 1.0
/*
Theme Name:         NewsCred General
Description:        NewsCred General is the CMC Starter Theme
Version:            1.0
Author:             Gregory Maher
Author URI:         http://looknorthinc.com/

License:            MIT License
License URI:        http://www.opensource.org/licenses/mit-license.php
*/
/* ---------------------------------------------------------------------------- 
  
  Unfortunately WordPress will require a style.css file
  located in the theme's root folder for stuff to work.

  However, we will not be using vanilla CSS. We're using Sass.

  Sass is a superset of CSS that adds in amazing features
  such as variables, nested selectors and loops. It's also
  the easiest way to customize Foundation.

  All Sass files are located in the /scss folder.

  Please read the README.md file before getting started. More info on how
  to use Sass with Foundation can be found here:
  http://foundation.zurb.com/docs/sass.html

  If you for some reason would like to write plain css instead of using Sass,
  you could just enqueue this file (style.css) to the header and add your styles in this file

---------------------------------------------------------------------------- */
/*! normalize.css v3.0.2 | MIT License | git.io/normalize */
/*! normalize.css v3.0.2 | MIT License | git.io/normalize */
/**
 * 1. Set default font family to sans-serif.
 * 2. Prevent iOS text size adjust after orientation change, without disabling
 *    user zoom.
 */
html {
  font-family: sans-serif;
  /* 1 */
  -ms-text-size-adjust: 100%;
  /* 2 */
  -webkit-text-size-adjust: 100%;
  /* 2 */ }

/**
 * Remove default margin.
 */
body {
  margin: 0; }

/* HTML5 display definitions
   ========================================================================== */
/**
 * Correct `block` display not defined for any HTML5 element in IE 8/9.
 * Correct `block` display not defined for `details` or `summary` in IE 10/11
 * and Firefox.
 * Correct `block` display not defined for `main` in IE 11.
 */
article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary {
  display: block; }

/**
 * 1. Correct `inline-block` display not defined in IE 8/9.
 * 2. Normalize vertical alignment of `progress` in Chrome, Firefox, and Opera.
 */
audio, canvas, progress, video {
  display: inline-block;
  /* 1 */
  vertical-align: baseline;
  /* 2 */ }

/**
 * Prevent modern browsers from displaying `audio` without controls.
 * Remove excess height in iOS 5 devices.
 */
audio:not([controls]) {
  display: none;
  height: 0; }

/**
 * Address `[hidden]` styling not present in IE 8/9/10.
 * Hide the `template` element in IE 8/9/11, Safari, and Firefox < 22.
 */
[hidden], template {
  display: none; }

/* Links
   ========================================================================== */
/**
 * Remove the gray background color from active links in IE 10.
 */
a {
  background-color: transparent; }

/**
 * Improve readability when focused and also mouse hovered in all browsers.
 */
a:active, a:hover {
  outline: 0; }

/* Text-level semantics
   ========================================================================== */
/**
 * Address styling not present in IE 8/9/10/11, Safari, and Chrome.
 */
abbr[title] {
  border-bottom: 1px dotted; }

/**
 * Address style set to `bolder` in Firefox 4+, Safari, and Chrome.
 */
b, strong {
  font-weight: bold; }

/**
 * Address styling not present in Safari and Chrome.
 */
dfn {
  font-style: italic; }

/**
 * Address variable `h1` font-size and margin within `section` and `article`
 * contexts in Firefox 4+, Safari, and Chrome.
 */
h1 {
  font-size: 2em;
  margin: 0.67em 0; }

/**
 * Address styling not present in IE 8/9.
 */
mark {
  background: #ff0;
  color: #000; }

/**
 * Address inconsistent and variable font size in all browsers.
 */
small {
  font-size: 80%; }

/**
 * Prevent `sub` and `sup` affecting `line-height` in all browsers.
 */
sub, sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline; }

sup {
  top: -0.5em; }

sub {
  bottom: -0.25em; }

/* Embedded content
   ========================================================================== */
/**
 * Remove border when inside `a` element in IE 8/9/10.
 */
img {
  border: 0; }

/**
 * Correct overflow not hidden in IE 9/10/11.
 */
svg:not(:root) {
  overflow: hidden; }

/* Grouping content
   ========================================================================== */
/**
 * Address margin not present in IE 8/9 and Safari.
 */
figure {
  margin: 1em 40px; }

/**
 * Address differences between Firefox and other browsers.
 */
hr {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
  height: 0; }

/**
 * Contain overflow in all browsers.
 */
pre {
  overflow: auto; }

/**
 * Address odd `em`-unit font size rendering in all browsers.
 */
code, kbd, pre, samp {
  font-family: monospace, monospace;
  font-size: 1em; }

/* Forms
   ========================================================================== */
/**
 * Known limitation: by default, Chrome and Safari on OS X allow very limited
 * styling of `select`, unless a `border` property is set.
 */
/**
 * 1. Correct color not being inherited.
 *    Known issue: affects color of disabled elements.
 * 2. Correct font properties not being inherited.
 * 3. Address margins set differently in Firefox 4+, Safari, and Chrome.
 */
button, input, optgroup, select, textarea {
  color: inherit;
  /* 1 */
  font: inherit;
  /* 2 */
  margin: 0;
  /* 3 */ }

/**
 * Address `overflow` set to `hidden` in IE 8/9/10/11.
 */
button {
  overflow: visible; }

/**
 * Address inconsistent `text-transform` inheritance for `button` and `select`.
 * All other form control elements do not inherit `text-transform` values.
 * Correct `button` style inheritance in Firefox, IE 8/9/10/11, and Opera.
 * Correct `select` style inheritance in Firefox.
 */
button, select {
  text-transform: none; }

/**
 * 1. Avoid the WebKit bug in Android 4.0.* where (2) destroys native `audio`
 *    and `video` controls.
 * 2. Correct inability to style clickable `input` types in iOS.
 * 3. Improve usability and consistency of cursor style between image-type
 *    `input` and others.
 */
button, html input[type="button"], input[type="reset"], input[type="submit"] {
  -webkit-appearance: button;
  /* 2 */
  cursor: pointer;
  /* 3 */ }

/**
 * Re-set default cursor for disabled elements.
 */
button[disabled], html input[disabled] {
  cursor: default; }

/**
 * Remove inner padding and border in Firefox 4+.
 */
button::-moz-focus-inner, input::-moz-focus-inner {
  border: 0;
  padding: 0; }

/**
 * Address Firefox 4+ setting `line-height` on `input` using `!important` in
 * the UA stylesheet.
 */
input {
  line-height: normal; }

/**
 * It's recommended that you don't attempt to style these elements.
 * Firefox's implementation doesn't respect box-sizing, padding, or width.
 *
 * 1. Address box sizing set to `content-box` in IE 8/9/10.
 * 2. Remove excess padding in IE 8/9/10.
 */
input[type="checkbox"], input[type="radio"] {
  box-sizing: border-box;
  /* 1 */
  padding: 0;
  /* 2 */ }

/**
 * Fix the cursor style for Chrome's increment/decrement buttons. For certain
 * `font-size` values of the `input`, it causes the cursor style of the
 * decrement button to change from `default` to `text`.
 */
input[type="number"]::-webkit-inner-spin-button, input[type="number"]::-webkit-outer-spin-button {
  height: auto; }

/**
 * 1. Address `appearance` set to `searchfield` in Safari and Chrome.
 * 2. Address `box-sizing` set to `border-box` in Safari and Chrome
 *    (include `-moz` to future-proof).
 */
input[type="search"] {
  -webkit-appearance: textfield;
  /* 1 */
  -moz-box-sizing: content-box;
  -webkit-box-sizing: content-box;
  /* 2 */
  box-sizing: content-box; }

/**
 * Remove inner padding and search cancel button in Safari and Chrome on OS X.
 * Safari (but not Chrome) clips the cancel button when the search input has
 * padding (and `textfield` appearance).
 */
input[type="search"]::-webkit-search-cancel-button, input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none; }

/**
 * Define consistent border, margin, and padding.
 */
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em; }

/**
 * 1. Correct `color` not being inherited in IE 8/9/10/11.
 * 2. Remove padding so people aren't caught out if they zero out fieldsets.
 */
legend {
  border: 0;
  /* 1 */
  padding: 0;
  /* 2 */ }

/**
 * Remove default vertical scrollbar in IE 8/9/10/11.
 */
textarea {
  overflow: auto; }

/**
 * Don't inherit the `font-weight` (applied by a rule above).
 * NOTE: the default cannot safely be changed in Chrome and Safari on OS X.
 */
optgroup {
  font-weight: bold; }

/* Tables
   ========================================================================== */
/**
 * Remove most spacing between table cells.
 */
table {
  border-collapse: collapse;
  border-spacing: 0; }

td, th {
  padding: 0; }

/*  
  ZURB Foundation components:
  Import the building blocks you need for your project. 
  Reducing the number of imported components will optimize page speed.
*/
meta.foundation-version {
  font-family: "/5.5.1/"; }

meta.foundation-mq-small {
  font-family: "/only screen/";
  width: 0em; }

meta.foundation-mq-small-only {
  font-family: "/only screen and (max-width: 40em)/";
  width: 0em; }

meta.foundation-mq-medium {
  font-family: "/only screen and (min-width:40.063em)/";
  width: 40.063em; }

meta.foundation-mq-medium-only {
  font-family: "/only screen and (min-width:40.063em) and (max-width:64em)/";
  width: 40.063em; }

meta.foundation-mq-large {
  font-family: "/only screen and (min-width:64.063em)/";
  width: 64.063em; }

meta.foundation-mq-large-only {
  font-family: "/only screen and (min-width:64.063em) and (max-width:90em)/";
  width: 64.063em; }

meta.foundation-mq-xlarge {
  font-family: "/only screen and (min-width:90.063em)/";
  width: 90.063em; }

meta.foundation-mq-xlarge-only {
  font-family: "/only screen and (min-width:90.063em) and (max-width:120em)/";
  width: 90.063em; }

meta.foundation-mq-xxlarge {
  font-family: "/only screen and (min-width:120.063em)/";
  width: 120.063em; }

meta.foundation-data-attribute-namespace {
  font-family: false; }

html, body {
  height: 100%; }

*, *:before, *:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box; }

html, body {
  font-size: 100%; }

body {
  background: #fff;
  color: #565656;
  padding: 0;
  margin: 0;
  font-family: arial, sans-serif;;
  font-weight: 400;
  font-style: normal;
  line-height: 1.5;
  position: relative;
  cursor: auto; }

a:hover {
  cursor: pointer; }

img {
  max-width: 100%;
  height: auto; }

img {
  -ms-interpolation-mode: bicubic; }

#map_canvas img, #map_canvas embed, #map_canvas object, .map_canvas img, .map_canvas embed, .map_canvas object {
  max-width: none !important; }

.left {
  float: left !important; }

.right {
  float: right !important; }

.clearfix:before, .clearfix:after {
  content: " ";
  display: table; }
.clearfix:after {
  clear: both; }

.hide {
  display: none; }

.invisible {
  visibility: hidden; }

.antialiased {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; }

img {
  display: inline-block;
  vertical-align: middle; }

textarea {
  height: auto;
  min-height: 50px; }

select {
  width: 100%; }

.row {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 0;
  margin-bottom: 0;
  max-width: 68.75rem; }
  .row:before, .row:after {
    content: " ";
    display: table; }
  .row:after {
    clear: both; }
  .row.collapse > .column, .row.collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row .row {
    width: auto;
    margin-left: -0.9375rem;
    margin-right: -0.9375rem;
    margin-top: 0;
    margin-bottom: 0;
    max-width: none; }
    .row .row:before, .row .row:after {
      content: " ";
      display: table; }
    .row .row:after {
      clear: both; }
    .row .row.collapse {
      width: auto;
      margin: 0;
      max-width: none; }
      .row .row.collapse:before, .row .row.collapse:after {
        content: " ";
        display: table; }
      .row .row.collapse:after {
        clear: both; }

.column, .columns {
  padding-left: 0.9375rem;
  padding-right: 0.9375rem;
  width: 100%;
  float: left; }

[class*="column"] + [class*="column"]:last-child {
  float: right; }

[class*="column"] + [class*="column"].end {
  float: left; }

@media only screen {
  .small-push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .small-pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .small-push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .small-pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .small-push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .small-pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .small-push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .small-pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .small-push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .small-pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .small-push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .small-pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .small-push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .small-pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .small-push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .small-pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .small-push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .small-pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .small-push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .small-pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .small-push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .small-pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .small-push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .small-pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .small-push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .small-pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .small-push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .small-pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .small-push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .small-pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .small-push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .small-pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; }
  .column, .columns {
    position: relative;
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .small-1 {
    width: 6.25%; }
  .small-2 {
    width: 12.5%; }
  .small-3 {
    width: 18.75%; }
  .small-4 {
    width: 25%; }
  .small-5 {
    width: 31.25%; }
  .small-6 {
    width: 37.5%; }
  .small-7 {
    width: 43.75%; }
  .small-8 {
    width: 50%; }
  .small-9 {
    width: 56.25%; }
  .small-10 {
    width: 62.5%; }
  .small-11 {
    width: 68.75%; }
  .small-12 {
    width: 75%; }
  .small-13 {
    width: 81.25%; }
  .small-14 {
    width: 87.5%; }
  .small-15 {
    width: 93.75%; }
  .small-16 {
    width: 100%; }
  .small-offset-0 {
    margin-left: 0% !important; }
  .small-offset-1 {
    margin-left: 6.25% !important; }
  .small-offset-2 {
    margin-left: 12.5% !important; }
  .small-offset-3 {
    margin-left: 18.75% !important; }
  .small-offset-4 {
    margin-left: 25% !important; }
  .small-offset-5 {
    margin-left: 31.25% !important; }
  .small-offset-6 {
    margin-left: 37.5% !important; }
  .small-offset-7 {
    margin-left: 43.75% !important; }
  .small-offset-8 {
    margin-left: 50% !important; }
  .small-offset-9 {
    margin-left: 56.25% !important; }
  .small-offset-10 {
    margin-left: 62.5% !important; }
  .small-offset-11 {
    margin-left: 68.75% !important; }
  .small-offset-12 {
    margin-left: 75% !important; }
  .small-offset-13 {
    margin-left: 81.25% !important; }
  .small-offset-14 {
    margin-left: 87.5% !important; }
  .small-offset-15 {
    margin-left: 93.75% !important; }
  .small-reset-order {
    margin-left: 0;
    margin-right: 0;
    left: auto;
    right: auto;
    float: left; }
  .column.small-centered, .columns.small-centered {
    margin-left: auto;
    margin-right: auto;
    float: none; }
  .column.small-uncentered, .columns.small-uncentered {
    margin-left: 0;
    margin-right: 0;
    float: left; }
  .column.small-centered:last-child, .columns.small-centered:last-child {
    float: none; }
  .column.small-uncentered:last-child, .columns.small-uncentered:last-child {
    float: left; }
  .column.small-uncentered.opposite, .columns.small-uncentered.opposite {
    float: right; }
  .row.small-collapse > .column, .row.small-collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.small-collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row.small-uncollapse > .column, .row.small-uncollapse > .columns {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; } }

@media only screen and (min-width:40.063em) {
  .medium-push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .medium-pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .medium-push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .medium-pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .medium-push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .medium-pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .medium-push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .medium-pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .medium-push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .medium-pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .medium-push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .medium-pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .medium-push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .medium-pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .medium-push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .medium-pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .medium-push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .medium-pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .medium-push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .medium-pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .medium-push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .medium-pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .medium-push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .medium-pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .medium-push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .medium-pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .medium-push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .medium-pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .medium-push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .medium-pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .medium-push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .medium-pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; }
  .column, .columns {
    position: relative;
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .medium-1 {
    width: 6.25%; }
  .medium-2 {
    width: 12.5%; }
  .medium-3 {
    width: 18.75%; }
  .medium-4 {
    width: 25%; }
  .medium-5 {
    width: 31.25%; }
  .medium-6 {
    width: 37.5%; }
  .medium-7 {
    width: 43.75%; }
  .medium-8 {
    width: 50%; }
  .medium-9 {
    width: 56.25%; }
  .medium-10 {
    width: 62.5%; }
  .medium-11 {
    width: 68.75%; }
  .medium-12 {
    width: 75%; }
  .medium-13 {
    width: 81.25%; }
  .medium-14 {
    width: 87.5%; }
  .medium-15 {
    width: 93.75%; }
  .medium-16 {
    width: 100%; }
  .medium-offset-0 {
    margin-left: 0% !important; }
  .medium-offset-1 {
    margin-left: 6.25% !important; }
  .medium-offset-2 {
    margin-left: 12.5% !important; }
  .medium-offset-3 {
    margin-left: 18.75% !important; }
  .medium-offset-4 {
    margin-left: 25% !important; }
  .medium-offset-5 {
    margin-left: 31.25% !important; }
  .medium-offset-6 {
    margin-left: 37.5% !important; }
  .medium-offset-7 {
    margin-left: 43.75% !important; }
  .medium-offset-8 {
    margin-left: 50% !important; }
  .medium-offset-9 {
    margin-left: 56.25% !important; }
  .medium-offset-10 {
    margin-left: 62.5% !important; }
  .medium-offset-11 {
    margin-left: 68.75% !important; }
  .medium-offset-12 {
    margin-left: 75% !important; }
  .medium-offset-13 {
    margin-left: 81.25% !important; }
  .medium-offset-14 {
    margin-left: 87.5% !important; }
  .medium-offset-15 {
    margin-left: 93.75% !important; }
  .medium-reset-order {
    margin-left: 0;
    margin-right: 0;
    left: auto;
    right: auto;
    float: left; }
  .column.medium-centered, .columns.medium-centered {
    margin-left: auto;
    margin-right: auto;
    float: none; }
  .column.medium-uncentered, .columns.medium-uncentered {
    margin-left: 0;
    margin-right: 0;
    float: left; }
  .column.medium-centered:last-child, .columns.medium-centered:last-child {
    float: none; }
  .column.medium-uncentered:last-child, .columns.medium-uncentered:last-child {
    float: left; }
  .column.medium-uncentered.opposite, .columns.medium-uncentered.opposite {
    float: right; }
  .row.medium-collapse > .column, .row.medium-collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.medium-collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row.medium-uncollapse > .column, .row.medium-uncollapse > .columns {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; } }

@media only screen and (min-width:64.063em) {
  .large-push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .large-pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .large-push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .large-pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .large-push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .large-pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .large-push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .large-pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .large-push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .large-pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .large-push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .large-pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .large-push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .large-pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .large-push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .large-pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .large-push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .large-pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .large-push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .large-pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .large-push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .large-pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .large-push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .large-pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .large-push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .large-pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .large-push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .large-pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .large-push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .large-pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .large-push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .large-pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; }
  .column, .columns {
    position: relative;
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .large-1 {
    width: 6.25%; }
  .large-2 {
    width: 12.5%; }
  .large-3 {
    width: 18.75%; }
  .large-4 {
    width: 25%; }
  .large-5 {
    width: 31.25%; }
  .large-6 {
    width: 37.5%; }
  .large-7 {
    width: 43.75%; }
  .large-8 {
    width: 50%; }
  .large-9 {
    width: 56.25%; }
  .large-10 {
    width: 62.5%; }
  .large-11 {
    width: 68.75%; }
  .large-12 {
    width: 75%; }
  .large-13 {
    width: 81.25%; }
  .large-14 {
    width: 87.5%; }
  .large-15 {
    width: 93.75%; }
  .large-16 {
    width: 100%; }
  .large-offset-0 {
    margin-left: 0% !important; }
  .large-offset-1 {
    margin-left: 6.25% !important; }
  .large-offset-2 {
    margin-left: 12.5% !important; }
  .large-offset-3 {
    margin-left: 18.75% !important; }
  .large-offset-4 {
    margin-left: 25% !important; }
  .large-offset-5 {
    margin-left: 31.25% !important; }
  .large-offset-6 {
    margin-left: 37.5% !important; }
  .large-offset-7 {
    margin-left: 43.75% !important; }
  .large-offset-8 {
    margin-left: 50% !important; }
  .large-offset-9 {
    margin-left: 56.25% !important; }
  .large-offset-10 {
    margin-left: 62.5% !important; }
  .large-offset-11 {
    margin-left: 68.75% !important; }
  .large-offset-12 {
    margin-left: 75% !important; }
  .large-offset-13 {
    margin-left: 81.25% !important; }
  .large-offset-14 {
    margin-left: 87.5% !important; }
  .large-offset-15 {
    margin-left: 93.75% !important; }
  .large-reset-order {
    margin-left: 0;
    margin-right: 0;
    left: auto;
    right: auto;
    float: left; }
  .column.large-centered, .columns.large-centered {
    margin-left: auto;
    margin-right: auto;
    float: none; }
  .column.large-uncentered, .columns.large-uncentered {
    margin-left: 0;
    margin-right: 0;
    float: left; }
  .column.large-centered:last-child, .columns.large-centered:last-child {
    float: none; }
  .column.large-uncentered:last-child, .columns.large-uncentered:last-child {
    float: left; }
  .column.large-uncentered.opposite, .columns.large-uncentered.opposite {
    float: right; }
  .row.large-collapse > .column, .row.large-collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.large-collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row.large-uncollapse > .column, .row.large-uncollapse > .columns {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; } }

.accordion {
  margin-bottom: 0; }
  .accordion:before, .accordion:after {
    content: " ";
    display: table; }
  .accordion:after {
    clear: both; }
  .accordion .accordion-navigation, .accordion dd {
    display: block;
    margin-bottom: 0 !important; }
    .accordion .accordion-navigation.active > a, .accordion dd.active > a {
      background: #e8e8e8; }
    .accordion .accordion-navigation > a, .accordion dd > a {
      background: #EFEFEF;
      color: #222222;
      padding: 1rem;
      display: block;
      font-family: arial, sans-serif;
      font-size: 1rem; }
      .accordion .accordion-navigation > a:hover, .accordion dd > a:hover {
        background: #e3e3e3; }
    .accordion .accordion-navigation > .content, .accordion dd > .content {
      display: none;
      padding: 0.9375rem; }
      .accordion .accordion-navigation > .content.active, .accordion dd > .content.active {
        display: block;
        background: #FFFFFF; }

.alert-box {
  border-style: solid;
  border-width: 1px;
  display: block;
  font-weight: 400;
  margin-bottom: 1.25rem;
  position: relative;
  padding: 0.875rem 1.5rem 0.875rem 0.875rem;
  font-size: 0.8125rem;
  transition: opacity 300ms ease-out;
  background-color: #1f5c87;
  border-color: #db8a00;
  color: #FFFFFF; }
  .alert-box .close {
    font-size: 1.375rem;
    padding: 0 6px 4px;
    line-height: .9;
    position: absolute;
    top: 50%;
    margin-top: -0.6875rem;
    right: 0.25rem;
    color: #333333;
    opacity: 0.3;
    background: inherit; }
    .alert-box .close:hover, .alert-box .close:focus {
      opacity: 0.5; }
  .alert-box.radius {
    border-radius: 3px; }
  .alert-box.round {
    border-radius: 1000px; }
  .alert-box.success {
    background-color: #43AC6A;
    border-color: #3a945b;
    color: #FFFFFF; }
  .alert-box.alert {
    background-color: #f04124;
    border-color: #de2d0f;
    color: #FFFFFF; }
  .alert-box.secondary {
    background-color: #E7E7E7;
    border-color: #c7c7c7;
    color: #4f4f4f; }
  .alert-box.warning {
    background-color: #f08a24;
    border-color: #de770f;
    color: #FFFFFF; }
  .alert-box.info {
    background-color: #a0d3e8;
    border-color: #74bfdd;
    color: #4f4f4f; }
  .alert-box.alert-close {
    opacity: 0; }

[class*="block-grid-"] {
  display: block;
  padding: 0;
  margin: 0 -0.625rem; }
  [class*="block-grid-"]:before, [class*="block-grid-"]:after {
    content: " ";
    display: table; }
  [class*="block-grid-"]:after {
    clear: both; }
  [class*="block-grid-"] > li {
    display: block;
    height: auto;
    float: left;
    padding: 0 0.625rem 1.25rem; }

@media only screen {
  .small-block-grid-1 > li {
    width: 100%;
    list-style: none; }
    .small-block-grid-1 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-1 > li:nth-of-type(1n+1) {
      clear: both; }
  .small-block-grid-2 > li {
    width: 50%;
    list-style: none; }
    .small-block-grid-2 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-2 > li:nth-of-type(2n+1) {
      clear: both; }
  .small-block-grid-3 > li {
    width: 33.3333333333%;
    list-style: none; }
    .small-block-grid-3 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-3 > li:nth-of-type(3n+1) {
      clear: both; }
  .small-block-grid-4 > li {
    width: 25%;
    list-style: none; }
    .small-block-grid-4 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-4 > li:nth-of-type(4n+1) {
      clear: both; }
  .small-block-grid-5 > li {
    width: 20%;
    list-style: none; }
    .small-block-grid-5 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-5 > li:nth-of-type(5n+1) {
      clear: both; }
  .small-block-grid-6 > li {
    width: 16.6666666667%;
    list-style: none; }
    .small-block-grid-6 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-6 > li:nth-of-type(6n+1) {
      clear: both; }
  .small-block-grid-7 > li {
    width: 14.2857142857%;
    list-style: none; }
    .small-block-grid-7 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-7 > li:nth-of-type(7n+1) {
      clear: both; }
  .small-block-grid-8 > li {
    width: 12.5%;
    list-style: none; }
    .small-block-grid-8 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-8 > li:nth-of-type(8n+1) {
      clear: both; }
  .small-block-grid-9 > li {
    width: 11.1111111111%;
    list-style: none; }
    .small-block-grid-9 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-9 > li:nth-of-type(9n+1) {
      clear: both; }
  .small-block-grid-10 > li {
    width: 10%;
    list-style: none; }
    .small-block-grid-10 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-10 > li:nth-of-type(10n+1) {
      clear: both; }
  .small-block-grid-11 > li {
    width: 9.0909090909%;
    list-style: none; }
    .small-block-grid-11 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-11 > li:nth-of-type(11n+1) {
      clear: both; }
  .small-block-grid-12 > li {
    width: 8.3333333333%;
    list-style: none; }
    .small-block-grid-12 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-12 > li:nth-of-type(12n+1) {
      clear: both; } }

@media only screen and (min-width:40.063em) {
  .medium-block-grid-1 > li {
    width: 100%;
    list-style: none; }
    .medium-block-grid-1 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-1 > li:nth-of-type(1n+1) {
      clear: both; }
  .medium-block-grid-2 > li {
    width: 50%;
    list-style: none; }
    .medium-block-grid-2 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-2 > li:nth-of-type(2n+1) {
      clear: both; }
  .medium-block-grid-3 > li {
    width: 33.3333333333%;
    list-style: none; }
    .medium-block-grid-3 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-3 > li:nth-of-type(3n+1) {
      clear: both; }
  .medium-block-grid-4 > li {
    width: 25%;
    list-style: none; }
    .medium-block-grid-4 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-4 > li:nth-of-type(4n+1) {
      clear: both; }
  .medium-block-grid-5 > li {
    width: 20%;
    list-style: none; }
    .medium-block-grid-5 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-5 > li:nth-of-type(5n+1) {
      clear: both; }
  .medium-block-grid-6 > li {
    width: 16.6666666667%;
    list-style: none; }
    .medium-block-grid-6 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-6 > li:nth-of-type(6n+1) {
      clear: both; }
  .medium-block-grid-7 > li {
    width: 14.2857142857%;
    list-style: none; }
    .medium-block-grid-7 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-7 > li:nth-of-type(7n+1) {
      clear: both; }
  .medium-block-grid-8 > li {
    width: 12.5%;
    list-style: none; }
    .medium-block-grid-8 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-8 > li:nth-of-type(8n+1) {
      clear: both; }
  .medium-block-grid-9 > li {
    width: 11.1111111111%;
    list-style: none; }
    .medium-block-grid-9 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-9 > li:nth-of-type(9n+1) {
      clear: both; }
  .medium-block-grid-10 > li {
    width: 10%;
    list-style: none; }
    .medium-block-grid-10 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-10 > li:nth-of-type(10n+1) {
      clear: both; }
  .medium-block-grid-11 > li {
    width: 9.0909090909%;
    list-style: none; }
    .medium-block-grid-11 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-11 > li:nth-of-type(11n+1) {
      clear: both; }
  .medium-block-grid-12 > li {
    width: 8.3333333333%;
    list-style: none; }
    .medium-block-grid-12 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-12 > li:nth-of-type(12n+1) {
      clear: both; } }

@media only screen and (min-width:64.063em) {
  .large-block-grid-1 > li {
    width: 100%;
    list-style: none; }
    .large-block-grid-1 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-1 > li:nth-of-type(1n+1) {
      clear: both; }
  .large-block-grid-2 > li {
    width: 50%;
    list-style: none; }
    .large-block-grid-2 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-2 > li:nth-of-type(2n+1) {
      clear: both; }
  .large-block-grid-3 > li {
    width: 33.3333333333%;
    list-style: none; }
    .large-block-grid-3 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-3 > li:nth-of-type(3n+1) {
      clear: both; }
  .large-block-grid-4 > li {
    width: 25%;
    list-style: none; }
    .large-block-grid-4 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-4 > li:nth-of-type(4n+1) {
      clear: both; }
  .large-block-grid-5 > li {
    width: 20%;
    list-style: none; }
    .large-block-grid-5 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-5 > li:nth-of-type(5n+1) {
      clear: both; }
  .large-block-grid-6 > li {
    width: 16.6666666667%;
    list-style: none; }
    .large-block-grid-6 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-6 > li:nth-of-type(6n+1) {
      clear: both; }
  .large-block-grid-7 > li {
    width: 14.2857142857%;
    list-style: none; }
    .large-block-grid-7 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-7 > li:nth-of-type(7n+1) {
      clear: both; }
  .large-block-grid-8 > li {
    width: 12.5%;
    list-style: none; }
    .large-block-grid-8 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-8 > li:nth-of-type(8n+1) {
      clear: both; }
  .large-block-grid-9 > li {
    width: 11.1111111111%;
    list-style: none; }
    .large-block-grid-9 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-9 > li:nth-of-type(9n+1) {
      clear: both; }
  .large-block-grid-10 > li {
    width: 10%;
    list-style: none; }
    .large-block-grid-10 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-10 > li:nth-of-type(10n+1) {
      clear: both; }
  .large-block-grid-11 > li {
    width: 9.0909090909%;
    list-style: none; }
    .large-block-grid-11 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-11 > li:nth-of-type(11n+1) {
      clear: both; }
  .large-block-grid-12 > li {
    width: 8.3333333333%;
    list-style: none; }
    .large-block-grid-12 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-12 > li:nth-of-type(12n+1) {
      clear: both; } }

.breadcrumbs {
  display: block;
  padding: 0.5625rem 0.875rem 0.5625rem;
  overflow: hidden;
  margin-left: 0;
  list-style: none;
  border-style: solid;
  border-width: 1px;
  background-color: #f4f4f4;
  border-color: gainsboro;
  border-radius: 3px; }
  .breadcrumbs > * {
    margin: 0;
    float: left;
    font-size: 0.6875rem;
    line-height: 0.6875rem;
    text-transform: uppercase;
    color: #1f5c87; }
    .breadcrumbs > *:hover a, .breadcrumbs > *:focus a {
      text-decoration: underline; }
    .breadcrumbs > * a {
      color: #1f5c87; }
    .breadcrumbs > *.current {
      cursor: default;
      color: #333333; }
      .breadcrumbs > *.current a {
        cursor: default;
        color: #333333; }
      .breadcrumbs > *.current:hover, .breadcrumbs > *.current:hover a, .breadcrumbs > *.current:focus, .breadcrumbs > *.current:focus a {
        text-decoration: none; }
    .breadcrumbs > *.unavailable {
      color: #999999; }
      .breadcrumbs > *.unavailable a {
        color: #999999; }
      .breadcrumbs > *.unavailable:hover, .breadcrumbs > *.unavailable:hover a, .breadcrumbs > *.unavailable:focus, .breadcrumbs > *.unavailable a:focus {
        text-decoration: none;
        color: #999999;
        cursor: false; }
    .breadcrumbs > *:before {
      content: "/";
      color: #AAAAAA;
      margin: 0 0.75rem;
      position: relative;
      top: 1px; }
    .breadcrumbs > *:first-child:before {
      content: " ";
      margin: 0; }

/* Accessibility - hides the forward slash */
[aria-label="breadcrumbs"] [aria-hidden="true"]:after {
  content: "/"; }

button, .button {
  border-style: solid;
  border-width: 0;
  cursor: pointer;
  font-family: arial, sans-serif;
  font-weight: 400;
  line-height: normal;
  margin: 0 0 1.25rem;
  position: relative;
  text-decoration: none;
  text-align: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  border-radius: 0;
  display: inline-block;
  padding-top: 1rem;
  padding-right: 2rem;
  padding-bottom: 1.0625rem;
  padding-left: 2rem;
  font-size: 1rem;
  background-color: #1f5c87;
  border-color: #cc8100;
  color: #FFFFFF;
  transition: background-color 300ms ease-out; }
  button:hover, button:focus, .button:hover, .button:focus {
    background-color: #cc8100; }
  button:hover, button:focus, .button:hover, .button:focus {
    color: #FFFFFF; }
  button.secondary, .button.secondary {
    background-color: #E7E7E7;
    border-color: #b9b9b9;
    color: #333333; }
    button.secondary:hover, button.secondary:focus, .button.secondary:hover, .button.secondary:focus {
      background-color: #b9b9b9; }
    button.secondary:hover, button.secondary:focus, .button.secondary:hover, .button.secondary:focus {
      color: #333333; }
  button.success, .button.success {
    background-color: #43AC6A;
    border-color: #368a55;
    color: #FFFFFF; }
    button.success:hover, button.success:focus, .button.success:hover, .button.success:focus {
      background-color: #368a55; }
    button.success:hover, button.success:focus, .button.success:hover, .button.success:focus {
      color: #FFFFFF; }
  button.alert, .button.alert {
    background-color: #f04124;
    border-color: #cf2a0e;
    color: #FFFFFF; }
    button.alert:hover, button.alert:focus, .button.alert:hover, .button.alert:focus {
      background-color: #cf2a0e; }
    button.alert:hover, button.alert:focus, .button.alert:hover, .button.alert:focus {
      color: #FFFFFF; }
  button.warning, .button.warning {
    background-color: #f08a24;
    border-color: #cf6e0e;
    color: #FFFFFF; }
    button.warning:hover, button.warning:focus, .button.warning:hover, .button.warning:focus {
      background-color: #cf6e0e; }
    button.warning:hover, button.warning:focus, .button.warning:hover, .button.warning:focus {
      color: #FFFFFF; }
  button.info, .button.info {
    background-color: #a0d3e8;
    border-color: #61b6d9;
    color: #333333; }
    button.info:hover, button.info:focus, .button.info:hover, .button.info:focus {
      background-color: #61b6d9; }
    button.info:hover, button.info:focus, .button.info:hover, .button.info:focus {
      color: #FFFFFF; }
  button.large, .button.large {
    padding-top: 1.125rem;
    padding-right: 2.25rem;
    padding-bottom: 1.1875rem;
    padding-left: 2.25rem;
    font-size: 1.25rem; }
  button.small, .button.small {
    padding-top: 0.875rem;
    padding-right: 1.75rem;
    padding-bottom: 0.9375rem;
    padding-left: 1.75rem;
    font-size: 0.8125rem; }
  button.tiny, .button.tiny {
    padding-top: 0.625rem;
    padding-right: 1.25rem;
    padding-bottom: 0.6875rem;
    padding-left: 1.25rem;
    font-size: 0.6875rem; }
  button.expand, .button.expand {
    padding-right: 0;
    padding-left: 0;
    width: 100%; }
  button.left-align, .button.left-align {
    text-align: left;
    text-indent: 0.75rem; }
  button.right-align, .button.right-align {
    text-align: right;
    padding-right: 0.75rem; }
  button.radius, .button.radius {
    border-radius: 3px; }
  button.round, .button.round {
    border-radius: 1000px; }
  button.disabled, button[disabled], .button.disabled, .button[disabled] {
    background-color: #1f5c87;
    border-color: #cc8100;
    color: #FFFFFF;
    cursor: default;
    opacity: 0.7;
    box-shadow: none; }
    button.disabled:hover, button.disabled:focus, button[disabled]:hover, button[disabled]:focus, .button.disabled:hover, .button.disabled:focus, .button[disabled]:hover, .button[disabled]:focus {
      background-color: #cc8100; }
    button.disabled:hover, button.disabled:focus, button[disabled]:hover, button[disabled]:focus, .button.disabled:hover, .button.disabled:focus, .button[disabled]:hover, .button[disabled]:focus {
      color: #FFFFFF; }
    button.disabled:hover, button.disabled:focus, button[disabled]:hover, button[disabled]:focus, .button.disabled:hover, .button.disabled:focus, .button[disabled]:hover, .button[disabled]:focus {
      background-color: #1f5c87; }
    button.disabled.secondary, button[disabled].secondary, .button.disabled.secondary, .button[disabled].secondary {
      background-color: #E7E7E7;
      border-color: #b9b9b9;
      color: #333333;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.secondary:hover, button.disabled.secondary:focus, button[disabled].secondary:hover, button[disabled].secondary:focus, .button.disabled.secondary:hover, .button.disabled.secondary:focus, .button[disabled].secondary:hover, .button[disabled].secondary:focus {
        background-color: #b9b9b9; }
      button.disabled.secondary:hover, button.disabled.secondary:focus, button[disabled].secondary:hover, button[disabled].secondary:focus, .button.disabled.secondary:hover, .button.disabled.secondary:focus, .button[disabled].secondary:hover, .button[disabled].secondary:focus {
        color: #333333; }
      button.disabled.secondary:hover, button.disabled.secondary:focus, button[disabled].secondary:hover, button[disabled].secondary:focus, .button.disabled.secondary:hover, .button.disabled.secondary:focus, .button[disabled].secondary:hover, .button[disabled].secondary:focus {
        background-color: #E7E7E7; }
    button.disabled.success, button[disabled].success, .button.disabled.success, .button[disabled].success {
      background-color: #43AC6A;
      border-color: #368a55;
      color: #FFFFFF;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.success:hover, button.disabled.success:focus, button[disabled].success:hover, button[disabled].success:focus, .button.disabled.success:hover, .button.disabled.success:focus, .button[disabled].success:hover, .button[disabled].success:focus {
        background-color: #368a55; }
      button.disabled.success:hover, button.disabled.success:focus, button[disabled].success:hover, button[disabled].success:focus, .button.disabled.success:hover, .button.disabled.success:focus, .button[disabled].success:hover, .button[disabled].success:focus {
        color: #FFFFFF; }
      button.disabled.success:hover, button.disabled.success:focus, button[disabled].success:hover, button[disabled].success:focus, .button.disabled.success:hover, .button.disabled.success:focus, .button[disabled].success:hover, .button[disabled].success:focus {
        background-color: #43AC6A; }
    button.disabled.alert, button[disabled].alert, .button.disabled.alert, .button[disabled].alert {
      background-color: #f04124;
      border-color: #cf2a0e;
      color: #FFFFFF;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.alert:hover, button.disabled.alert:focus, button[disabled].alert:hover, button[disabled].alert:focus, .button.disabled.alert:hover, .button.disabled.alert:focus, .button[disabled].alert:hover, .button[disabled].alert:focus {
        background-color: #cf2a0e; }
      button.disabled.alert:hover, button.disabled.alert:focus, button[disabled].alert:hover, button[disabled].alert:focus, .button.disabled.alert:hover, .button.disabled.alert:focus, .button[disabled].alert:hover, .button[disabled].alert:focus {
        color: #FFFFFF; }
      button.disabled.alert:hover, button.disabled.alert:focus, button[disabled].alert:hover, button[disabled].alert:focus, .button.disabled.alert:hover, .button.disabled.alert:focus, .button[disabled].alert:hover, .button[disabled].alert:focus {
        background-color: #f04124; }
    button.disabled.warning, button[disabled].warning, .button.disabled.warning, .button[disabled].warning {
      background-color: #f08a24;
      border-color: #cf6e0e;
      color: #FFFFFF;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.warning:hover, button.disabled.warning:focus, button[disabled].warning:hover, button[disabled].warning:focus, .button.disabled.warning:hover, .button.disabled.warning:focus, .button[disabled].warning:hover, .button[disabled].warning:focus {
        background-color: #cf6e0e; }
      button.disabled.warning:hover, button.disabled.warning:focus, button[disabled].warning:hover, button[disabled].warning:focus, .button.disabled.warning:hover, .button.disabled.warning:focus, .button[disabled].warning:hover, .button[disabled].warning:focus {
        color: #FFFFFF; }
      button.disabled.warning:hover, button.disabled.warning:focus, button[disabled].warning:hover, button[disabled].warning:focus, .button.disabled.warning:hover, .button.disabled.warning:focus, .button[disabled].warning:hover, .button[disabled].warning:focus {
        background-color: #f08a24; }
    button.disabled.info, button[disabled].info, .button.disabled.info, .button[disabled].info {
      background-color: #a0d3e8;
      border-color: #61b6d9;
      color: #333333;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.info:hover, button.disabled.info:focus, button[disabled].info:hover, button[disabled].info:focus, .button.disabled.info:hover, .button.disabled.info:focus, .button[disabled].info:hover, .button[disabled].info:focus {
        background-color: #61b6d9; }
      button.disabled.info:hover, button.disabled.info:focus, button[disabled].info:hover, button[disabled].info:focus, .button.disabled.info:hover, .button.disabled.info:focus, .button[disabled].info:hover, .button[disabled].info:focus {
        color: #FFFFFF; }
      button.disabled.info:hover, button.disabled.info:focus, button[disabled].info:hover, button[disabled].info:focus, .button.disabled.info:hover, .button.disabled.info:focus, .button[disabled].info:hover, .button[disabled].info:focus {
        background-color: #a0d3e8; }

button::-moz-focus-inner {
  border: 0;
  padding: 0; }

@media only screen and (min-width:40.063em) {
  button, .button {
    display: inline-block; } }

.button-group {
  list-style: none;
  margin: 0;
  left: 0; }
  .button-group:before, .button-group:after {
    content: " ";
    display: table; }
  .button-group:after {
    clear: both; }
  .button-group.even-2 li {
    margin: 0 -2px;
    display: inline-block;
    width: 50%; }
    .button-group.even-2 li > button, .button-group.even-2 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-2 li:first-child button, .button-group.even-2 li:first-child .button {
      border-left: 0; }
    .button-group.even-2 li button, .button-group.even-2 li .button {
      width: 100%; }
  .button-group.even-3 li {
    margin: 0 -2px;
    display: inline-block;
    width: 33.3333333333%; }
    .button-group.even-3 li > button, .button-group.even-3 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-3 li:first-child button, .button-group.even-3 li:first-child .button {
      border-left: 0; }
    .button-group.even-3 li button, .button-group.even-3 li .button {
      width: 100%; }
  .button-group.even-4 li {
    margin: 0 -2px;
    display: inline-block;
    width: 25%; }
    .button-group.even-4 li > button, .button-group.even-4 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-4 li:first-child button, .button-group.even-4 li:first-child .button {
      border-left: 0; }
    .button-group.even-4 li button, .button-group.even-4 li .button {
      width: 100%; }
  .button-group.even-5 li {
    margin: 0 -2px;
    display: inline-block;
    width: 20%; }
    .button-group.even-5 li > button, .button-group.even-5 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-5 li:first-child button, .button-group.even-5 li:first-child .button {
      border-left: 0; }
    .button-group.even-5 li button, .button-group.even-5 li .button {
      width: 100%; }
  .button-group.even-6 li {
    margin: 0 -2px;
    display: inline-block;
    width: 16.6666666667%; }
    .button-group.even-6 li > button, .button-group.even-6 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-6 li:first-child button, .button-group.even-6 li:first-child .button {
      border-left: 0; }
    .button-group.even-6 li button, .button-group.even-6 li .button {
      width: 100%; }
  .button-group.even-7 li {
    margin: 0 -2px;
    display: inline-block;
    width: 14.2857142857%; }
    .button-group.even-7 li > button, .button-group.even-7 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-7 li:first-child button, .button-group.even-7 li:first-child .button {
      border-left: 0; }
    .button-group.even-7 li button, .button-group.even-7 li .button {
      width: 100%; }
  .button-group.even-8 li {
    margin: 0 -2px;
    display: inline-block;
    width: 12.5%; }
    .button-group.even-8 li > button, .button-group.even-8 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-8 li:first-child button, .button-group.even-8 li:first-child .button {
      border-left: 0; }
    .button-group.even-8 li button, .button-group.even-8 li .button {
      width: 100%; }
  .button-group > li {
    margin: 0 -2px;
    display: inline-block; }
    .button-group > li > button, .button-group > li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group > li:first-child button, .button-group > li:first-child .button {
      border-left: 0; }
  .button-group.stack > li {
    margin: 0 -2px;
    display: inline-block;
    display: block;
    margin: 0;
    float: none; }
    .button-group.stack > li > button, .button-group.stack > li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.stack > li:first-child button, .button-group.stack > li:first-child .button {
      border-left: 0; }
    .button-group.stack > li > button, .button-group.stack > li .button {
      border-top: 1px solid;
      border-color: rgba(255, 255, 255, 0.5);
      border-left-width: 0;
      margin: 0;
      display: block; }
    .button-group.stack > li > button {
      width: 100%; }
    .button-group.stack > li:first-child button, .button-group.stack > li:first-child .button {
      border-top: 0; }
  .button-group.stack-for-small > li {
    margin: 0 -2px;
    display: inline-block; }
    .button-group.stack-for-small > li > button, .button-group.stack-for-small > li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.stack-for-small > li:first-child button, .button-group.stack-for-small > li:first-child .button {
      border-left: 0; }
    @media only screen and (max-width: 40em) {
      .button-group.stack-for-small > li {
        margin: 0 -2px;
        display: inline-block;
        display: block;
        margin: 0; }
        .button-group.stack-for-small > li > button, .button-group.stack-for-small > li .button {
          border-left: 1px solid;
          border-color: rgba(255, 255, 255, 0.5); }
        .button-group.stack-for-small > li:first-child button, .button-group.stack-for-small > li:first-child .button {
          border-left: 0; }
        .button-group.stack-for-small > li > button, .button-group.stack-for-small > li .button {
          border-top: 1px solid;
          border-color: rgba(255, 255, 255, 0.5);
          border-left-width: 0;
          margin: 0;
          display: block; }
        .button-group.stack-for-small > li > button {
          width: 100%; }
        .button-group.stack-for-small > li:first-child button, .button-group.stack-for-small > li:first-child .button {
          border-top: 0; } }
  .button-group.radius > * {
    margin: 0 -2px;
    display: inline-block; }
    .button-group.radius > * > button, .button-group.radius > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.radius > *:first-child button, .button-group.radius > *:first-child .button {
      border-left: 0; }
    .button-group.radius > *, .button-group.radius > * > a, .button-group.radius > * > button, .button-group.radius > * > .button {
      border-radius: 0; }
    .button-group.radius > *:first-child, .button-group.radius > *:first-child > a, .button-group.radius > *:first-child > button, .button-group.radius > *:first-child > .button {
      -webkit-border-bottom-left-radius: 3px;
      -webkit-border-top-left-radius: 3px;
      border-bottom-left-radius: 3px;
      border-top-left-radius: 3px; }
    .button-group.radius > *:last-child, .button-group.radius > *:last-child > a, .button-group.radius > *:last-child > button, .button-group.radius > *:last-child > .button {
      -webkit-border-bottom-right-radius: 3px;
      -webkit-border-top-right-radius: 3px;
      border-bottom-right-radius: 3px;
      border-top-right-radius: 3px; }
  .button-group.radius.stack > * {
    margin: 0 -2px;
    display: inline-block;
    display: block;
    margin: 0; }
    .button-group.radius.stack > * > button, .button-group.radius.stack > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.radius.stack > *:first-child button, .button-group.radius.stack > *:first-child .button {
      border-left: 0; }
    .button-group.radius.stack > * > button, .button-group.radius.stack > * .button {
      border-top: 1px solid;
      border-color: rgba(255, 255, 255, 0.5);
      border-left-width: 0;
      margin: 0;
      display: block; }
    .button-group.radius.stack > * > button {
      width: 100%; }
    .button-group.radius.stack > *:first-child button, .button-group.radius.stack > *:first-child .button {
      border-top: 0; }
    .button-group.radius.stack > *, .button-group.radius.stack > * > a, .button-group.radius.stack > * > button, .button-group.radius.stack > * > .button {
      border-radius: 0; }
    .button-group.radius.stack > *:first-child, .button-group.radius.stack > *:first-child > a, .button-group.radius.stack > *:first-child > button, .button-group.radius.stack > *:first-child > .button {
      -webkit-top-left-radius: 3px;
      -webkit-top-right-radius: 3px;
      border-top-left-radius: 3px;
      border-top-right-radius: 3px; }
    .button-group.radius.stack > *:last-child, .button-group.radius.stack > *:last-child > a, .button-group.radius.stack > *:last-child > button, .button-group.radius.stack > *:last-child > .button {
      -webkit-bottom-left-radius: 3px;
      -webkit-bottom-right-radius: 3px;
      border-bottom-left-radius: 3px;
      border-bottom-right-radius: 3px; }
  @media only screen and (min-width:40.063em) {
    .button-group.radius.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block; }
      .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.radius.stack-for-small > *:first-child button, .button-group.radius.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.radius.stack-for-small > *, .button-group.radius.stack-for-small > * > a, .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.radius.stack-for-small > *:first-child, .button-group.radius.stack-for-small > *:first-child > a, .button-group.radius.stack-for-small > *:first-child > button, .button-group.radius.stack-for-small > *:first-child > .button {
        -webkit-border-bottom-left-radius: 3px;
        -webkit-border-top-left-radius: 3px;
        border-bottom-left-radius: 3px;
        border-top-left-radius: 3px; }
      .button-group.radius.stack-for-small > *:last-child, .button-group.radius.stack-for-small > *:last-child > a, .button-group.radius.stack-for-small > *:last-child > button, .button-group.radius.stack-for-small > *:last-child > .button {
        -webkit-border-bottom-right-radius: 3px;
        -webkit-border-top-right-radius: 3px;
        border-bottom-right-radius: 3px;
        border-top-right-radius: 3px; } }
  @media only screen and (max-width: 40em) {
    .button-group.radius.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block;
      display: block;
      margin: 0; }
      .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.radius.stack-for-small > *:first-child button, .button-group.radius.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * .button {
        border-top: 1px solid;
        border-color: rgba(255, 255, 255, 0.5);
        border-left-width: 0;
        margin: 0;
        display: block; }
      .button-group.radius.stack-for-small > * > button {
        width: 100%; }
      .button-group.radius.stack-for-small > *:first-child button, .button-group.radius.stack-for-small > *:first-child .button {
        border-top: 0; }
      .button-group.radius.stack-for-small > *, .button-group.radius.stack-for-small > * > a, .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.radius.stack-for-small > *:first-child, .button-group.radius.stack-for-small > *:first-child > a, .button-group.radius.stack-for-small > *:first-child > button, .button-group.radius.stack-for-small > *:first-child > .button {
        -webkit-top-left-radius: 3px;
        -webkit-top-right-radius: 3px;
        border-top-left-radius: 3px;
        border-top-right-radius: 3px; }
      .button-group.radius.stack-for-small > *:last-child, .button-group.radius.stack-for-small > *:last-child > a, .button-group.radius.stack-for-small > *:last-child > button, .button-group.radius.stack-for-small > *:last-child > .button {
        -webkit-bottom-left-radius: 3px;
        -webkit-bottom-right-radius: 3px;
        border-bottom-left-radius: 3px;
        border-bottom-right-radius: 3px; } }
  .button-group.round > * {
    margin: 0 -2px;
    display: inline-block; }
    .button-group.round > * > button, .button-group.round > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.round > *:first-child button, .button-group.round > *:first-child .button {
      border-left: 0; }
    .button-group.round > *, .button-group.round > * > a, .button-group.round > * > button, .button-group.round > * > .button {
      border-radius: 0; }
    .button-group.round > *:first-child, .button-group.round > *:first-child > a, .button-group.round > *:first-child > button, .button-group.round > *:first-child > .button {
      -webkit-border-bottom-left-radius: 1000px;
      -webkit-border-top-left-radius: 1000px;
      border-bottom-left-radius: 1000px;
      border-top-left-radius: 1000px; }
    .button-group.round > *:last-child, .button-group.round > *:last-child > a, .button-group.round > *:last-child > button, .button-group.round > *:last-child > .button {
      -webkit-border-bottom-right-radius: 1000px;
      -webkit-border-top-right-radius: 1000px;
      border-bottom-right-radius: 1000px;
      border-top-right-radius: 1000px; }
  .button-group.round.stack > * {
    margin: 0 -2px;
    display: inline-block;
    display: block;
    margin: 0; }
    .button-group.round.stack > * > button, .button-group.round.stack > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.round.stack > *:first-child button, .button-group.round.stack > *:first-child .button {
      border-left: 0; }
    .button-group.round.stack > * > button, .button-group.round.stack > * .button {
      border-top: 1px solid;
      border-color: rgba(255, 255, 255, 0.5);
      border-left-width: 0;
      margin: 0;
      display: block; }
    .button-group.round.stack > * > button {
      width: 100%; }
    .button-group.round.stack > *:first-child button, .button-group.round.stack > *:first-child .button {
      border-top: 0; }
    .button-group.round.stack > *, .button-group.round.stack > * > a, .button-group.round.stack > * > button, .button-group.round.stack > * > .button {
      border-radius: 0; }
    .button-group.round.stack > *:first-child, .button-group.round.stack > *:first-child > a, .button-group.round.stack > *:first-child > button, .button-group.round.stack > *:first-child > .button {
      -webkit-top-left-radius: 1rem;
      -webkit-top-right-radius: 1rem;
      border-top-left-radius: 1rem;
      border-top-right-radius: 1rem; }
    .button-group.round.stack > *:last-child, .button-group.round.stack > *:last-child > a, .button-group.round.stack > *:last-child > button, .button-group.round.stack > *:last-child > .button {
      -webkit-bottom-left-radius: 1rem;
      -webkit-bottom-right-radius: 1rem;
      border-bottom-left-radius: 1rem;
      border-bottom-right-radius: 1rem; }
  @media only screen and (min-width:40.063em) {
    .button-group.round.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block; }
      .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.round.stack-for-small > *:first-child button, .button-group.round.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.round.stack-for-small > *, .button-group.round.stack-for-small > * > a, .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.round.stack-for-small > *:first-child, .button-group.round.stack-for-small > *:first-child > a, .button-group.round.stack-for-small > *:first-child > button, .button-group.round.stack-for-small > *:first-child > .button {
        -webkit-border-bottom-left-radius: 1000px;
        -webkit-border-top-left-radius: 1000px;
        border-bottom-left-radius: 1000px;
        border-top-left-radius: 1000px; }
      .button-group.round.stack-for-small > *:last-child, .button-group.round.stack-for-small > *:last-child > a, .button-group.round.stack-for-small > *:last-child > button, .button-group.round.stack-for-small > *:last-child > .button {
        -webkit-border-bottom-right-radius: 1000px;
        -webkit-border-top-right-radius: 1000px;
        border-bottom-right-radius: 1000px;
        border-top-right-radius: 1000px; } }
  @media only screen and (max-width: 40em) {
    .button-group.round.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block;
      display: block;
      margin: 0; }
      .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.round.stack-for-small > *:first-child button, .button-group.round.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * .button {
        border-top: 1px solid;
        border-color: rgba(255, 255, 255, 0.5);
        border-left-width: 0;
        margin: 0;
        display: block; }
      .button-group.round.stack-for-small > * > button {
        width: 100%; }
      .button-group.round.stack-for-small > *:first-child button, .button-group.round.stack-for-small > *:first-child .button {
        border-top: 0; }
      .button-group.round.stack-for-small > *, .button-group.round.stack-for-small > * > a, .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.round.stack-for-small > *:first-child, .button-group.round.stack-for-small > *:first-child > a, .button-group.round.stack-for-small > *:first-child > button, .button-group.round.stack-for-small > *:first-child > .button {
        -webkit-top-left-radius: 1rem;
        -webkit-top-right-radius: 1rem;
        border-top-left-radius: 1rem;
        border-top-right-radius: 1rem; }
      .button-group.round.stack-for-small > *:last-child, .button-group.round.stack-for-small > *:last-child > a, .button-group.round.stack-for-small > *:last-child > button, .button-group.round.stack-for-small > *:last-child > .button {
        -webkit-bottom-left-radius: 1rem;
        -webkit-bottom-right-radius: 1rem;
        border-bottom-left-radius: 1rem;
        border-bottom-right-radius: 1rem; } }

.button-bar:before, .button-bar:after {
  content: " ";
  display: table; }
.button-bar:after {
  clear: both; }
.button-bar .button-group {
  float: left;
  margin-right: 0.625rem; }
  .button-bar .button-group div {
    overflow: hidden; }

/* Clearing Styles */
.clearing-thumbs, [data-clearing] {
  margin-bottom: 0;
  margin-left: 0;
  list-style: none; }
  .clearing-thumbs:before, .clearing-thumbs:after, [data-clearing]:before, [data-clearing]:after {
    content: " ";
    display: table; }
  .clearing-thumbs:after, [data-clearing]:after {
    clear: both; }
  .clearing-thumbs li, [data-clearing] li {
    float: left;
    margin-right: 10px; }
  .clearing-thumbs[class*="block-grid-"] li, [data-clearing][class*="block-grid-"] li {
    margin-right: 0; }

.clearing-blackout {
  background: #333333;
  position: fixed;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  z-index: 998; }
  .clearing-blackout .clearing-close {
    display: block; }

.clearing-container {
  position: relative;
  z-index: 998;
  height: 100%;
  overflow: hidden;
  margin: 0; }

.clearing-touch-label {
  position: absolute;
  top: 50%;
  left: 50%;
  color: #AAAAAA;
  font-size: 0.6em; }

.visible-img {
  height: 95%;
  position: relative; }
  .visible-img img {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translateY(-50%) translateX(-50%);
    -webkit-transform: translateY(-50%) translateX(-50%);
    -ms-transform: translateY(-50%) translateX(-50%);
    max-height: 100%;
    max-width: 100%; }

.clearing-caption {
  color: #565656;
  font-size: 0.875em;
  line-height: 1.3;
  margin-bottom: 0;
  text-align: center;
  bottom: 0;
  background: #333333;
  width: 100%;
  padding: 10px 30px 20px;
  position: absolute;
  left: 0; }

.clearing-close {
  z-index: 999;
  padding-left: 20px;
  padding-top: 10px;
  font-size: 30px;
  line-height: 1;
  color: #565656;
  display: none; }
  .clearing-close:hover, .clearing-close:focus {
    color: #565656; }

.clearing-assembled .clearing-container {
  height: 100%; }
  .clearing-assembled .clearing-container .carousel > ul {
    display: none; }

.clearing-feature li {
  display: none; }
  .clearing-feature li.clearing-featured-img {
    display: block; }

@media only screen and (min-width:40.063em) {
  .clearing-main-prev, .clearing-main-next {
    position: absolute;
    height: 100%;
    width: 40px;
    top: 0; }
    .clearing-main-prev > span, .clearing-main-next > span {
      position: absolute;
      top: 50%;
      display: block;
      width: 0;
      height: 0;
      border: solid 12px; }
      .clearing-main-prev > span:hover, .clearing-main-next > span:hover {
        opacity: 0.8; }
  .clearing-main-prev {
    left: 0; }
    .clearing-main-prev > span {
      left: 5px;
      border-color: transparent;
      border-right-color: #565656; }
  .clearing-main-next {
    right: 0; }
    .clearing-main-next > span {
      border-color: transparent;
      border-left-color: #565656; }
  .clearing-main-prev.disabled, .clearing-main-next.disabled {
    opacity: 0.3; }
  .clearing-assembled .clearing-container .carousel {
    background: rgba(51, 51, 51, 0.8);
    height: 120px;
    margin-top: 10px;
    text-align: center; }
    .clearing-assembled .clearing-container .carousel > ul {
      display: inline-block;
      z-index: 999;
      height: 100%;
      position: relative;
      float: none; }
      .clearing-assembled .clearing-container .carousel > ul li {
        display: block;
        width: 120px;
        min-height: inherit;
        float: left;
        overflow: hidden;
        margin-right: 0;
        padding: 0;
        position: relative;
        cursor: pointer;
        opacity: 0.4;
        clear: none; }
        .clearing-assembled .clearing-container .carousel > ul li.fix-height img {
          height: 100%;
          max-width: none; }
        .clearing-assembled .clearing-container .carousel > ul li a.th {
          border: none;
          box-shadow: none;
          display: block; }
        .clearing-assembled .clearing-container .carousel > ul li img {
          cursor: pointer !important;
          width: 100% !important; }
        .clearing-assembled .clearing-container .carousel > ul li.visible {
          opacity: 1; }
        .clearing-assembled .clearing-container .carousel > ul li:hover {
          opacity: 0.8; }
  .clearing-assembled .clearing-container .visible-img {
    background: #333333;
    overflow: hidden;
    height: 85%; }
  .clearing-close {
    position: absolute;
    top: 10px;
    right: 20px;
    padding-left: 0;
    padding-top: 0; } }

/* Foundation Dropdowns */
.f-dropdown {
  position: absolute;
  left: -9999px;
  list-style: none;
  margin-left: 0;
  outline: none;
  width: 100%;
  max-height: none;
  height: auto;
  background: #FFFFFF;
  border: solid 1px #cccccc;
  font-size: 0.875rem;
  z-index: 89;
  margin-top: 2px;
  max-width: 200px; }
  .f-dropdown > *:first-child {
    margin-top: 0; }
  .f-dropdown > *:last-child {
    margin-bottom: 0; }
  .f-dropdown:before {
    content: "";
    display: block;
    width: 0;
    height: 0;
    border: inset 6px;
    border-color: transparent transparent #FFFFFF transparent;
    border-bottom-style: solid;
    position: absolute;
    top: -12px;
    left: 10px;
    z-index: 89; }
  .f-dropdown:after {
    content: "";
    display: block;
    width: 0;
    height: 0;
    border: inset 7px;
    border-color: transparent transparent #cccccc transparent;
    border-bottom-style: solid;
    position: absolute;
    top: -14px;
    left: 9px;
    z-index: 88; }
  .f-dropdown.right:before {
    left: auto;
    right: 10px; }
  .f-dropdown.right:after {
    left: auto;
    right: 9px; }
  .f-dropdown.drop-right {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    width: 100%;
    max-height: none;
    height: auto;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    margin-top: 0;
    margin-left: 2px;
    max-width: 200px; }
    .f-dropdown.drop-right > *:first-child {
      margin-top: 0; }
    .f-dropdown.drop-right > *:last-child {
      margin-bottom: 0; }
    .f-dropdown.drop-right:before {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 6px;
      border-color: transparent #FFFFFF transparent transparent;
      border-right-style: solid;
      position: absolute;
      top: 10px;
      left: -12px;
      z-index: 89; }
    .f-dropdown.drop-right:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 7px;
      border-color: transparent #cccccc transparent transparent;
      border-right-style: solid;
      position: absolute;
      top: 9px;
      left: -14px;
      z-index: 88; }
  .f-dropdown.drop-left {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    width: 100%;
    max-height: none;
    height: auto;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    margin-top: 0;
    margin-left: -2px;
    max-width: 200px; }
    .f-dropdown.drop-left > *:first-child {
      margin-top: 0; }
    .f-dropdown.drop-left > *:last-child {
      margin-bottom: 0; }
    .f-dropdown.drop-left:before {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 6px;
      border-color: transparent transparent transparent #FFFFFF;
      border-left-style: solid;
      position: absolute;
      top: 10px;
      right: -12px;
      left: auto;
      z-index: 89; }
    .f-dropdown.drop-left:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 7px;
      border-color: transparent transparent transparent #cccccc;
      border-left-style: solid;
      position: absolute;
      top: 9px;
      right: -14px;
      left: auto;
      z-index: 88; }
  .f-dropdown.drop-top {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    width: 100%;
    max-height: none;
    height: auto;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    margin-top: -2px;
    margin-left: 0;
    max-width: 200px; }
    .f-dropdown.drop-top > *:first-child {
      margin-top: 0; }
    .f-dropdown.drop-top > *:last-child {
      margin-bottom: 0; }
    .f-dropdown.drop-top:before {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 6px;
      border-color: #FFFFFF transparent transparent transparent;
      border-top-style: solid;
      position: absolute;
      top: auto;
      bottom: -12px;
      left: 10px;
      right: auto;
      z-index: 89; }
    .f-dropdown.drop-top:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 7px;
      border-color: #cccccc transparent transparent transparent;
      border-top-style: solid;
      position: absolute;
      top: auto;
      bottom: -14px;
      left: 9px;
      right: auto;
      z-index: 88; }
  .f-dropdown li {
    font-size: 0.875rem;
    cursor: pointer;
    line-height: 1.125rem;
    margin: 0; }
    .f-dropdown li:hover, .f-dropdown li:focus {
      background: #EEEEEE; }
    .f-dropdown li.radius {
      border-radius: 3px; }
    .f-dropdown li a {
      display: block;
      padding: 0.5rem;
      color: #555555; }
  .f-dropdown.content {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    padding: 1.25rem;
    width: 100%;
    height: auto;
    max-height: none;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    max-width: 200px; }
    .f-dropdown.content > *:first-child {
      margin-top: 0; }
    .f-dropdown.content > *:last-child {
      margin-bottom: 0; }
  .f-dropdown.tiny {
    max-width: 200px; }
  .f-dropdown.small {
    max-width: 300px; }
  .f-dropdown.medium {
    max-width: 500px; }
  .f-dropdown.large {
    max-width: 800px; }
  .f-dropdown.mega {
    width: 100% !important;
    max-width: 100% !important; }
    .f-dropdown.mega.open {
      left: 0 !important; }

.dropdown.button, button.dropdown {
  position: relative;
  outline: none;
  padding-right: 3.5625rem; }
  .dropdown.button::after, button.dropdown::after {
    position: absolute;
    content: "";
    width: 0;
    height: 0;
    display: block;
    border-style: solid;
    border-color: #FFFFFF transparent transparent transparent;
    top: 50%; }
  .dropdown.button::after, button.dropdown::after {
    border-width: 0.375rem;
    right: 1.40625rem;
    margin-top: -0.15625rem; }
  .dropdown.button::after, button.dropdown::after {
    border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.tiny, button.dropdown.tiny {
    padding-right: 2.625rem; }
    .dropdown.button.tiny:after, button.dropdown.tiny:after {
      border-width: 0.375rem;
      right: 1.125rem;
      margin-top: -0.125rem; }
    .dropdown.button.tiny::after, button.dropdown.tiny::after {
      border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.small, button.dropdown.small {
    padding-right: 3.0625rem; }
    .dropdown.button.small::after, button.dropdown.small::after {
      border-width: 0.4375rem;
      right: 1.3125rem;
      margin-top: -0.15625rem; }
    .dropdown.button.small::after, button.dropdown.small::after {
      border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.large, button.dropdown.large {
    padding-right: 3.625rem; }
    .dropdown.button.large::after, button.dropdown.large::after {
      border-width: 0.3125rem;
      right: 1.71875rem;
      margin-top: -0.15625rem; }
    .dropdown.button.large::after, button.dropdown.large::after {
      border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.secondary:after, button.dropdown.secondary:after {
    border-color: #333333 transparent transparent transparent; }

.flex-video {
  position: relative;
  padding-top: 1.5625rem;
  padding-bottom: 67.5%;
  height: 0;
  margin-bottom: 1rem;
  overflow: hidden; }
  .flex-video.widescreen {
    padding-bottom: 56.34%; }
  .flex-video.vimeo {
    padding-top: 0; }
  .flex-video iframe, .flex-video object, .flex-video embed, .flex-video video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%; }

/* Standard Forms */
form {
  margin: 0 0 1rem; }

/* Using forms within rows, we need to set some defaults */
form .row .row {
  margin: 0 -0.5rem; }
  form .row .row .column, form .row .row .columns {
    padding: 0 0.5rem; }
  form .row .row.collapse {
    margin: 0; }
    form .row .row.collapse .column, form .row .row.collapse .columns {
      padding: 0; }
    form .row .row.collapse input {
      -webkit-border-bottom-right-radius: 0;
      -webkit-border-top-right-radius: 0;
      border-bottom-right-radius: 0;
      border-top-right-radius: 0; }
form .row input.column, form .row input.columns, form .row textarea.column, form .row textarea.columns {
  padding-left: 0.5rem; }

/* Label Styles */
label {
  font-size: 0.875rem;
  color: #4d4d4d;
  cursor: pointer;
  display: block;
  font-weight: 400;
  line-height: 1.5;
  margin-bottom: 0;
  /* Styles for required inputs */ }
  label.right {
    float: none !important;
    text-align: right; }
  label.inline {
    margin: 0 0 1rem 0;
    padding: 0.5625rem 0; }
  label small {
    text-transform: capitalize;
    color: #676767; }

/* Attach elements to the beginning or end of an input */
.prefix, .postfix {
  display: block;
  position: relative;
  z-index: 2;
  text-align: center;
  width: 100%;
  padding-top: 0;
  padding-bottom: 0;
  border-style: solid;
  border-width: 1px;
  overflow: visible;
  font-size: 0.875rem;
  height: 2.3125rem;
  line-height: 2.3125rem; }

/* Adjust padding, alignment and radius if pre/post element is a button */
.postfix.button {
  padding-left: 0;
  padding-right: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
  border: none; }

.prefix.button {
  padding-left: 0;
  padding-right: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
  border: none; }

.prefix.button.radius {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }

.postfix.button.radius {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 3px;
  -webkit-border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }

.prefix.button.round {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 1000px;
  -webkit-border-top-left-radius: 1000px;
  border-bottom-left-radius: 1000px;
  border-top-left-radius: 1000px; }

.postfix.button.round {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 1000px;
  -webkit-border-top-right-radius: 1000px;
  border-bottom-right-radius: 1000px;
  border-top-right-radius: 1000px; }

/* Separate prefix and postfix styles when on span or label so buttons keep their own */
span.prefix, label.prefix {
  background: #f2f2f2;
  border-right: none;
  color: #333333;
  border-color: #cccccc; }

span.postfix, label.postfix {
  background: #f2f2f2;
  border-left: none;
  color: #333333;
  border-color: #cccccc; }

/* We use this to get basic styling on all basic form elements */
input[type="text"], input[type="password"], input[type="date"], input[type="datetime"], input[type="datetime-local"], input[type="month"], input[type="week"], input[type="email"], input[type="number"], input[type="search"], input[type="tel"], input[type="time"], input[type="url"], input[type="color"], textarea {
  -webkit-appearance: none;
  border-radius: 0;
  background-color: #FFFFFF;
  font-family: inherit;
  border-style: solid;
  border-width: 1px;
  border-color: #cccccc;
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  color: rgba(0, 0, 0, 0.75);
  display: block;
  font-size: 0.875rem;
  margin: 0 0 1rem 0;
  padding: 0.5rem;
  height: 2.3125rem;
  width: 100%;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  transition: all 0.15s linear; }
  input[type="text"]:focus, input[type="password"]:focus, input[type="date"]:focus, input[type="datetime"]:focus, input[type="datetime-local"]:focus, input[type="month"]:focus, input[type="week"]:focus, input[type="email"]:focus, input[type="number"]:focus, input[type="search"]:focus, input[type="tel"]:focus, input[type="time"]:focus, input[type="url"]:focus, input[type="color"]:focus, textarea:focus {
    background: #fafafa;
    border-color: #999999;
    outline: none; }
  input[type="text"]:disabled, input[type="password"]:disabled, input[type="date"]:disabled, input[type="datetime"]:disabled, input[type="datetime-local"]:disabled, input[type="month"]:disabled, input[type="week"]:disabled, input[type="email"]:disabled, input[type="number"]:disabled, input[type="search"]:disabled, input[type="tel"]:disabled, input[type="time"]:disabled, input[type="url"]:disabled, input[type="color"]:disabled, textarea:disabled {
    background-color: #DDDDDD;
    cursor: default; }
  input[type="text"][disabled], input[type="text"][readonly], fieldset[disabled] input[type="text"], input[type="password"][disabled], input[type="password"][readonly], fieldset[disabled] input[type="password"], input[type="date"][disabled], input[type="date"][readonly], fieldset[disabled] input[type="date"], input[type="datetime"][disabled], input[type="datetime"][readonly], fieldset[disabled] input[type="datetime"], input[type="datetime-local"][disabled], input[type="datetime-local"][readonly], fieldset[disabled] input[type="datetime-local"], input[type="month"][disabled], input[type="month"][readonly], fieldset[disabled] input[type="month"], input[type="week"][disabled], input[type="week"][readonly], fieldset[disabled] input[type="week"], input[type="email"][disabled], input[type="email"][readonly], fieldset[disabled] input[type="email"], input[type="number"][disabled], input[type="number"][readonly], fieldset[disabled] input[type="number"], input[type="search"][disabled], input[type="search"][readonly], fieldset[disabled] input[type="search"], input[type="tel"][disabled], input[type="tel"][readonly], fieldset[disabled] input[type="tel"], input[type="time"][disabled], input[type="time"][readonly], fieldset[disabled] input[type="time"], input[type="url"][disabled], input[type="url"][readonly], fieldset[disabled] input[type="url"], input[type="color"][disabled], input[type="color"][readonly], fieldset[disabled] input[type="color"], textarea[disabled], textarea[readonly], fieldset[disabled] textarea {
    background-color: #DDDDDD;
    cursor: default; }
  input[type="text"].radius, input[type="password"].radius, input[type="date"].radius, input[type="datetime"].radius, input[type="datetime-local"].radius, input[type="month"].radius, input[type="week"].radius, input[type="email"].radius, input[type="number"].radius, input[type="search"].radius, input[type="tel"].radius, input[type="time"].radius, input[type="url"].radius, input[type="color"].radius, textarea.radius {
    border-radius: 3px; }

form .row .prefix-radius.row.collapse input, form .row .prefix-radius.row.collapse textarea, form .row .prefix-radius.row.collapse select, form .row .prefix-radius.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 3px;
  -webkit-border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }
form .row .prefix-radius.row.collapse .prefix {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }
form .row .postfix-radius.row.collapse input, form .row .postfix-radius.row.collapse textarea, form .row .postfix-radius.row.collapse select, form .row .postfix-radius.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }
form .row .postfix-radius.row.collapse .postfix {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 3px;
  -webkit-border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }
form .row .prefix-round.row.collapse input, form .row .prefix-round.row.collapse textarea, form .row .prefix-round.row.collapse select, form .row .prefix-round.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 1000px;
  -webkit-border-top-right-radius: 1000px;
  border-bottom-right-radius: 1000px;
  border-top-right-radius: 1000px; }
form .row .prefix-round.row.collapse .prefix {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 1000px;
  -webkit-border-top-left-radius: 1000px;
  border-bottom-left-radius: 1000px;
  border-top-left-radius: 1000px; }
form .row .postfix-round.row.collapse input, form .row .postfix-round.row.collapse textarea, form .row .postfix-round.row.collapse select, form .row .postfix-round.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 1000px;
  -webkit-border-top-left-radius: 1000px;
  border-bottom-left-radius: 1000px;
  border-top-left-radius: 1000px; }
form .row .postfix-round.row.collapse .postfix {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 1000px;
  -webkit-border-top-right-radius: 1000px;
  border-bottom-right-radius: 1000px;
  border-top-right-radius: 1000px; }

input[type="submit"] {
  -webkit-appearance: none;
  border-radius: 0; }

/* Respect enforced amount of rows for textarea */
textarea[rows] {
  height: auto; }

/* Not allow resize out of parent */
textarea {
  max-width: 100%; }

/* Add height value for select elements to match text input height */
select {
  -webkit-appearance: none !important;
  border-radius: 0;
  background-color: #FAFAFA;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeD0iMTJweCIgeT0iMHB4IiB3aWR0aD0iMjRweCIgaGVpZ2h0PSIzcHgiIHZpZXdCb3g9IjAgMCA2IDMiIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDYgMyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+PHBvbHlnb24gcG9pbnRzPSI1Ljk5MiwwIDIuOTkyLDMgLTAuMDA4LDAgIi8+PC9zdmc+);
  background-position: 100% center;
  background-repeat: no-repeat;
  border-style: solid;
  border-width: 1px;
  border-color: #cccccc;
  padding: 0.5rem;
  font-size: 0.875rem;
  font-family: arial, sans-serif;
  color: rgba(0, 0, 0, 0.75);
  line-height: normal;
  border-radius: 0;
  height: 2.3125rem; }
  select::-ms-expand {
    display: none; }
  select.radius {
    border-radius: 3px; }
  select:hover {
    background-color: #f3f3f3;
    border-color: #999999; }
  select:disabled {
    background-color: #DDDDDD;
    cursor: default; }
  select[multiple] {
    height: auto; }

/* Adjust margin for form elements below */
input[type="file"], input[type="checkbox"], input[type="radio"], select {
  margin: 0 0 1rem 0; }

input[type="checkbox"] + label, input[type="radio"] + label {
  display: inline-block;
  margin-left: 0.5rem;
  margin-right: 1rem;
  margin-bottom: 0;
  vertical-align: baseline; }

/* Normalize file input width */
input[type="file"] {
  width: 100%; }

/* HTML5 Number spinners settings */
/* We add basic fieldset styling */
fieldset {
  border: 1px solid #DDDDDD;
  padding: 1.25rem;
  margin: 1.125rem 0; }
  fieldset legend {
    font-weight: bold;
    background: #FFFFFF;
    padding: 0 0.1875rem;
    margin: 0;
    margin-left: -0.1875rem; }

/* Error Handling */
[data-abide] .error small.error, [data-abide] .error span.error, [data-abide] span.error, [data-abide] small.error {
  display: block;
  padding: 0.375rem 0.5625rem 0.5625rem;
  margin-top: -1px;
  margin-bottom: 1rem;
  font-size: 0.75rem;
  font-weight: 400;
  font-style: italic;
  background: #f04124;
  color: #FFFFFF; }
[data-abide] span.error, [data-abide] small.error {
  display: none; }

span.error, small.error {
  display: block;
  padding: 0.375rem 0.5625rem 0.5625rem;
  margin-top: -1px;
  margin-bottom: 1rem;
  font-size: 0.75rem;
  font-weight: 400;
  font-style: italic;
  background: #f04124;
  color: #FFFFFF; }

.error input, .error textarea, .error select {
  margin-bottom: 0; }
.error input[type="checkbox"], .error input[type="radio"] {
  margin-bottom: 1rem; }
.error label, .error label.error {
  color: #f04124; }
.error small.error {
  display: block;
  padding: 0.375rem 0.5625rem 0.5625rem;
  margin-top: -1px;
  margin-bottom: 1rem;
  font-size: 0.75rem;
  font-weight: 400;
  font-style: italic;
  background: #f04124;
  color: #FFFFFF; }
.error > label > small {
  color: #676767;
  background: transparent;
  padding: 0;
  text-transform: capitalize;
  font-style: normal;
  font-size: 60%;
  margin: 0;
  display: inline; }
.error span.error-message {
  display: block; }

input.error, textarea.error, select.error {
  margin-bottom: 0; }

label.error {
  color: #f04124; }

.icon-bar {
  width: 100%;
  font-size: 0;
  display: inline-block;
  background: #333333; }
  .icon-bar > * {
    text-align: center;
    font-size: 1rem;
    width: 25%;
    margin: 0 auto;
    display: block;
    padding: 1.25rem;
    float: left; }
    .icon-bar > * i, .icon-bar > * img {
      display: block;
      margin: 0 auto; }
      .icon-bar > * i + label, .icon-bar > * img + label {
        margin-top: .0625rem; }
    .icon-bar > * i {
      font-size: 1.875rem;
      vertical-align: middle; }
    .icon-bar > * img {
      width: 1.875rem;
      height: 1.875rem; }
  .icon-bar.label-right > * i, .icon-bar.label-right > * img {
    margin: 0 .0625rem 0 0;
    display: inline-block; }
    .icon-bar.label-right > * i + label, .icon-bar.label-right > * img + label {
      margin-top: 0; }
  .icon-bar.label-right > * label {
    display: inline-block; }
  .icon-bar.vertical.label-right > * {
    text-align: left; }
  .icon-bar.vertical, .icon-bar.small-vertical {
    height: 100%;
    width: auto; }
    .icon-bar.vertical .item, .icon-bar.small-vertical .item {
      width: auto;
      margin: auto;
      float: none; }
  @media only screen and (min-width:40.063em) {
    .icon-bar.medium-vertical {
      height: 100%;
      width: auto; }
      .icon-bar.medium-vertical .item {
        width: auto;
        margin: auto;
        float: none; } }
  @media only screen and (min-width:64.063em) {
    .icon-bar.large-vertical {
      height: 100%;
      width: auto; }
      .icon-bar.large-vertical .item {
        width: auto;
        margin: auto;
        float: none; } }
  .icon-bar > * {
    font-size: 1rem;
    padding: 1.25rem; }
    .icon-bar > * i + label, .icon-bar > * img + label {
      margin-top: .0625rem; }
    .icon-bar > * i {
      font-size: 1.875rem; }
    .icon-bar > * img {
      width: 1.875rem;
      height: 1.875rem; }
  .icon-bar > * label {
    color: #FFFFFF; }
  .icon-bar > * i {
    color: #FFFFFF; }
  .icon-bar > a:hover {
    background: #1f5c87; }
    .icon-bar > a:hover label {
      color: #FFFFFF; }
    .icon-bar > a:hover i {
      color: #FFFFFF; }
  .icon-bar > a.active {
    background: #1f5c87; }
    .icon-bar > a.active label {
      color: #FFFFFF; }
    .icon-bar > a.active i {
      color: #FFFFFF; }
  .icon-bar .item.disabled {
    opacity: 0.7;
    cursor: false;
    pointer-events: none; }
    .icon-bar .item.disabled > * {
      opacity: 0.7;
      cursor: false; }

.icon-bar.two-up .item {
  width: 50%; }
.icon-bar.two-up.vertical .item, .icon-bar.two-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.two-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.two-up.large-vertical .item {
    width: auto; } }
.icon-bar.three-up .item {
  width: 33.3333%; }
.icon-bar.three-up.vertical .item, .icon-bar.three-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.three-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.three-up.large-vertical .item {
    width: auto; } }
.icon-bar.four-up .item {
  width: 25%; }
.icon-bar.four-up.vertical .item, .icon-bar.four-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.four-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.four-up.large-vertical .item {
    width: auto; } }
.icon-bar.five-up .item {
  width: 20%; }
.icon-bar.five-up.vertical .item, .icon-bar.five-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.five-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.five-up.large-vertical .item {
    width: auto; } }
.icon-bar.six-up .item {
  width: 16.66667%; }
.icon-bar.six-up.vertical .item, .icon-bar.six-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.six-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.six-up.large-vertical .item {
    width: auto; } }
.icon-bar.seven-up .item {
  width: 14.28571%; }
.icon-bar.seven-up.vertical .item, .icon-bar.seven-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.seven-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.seven-up.large-vertical .item {
    width: auto; } }
.icon-bar.eight-up .item {
  width: 12.5%; }
.icon-bar.eight-up.vertical .item, .icon-bar.eight-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.eight-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.eight-up.large-vertical .item {
    width: auto; } }

.inline-list {
  margin: 0 auto 1.0625rem auto;
  margin-left: -1.375rem;
  margin-right: 0;
  padding: 0;
  list-style: none;
  overflow: hidden; }
  .inline-list > li {
    list-style: none;
    float: left;
    margin-left: 1.375rem;
    display: block; }
    .inline-list > li > * {
      display: block; }

/* Foundation Joyride */
.joyride-list {
  display: none; }

/* Default styles for the container */
.joyride-tip-guide {
  display: none;
  position: absolute;
  background: #333333;
  color: #FFFFFF;
  z-index: 101;
  top: 0;
  left: 2.5%;
  font-family: inherit;
  font-weight: 400;
  width: 95%; }

.lt-ie9 .joyride-tip-guide {
  max-width: 800px;
  left: 50%;
  margin-left: -400px; }

.joyride-content-wrapper {
  width: 100%;
  padding: 1.125rem 1.25rem 1.5rem; }
  .joyride-content-wrapper .button {
    margin-bottom: 0 !important; }
  .joyride-content-wrapper .joyride-prev-tip {
    margin-right: 10px; }

/* Add a little css triangle pip, older browser just miss out on the fanciness of it */
.joyride-tip-guide .joyride-nub {
  display: block;
  position: absolute;
  left: 22px;
  width: 0;
  height: 0;
  border: 10px solid #333333; }
  .joyride-tip-guide .joyride-nub.top {
    border-top-style: solid;
    border-color: #333333;
    border-top-color: transparent !important;
    border-left-color: transparent !important;
    border-right-color: transparent !important;
    top: -20px; }
  .joyride-tip-guide .joyride-nub.bottom {
    border-bottom-style: solid;
    border-color: #333333 !important;
    border-bottom-color: transparent !important;
    border-left-color: transparent !important;
    border-right-color: transparent !important;
    bottom: -20px; }
  .joyride-tip-guide .joyride-nub.right {
    right: -20px; }
  .joyride-tip-guide .joyride-nub.left {
    left: -20px; }

/* Typography */
.joyride-tip-guide h1, .joyride-tip-guide h2, .joyride-tip-guide h3, .joyride-tip-guide h4, .joyride-tip-guide h5, .joyride-tip-guide h6 {
  line-height: 1.25;
  margin: 0;
  font-weight: bold;
  color: #FFFFFF; }

.joyride-tip-guide p {
  margin: 0 0 1.125rem 0;
  font-size: 0.875rem;
  line-height: 1.3; }

.joyride-timer-indicator-wrap {
  width: 50px;
  height: 3px;
  border: solid 1px #555555;
  position: absolute;
  right: 1.0625rem;
  bottom: 1rem; }

.joyride-timer-indicator {
  display: block;
  width: 0;
  height: inherit;
  background: #666666; }

.joyride-close-tip {
  position: absolute;
  right: 12px;
  top: 10px;
  color: #777777 !important;
  text-decoration: none;
  font-size: 24px;
  font-weight: 400;
  line-height: .5 !important; }
  .joyride-close-tip:hover, .joyride-close-tip:focus {
    color: #EEEEEE !important; }

.joyride-modal-bg {
  position: fixed;
  height: 100%;
  width: 100%;
  background: transparent;
  background: rgba(0, 0, 0, 0.5);
  z-index: 100;
  display: none;
  top: 0;
  left: 0;
  cursor: pointer; }

.joyride-expose-wrapper {
  background-color: #FFFFFF;
  position: absolute;
  border-radius: 3px;
  z-index: 102;
  box-shadow: 0 0 15px #FFFFFF; }

.joyride-expose-cover {
  background: transparent;
  border-radius: 3px;
  position: absolute;
  z-index: 9999;
  top: 0;
  left: 0; }

/* Styles for screens that are at least 768px; */
@media only screen and (min-width:40.063em) {
  .joyride-tip-guide {
    width: 300px;
    left: inherit; }
    .joyride-tip-guide .joyride-nub.bottom {
      border-color: #333333 !important;
      border-bottom-color: transparent !important;
      border-left-color: transparent !important;
      border-right-color: transparent !important;
      bottom: -20px; }
    .joyride-tip-guide .joyride-nub.right {
      border-color: #333333 !important;
      border-top-color: transparent !important;
      border-right-color: transparent !important;
      border-bottom-color: transparent !important;
      top: 22px;
      left: auto;
      right: -20px; }
    .joyride-tip-guide .joyride-nub.left {
      border-color: #333333 !important;
      border-top-color: transparent !important;
      border-left-color: transparent !important;
      border-bottom-color: transparent !important;
      top: 22px;
      left: -20px;
      right: auto; } }

.keystroke, kbd {
  background-color: #ededed;
  border-color: #dddddd;
  color: #222222;
  border-style: solid;
  border-width: 1px;
  margin: 0;
  font-family: "Consolas", "Menlo", "Courier", monospace;
  font-size: inherit;
  padding: 0.125rem 0.25rem 0;
  border-radius: 3px; }

.label {
  font-weight: 400;
  font-family: arial, sans-serif;
  text-align: center;
  text-decoration: none;
  line-height: 1;
  white-space: nowrap;
  display: inline-block;
  position: relative;
  margin-bottom: auto;
  padding: 0.25rem 0.5rem 0.25rem;
  font-size: 0.6875rem;
  background-color: #1f5c87;
  color: #FFFFFF; }
  .label.radius {
    border-radius: 3px; }
  .label.round {
    border-radius: 1000px; }
  .label.alert {
    background-color: #f04124;
    color: #FFFFFF; }
  .label.warning {
    background-color: #f08a24;
    color: #FFFFFF; }
  .label.success {
    background-color: #43AC6A;
    color: #FFFFFF; }
  .label.secondary {
    background-color: #E7E7E7;
    color: #333333; }
  .label.info {
    background-color: #a0d3e8;
    color: #333333; }

[data-magellan-expedition], [data-magellan-expedition-clone] {
  background: #FFFFFF;
  z-index: 50;
  min-width: 100%;
  padding: 10px; }
  [data-magellan-expedition] .sub-nav, [data-magellan-expedition-clone] .sub-nav {
    margin-bottom: 0; }
    [data-magellan-expedition] .sub-nav dd, [data-magellan-expedition-clone] .sub-nav dd {
      margin-bottom: 0; }
    [data-magellan-expedition] .sub-nav a, [data-magellan-expedition-clone] .sub-nav a {
      line-height: 1.8em; }

@-webkit-keyframes rotate {
  from {
    -webkit-transform: rotate(0deg); }

  to {
    -webkit-transform: rotate(360deg); } }

@-moz-keyframes rotate {
  from {
    -moz-transform: rotate(0deg); }

  to {
    -moz-transform: rotate(360deg); } }

@-o-keyframes rotate {
  from {
    -o-transform: rotate(0deg); }

  to {
    -o-transform: rotate(360deg); } }

@keyframes rotate {
  from {
    transform: rotate(0deg); }

  to {
    transform: rotate(360deg); } }

/* Orbit Graceful Loading */
.slideshow-wrapper {
  position: relative; }
  .slideshow-wrapper ul {
    list-style-type: none;
    margin: 0; }
    .slideshow-wrapper ul li, .slideshow-wrapper ul li .orbit-caption {
      display: none; }
    .slideshow-wrapper ul li:first-child {
      display: block; }
  .slideshow-wrapper .orbit-container {
    background-color: transparent; }
    .slideshow-wrapper .orbit-container li {
      display: block; }
      .slideshow-wrapper .orbit-container li .orbit-caption {
        display: block; }
    .slideshow-wrapper .orbit-container .orbit-bullets li {
      display: inline-block; }
  .slideshow-wrapper .preloader {
    display: block;
    width: 40px;
    height: 40px;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-top: -20px;
    margin-left: -20px;
    border: solid 3px;
    border-color: #555555 #FFFFFF;
    border-radius: 1000px;
    animation-name: rotate;
    animation-duration: 1.5s;
    animation-iteration-count: infinite;
    animation-timing-function: linear; }

.orbit-container {
  overflow: hidden;
  width: 100%;
  position: relative;
  background: none; }
  .orbit-container .orbit-slides-container {
    list-style: none;
    margin: 0;
    padding: 0;
    position: relative;
    -webkit-transform: translateZ(0); }
    .orbit-container .orbit-slides-container img {
      display: block;
      max-width: 100%; }
    .orbit-container .orbit-slides-container > * {
      position: absolute;
      top: 0;
      width: 100%;
      margin-left: 100%; }
      .orbit-container .orbit-slides-container > *:first-child {
        margin-left: 0; }
      .orbit-container .orbit-slides-container > * .orbit-caption {
        position: absolute;
        bottom: 0;
        background-color: rgba(51, 51, 51, 0.8);
        color: #FFFFFF;
        width: 100%;
        padding: 0.625rem 0.875rem;
        font-size: 0.875rem; }
  .orbit-container .orbit-slide-number {
    position: absolute;
    top: 10px;
    left: 10px;
    font-size: 12px;
    color: #FFFFFF;
    background: transparent;
    z-index: 10; }
    .orbit-container .orbit-slide-number span {
      font-weight: 700;
      padding: 0.3125rem; }
  .orbit-container .orbit-timer {
    position: absolute;
    top: 12px;
    right: 10px;
    height: 6px;
    width: 100px;
    z-index: 10; }
    .orbit-container .orbit-timer .orbit-progress {
      height: 3px;
      background-color: rgba(255, 255, 255, 0.3);
      display: block;
      width: 0;
      position: relative;
      right: 20px;
      top: 5px; }
    .orbit-container .orbit-timer > span {
      display: none;
      position: absolute;
      top: 0;
      right: 0;
      width: 11px;
      height: 14px;
      border: solid 4px #FFFFFF;
      border-top: none;
      border-bottom: none; }
    .orbit-container .orbit-timer.paused > span {
      right: -4px;
      top: 0;
      width: 11px;
      height: 14px;
      border: inset 8px;
      border-left-style: solid;
      border-color: transparent;
      border-left-color: #FFFFFF; }
      .orbit-container .orbit-timer.paused > span.dark {
        border-left-color: #333333; }
  .orbit-container:hover .orbit-timer > span {
    display: block; }
  .orbit-container .orbit-prev, .orbit-container .orbit-next {
    position: absolute;
    top: 45%;
    margin-top: -25px;
    width: 36px;
    height: 60px;
    line-height: 50px;
    color: white;
    background-color: transparent;
    text-indent: -9999px !important;
    z-index: 10; }
    .orbit-container .orbit-prev:hover, .orbit-container .orbit-next:hover {
      background-color: rgba(0, 0, 0, 0.3); }
    .orbit-container .orbit-prev > span, .orbit-container .orbit-next > span {
      position: absolute;
      top: 50%;
      margin-top: -10px;
      display: block;
      width: 0;
      height: 0;
      border: inset 10px; }
  .orbit-container .orbit-prev {
    left: 0; }
    .orbit-container .orbit-prev > span {
      border-right-style: solid;
      border-color: transparent;
      border-right-color: #FFFFFF; }
    .orbit-container .orbit-prev:hover > span {
      border-right-color: #FFFFFF; }
  .orbit-container .orbit-next {
    right: 0; }
    .orbit-container .orbit-next > span {
      border-color: transparent;
      border-left-style: solid;
      border-left-color: #FFFFFF;
      left: 50%;
      margin-left: -4px; }
    .orbit-container .orbit-next:hover > span {
      border-left-color: #FFFFFF; }

.orbit-bullets-container {
  text-align: center; }

.orbit-bullets {
  margin: 0 auto 30px auto;
  overflow: hidden;
  position: relative;
  top: 10px;
  float: none;
  text-align: center;
  display: block; }
  .orbit-bullets li {
    cursor: pointer;
    display: inline-block;
    width: 0.5625rem;
    height: 0.5625rem;
    background: #565656;
    float: none;
    margin-right: 6px;
    border-radius: 1000px; }
    .orbit-bullets li.active {
      background: #999999; }
    .orbit-bullets li:last-child {
      margin-right: 0; }

.touch .orbit-container .orbit-prev, .touch .orbit-container .orbit-next {
  display: none; }
.touch .orbit-bullets {
  display: none; }

@media only screen and (min-width:40.063em) {
  .touch .orbit-container .orbit-prev, .touch .orbit-container .orbit-next {
    display: inherit; }
  .touch .orbit-bullets {
    display: block; } }

@media only screen and (max-width: 40em) {
  .orbit-stack-on-small .orbit-slides-container {
    height: auto !important; }
  .orbit-stack-on-small .orbit-slides-container > * {
    position: relative;
    margin: 0 !important;
    opacity: 1 !important; }
  .orbit-stack-on-small .orbit-slide-number {
    display: none; }
  .orbit-timer {
    display: none; }
  .orbit-next, .orbit-prev {
    display: none; }
  .orbit-bullets {
    display: none; } }

ul.pagination {
  display: block;
  min-height: 1.5rem;
  margin-left: -0.3125rem; }
  ul.pagination li {
    height: 1.5rem;
    color: #222222;
    font-size: 0.875rem;
    margin-left: 0.3125rem; }
    ul.pagination li a, ul.pagination li button {
      display: block;
      padding: 0.0625rem 0.625rem 0.0625rem;
      color: #999999;
      background: none;
      border-radius: 3px;
      font-weight: normal;
      font-size: 1em;
      line-height: inherit;
      transition: background-color 300ms ease-out; }
    ul.pagination li:hover a, ul.pagination li a:focus, ul.pagination li:hover button, ul.pagination li button:focus {
      background: #e6e6e6; }
    ul.pagination li.unavailable a, ul.pagination li.unavailable button {
      cursor: default;
      color: #999999; }
    ul.pagination li.unavailable:hover a, ul.pagination li.unavailable a:focus, ul.pagination li.unavailable:hover button, ul.pagination li.unavailable button:focus {
      background: transparent; }
    ul.pagination li.current a, ul.pagination li.current button {
      background: #1f5c87;
      color: #FFFFFF;
      font-weight: bold;
      cursor: default; }
      ul.pagination li.current a:hover, ul.pagination li.current a:focus, ul.pagination li.current button:hover, ul.pagination li.current button:focus {
        background: #1f5c87; }
  ul.pagination li {
    float: left;
    display: block; }

/* Pagination centred wrapper */
.pagination-centered {
  text-align: center; }
  .pagination-centered ul.pagination li {
    float: none;
    display: inline-block; }

/* Panels */
.panel {
  border-style: solid;
  border-width: 1px;
  border-color: #d8d8d8;
  margin-bottom: 1.25rem;
  padding: 1.25rem;
  background: #f2f2f2;
  color: #333333; }
  .panel > :first-child {
    margin-top: 0; }
  .panel > :last-child {
    margin-bottom: 0; }
  .panel h1, .panel h2, .panel h3, .panel h4, .panel h5, .panel h6, .panel p, .panel li, .panel dl {
    color: #333333; }
  .panel h1, .panel h2, .panel h3, .panel h4, .panel h5, .panel h6 {
    line-height: 1;
    margin-bottom: 0.625rem; }
    .panel h1.subheader, .panel h2.subheader, .panel h3.subheader, .panel h4.subheader, .panel h5.subheader, .panel h6.subheader {
      line-height: 1.4; }
  .panel.callout {
    border-style: solid;
    border-width: 1px;
    border-color: #ffe5b9;
    margin-bottom: 1.25rem;
    padding: 1.25rem;
    background: #fff9f0;
    color: #333333; }
    .panel.callout > :first-child {
      margin-top: 0; }
    .panel.callout > :last-child {
      margin-bottom: 0; }
    .panel.callout h1, .panel.callout h2, .panel.callout h3, .panel.callout h4, .panel.callout h5, .panel.callout h6, .panel.callout p, .panel.callout li, .panel.callout dl {
      color: #333333; }
    .panel.callout h1, .panel.callout h2, .panel.callout h3, .panel.callout h4, .panel.callout h5, .panel.callout h6 {
      line-height: 1;
      margin-bottom: 0.625rem; }
      .panel.callout h1.subheader, .panel.callout h2.subheader, .panel.callout h3.subheader, .panel.callout h4.subheader, .panel.callout h5.subheader, .panel.callout h6.subheader {
        line-height: 1.4; }
    .panel.callout a:not(.button) {
      color: #1f5c87; }
      .panel.callout a:not(.button):hover, .panel.callout a:not(.button):focus {
        color: #db8a00; }
  .panel.radius {
    border-radius: 3px; }

/* Pricing Tables */
.pricing-table {
  border: solid 1px #DDDDDD;
  margin-left: 0;
  margin-bottom: 1.25rem; }
  .pricing-table * {
    list-style: none;
    line-height: 1; }
  .pricing-table .title {
    background-color: #333333;
    padding: 0.9375rem 1.25rem;
    text-align: center;
    color: #EEEEEE;
    font-weight: 400;
    font-size: 1rem;
    font-family: arial, sans-serif; }
  .pricing-table .price {
    background-color: #F6F6F6;
    padding: 0.9375rem 1.25rem;
    text-align: center;
    color: #333333;
    font-weight: 400;
    font-size: 2rem;
    font-family: arial, sans-serif; }
  .pricing-table .description {
    background-color: #FFFFFF;
    padding: 0.9375rem;
    text-align: center;
    color: #777777;
    font-size: 0.75rem;
    font-weight: 400;
    line-height: 1.4;
    border-bottom: dotted 1px #DDDDDD; }
  .pricing-table .bullet-item {
    background-color: #FFFFFF;
    padding: 0.9375rem;
    text-align: center;
    color: #333333;
    font-size: 0.875rem;
    font-weight: 400;
    border-bottom: dotted 1px #DDDDDD; }
  .pricing-table .cta-button {
    background-color: #FFFFFF;
    text-align: center;
    padding: 1.25rem 1.25rem 0; }

/* Progress Bar */
.progress {
  background-color: #F6F6F6;
  height: 1.5625rem;
  border: 1px solid white;
  padding: 0.125rem;
  margin-bottom: 0.625rem; }
  .progress .meter {
    background: #1f5c87;
    height: 100%;
    display: block; }
  .progress.secondary .meter {
    background: #E7E7E7;
    height: 100%;
    display: block; }
  .progress.success .meter {
    background: #43AC6A;
    height: 100%;
    display: block; }
  .progress.alert .meter {
    background: #f04124;
    height: 100%;
    display: block; }
  .progress.radius {
    border-radius: 3px; }
    .progress.radius .meter {
      border-radius: 2px; }
  .progress.round {
    border-radius: 1000px; }
    .progress.round .meter {
      border-radius: 999px; }

.range-slider {
  position: relative;
  border: 1px solid #DDDDDD;
  margin: 1.25rem 0;
  -ms-touch-action: none;
  touch-action: none;
  display: block;
  width: 100%;
  height: 1rem;
  background: #FAFAFA; }
  .range-slider.vertical-range {
    position: relative;
    border: 1px solid #DDDDDD;
    margin: 1.25rem 0;
    -ms-touch-action: none;
    touch-action: none;
    display: inline-block;
    width: 1rem;
    height: 12.5rem; }
    .range-slider.vertical-range .range-slider-handle {
      margin-top: 0;
      margin-left: -0.5rem;
      position: absolute;
      bottom: -10.5rem; }
    .range-slider.vertical-range .range-slider-active-segment {
      width: 0.875rem;
      height: auto;
      bottom: 0; }
  .range-slider.radius {
    background: #FAFAFA;
    border-radius: 3px; }
    .range-slider.radius .range-slider-handle {
      background: #1f5c87;
      border-radius: 3px; }
      .range-slider.radius .range-slider-handle:hover {
        background: #e08e00; }
  .range-slider.round {
    background: #FAFAFA;
    border-radius: 1000px; }
    .range-slider.round .range-slider-handle {
      background: #1f5c87;
      border-radius: 1000px; }
      .range-slider.round .range-slider-handle:hover {
        background: #e08e00; }
  .range-slider.disabled, .range-slider[disabled] {
    background: #FAFAFA;
    cursor: false;
    opacity: 0.7; }
    .range-slider.disabled .range-slider-handle, .range-slider[disabled] .range-slider-handle {
      background: #1f5c87;
      cursor: default;
      opacity: 0.7; }
      .range-slider.disabled .range-slider-handle:hover, .range-slider[disabled] .range-slider-handle:hover {
        background: #e08e00; }

.range-slider-active-segment {
  display: inline-block;
  position: absolute;
  height: 0.875rem;
  background: #e5e5e5; }

.range-slider-handle {
  display: inline-block;
  position: absolute;
  z-index: 1;
  top: -0.3125rem;
  width: 2rem;
  height: 1.375rem;
  border: 1px solid none;
  cursor: pointer;
  -ms-touch-action: manipulation;
  touch-action: manipulation;
  background: #1f5c87; }
  .range-slider-handle:hover {
    background: #e08e00; }

.reveal-modal-bg {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: #000000;
  background: rgba(0, 0, 0, 0.45);
  z-index: 1004;
  display: none;
  left: 0; }

.reveal-modal {
  visibility: hidden;
  display: none;
  position: absolute;
  z-index: 1005;
  width: 100%;
  top: 0;
  border-radius: 3px;
  left: 0;
  background-color: #FFFFFF;
  padding: 1.875rem;
  border: solid 1px #666666;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.4); }
  @media only screen and (max-width: 40em) {
    .reveal-modal {
      min-height: 100vh; } }
  .reveal-modal .column, .reveal-modal .columns {
    min-width: 0; }
  .reveal-modal > :first-child {
    margin-top: 0; }
  .reveal-modal > :last-child {
    margin-bottom: 0; }
  @media only screen and (min-width:40.063em) {
    .reveal-modal {
      width: 80%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal {
      top: 6.25rem; } }
  .reveal-modal.radius {
    border-radius: 3px; }
  .reveal-modal.round {
    border-radius: 1000px; }
  .reveal-modal.collapse {
    padding: 0; }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.tiny {
      width: 30%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.small {
      width: 40%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.medium {
      width: 60%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.large {
      width: 70%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.xlarge {
      width: 95%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  .reveal-modal.full {
    top: 0;
    left: 0;
    height: 100%;
    height: 100vh;
    min-height: 100vh;
    max-width: none !important;
    margin-left: 0 !important; }
    @media only screen and (min-width:40.063em) {
      .reveal-modal.full {
        width: 100%;
        max-width: 68.75rem;
        left: 0;
        right: 0;
        margin: 0 auto; } }
  .reveal-modal.toback {
    z-index: 1003; }
  .reveal-modal .close-reveal-modal {
    font-size: 2.5rem;
    line-height: 1;
    position: absolute;
    top: 0.625rem;
    right: 1.375rem;
    color: #AAAAAA;
    font-weight: bold;
    cursor: pointer; }

.side-nav {
  display: block;
  margin: 0;
  padding: 0.875rem 0;
  list-style-type: none;
  list-style-position: outside;
  font-family: arial, sans-serif; }
  .side-nav li {
    margin: 0 0 0.4375rem 0;
    font-size: 0.875rem;
    font-weight: 400; }
    .side-nav li a:not(.button) {
      display: block;
      color: #1f5c87;
      margin: 0;
      padding: 0.4375rem 0.875rem; }
      .side-nav li a:not(.button):hover, .side-nav li a:not(.button):focus {
        background: rgba(0, 0, 0, 0.025);
        color: #ffbd4d; }
    .side-nav li.active > a:first-child:not(.button) {
      color: #ffbd4d;
      font-weight: 400;
      font-family: arial, sans-serif; }
    .side-nav li.divider {
      border-top: 1px solid;
      height: 0;
      padding: 0;
      list-style: none;
      border-top-color: white; }
    .side-nav li.heading {
      color: #1f5c87;
      font-size: 0.875rem;
      font-weight: bold;
      text-transform: uppercase; }

.split.button {
  position: relative;
  padding-right: 5.0625rem; }
  .split.button span {
    display: block;
    height: 100%;
    position: absolute;
    right: 0;
    top: 0;
    border-left: solid 1px; }
    .split.button span:after {
      position: absolute;
      content: "";
      width: 0;
      height: 0;
      display: block;
      border-style: inset;
      top: 50%;
      left: 50%; }
    .split.button span:active {
      background-color: rgba(0, 0, 0, 0.1); }
  .split.button span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button span {
    width: 3.09375rem; }
    .split.button span:after {
      border-top-style: solid;
      border-width: 0.375rem;
      top: 48%;
      margin-left: -0.375rem; }
  .split.button span:after {
    border-color: #FFFFFF transparent transparent transparent; }
  .split.button.secondary span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button.secondary span:after {
    border-color: #FFFFFF transparent transparent transparent; }
  .split.button.alert span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button.success span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button.tiny {
    padding-right: 3.75rem; }
    .split.button.tiny span {
      width: 2.25rem; }
      .split.button.tiny span:after {
        border-top-style: solid;
        border-width: 0.375rem;
        top: 48%;
        margin-left: -0.375rem; }
  .split.button.small {
    padding-right: 4.375rem; }
    .split.button.small span {
      width: 2.625rem; }
      .split.button.small span:after {
        border-top-style: solid;
        border-width: 0.4375rem;
        top: 48%;
        margin-left: -0.375rem; }
  .split.button.large {
    padding-right: 5.5rem; }
    .split.button.large span {
      width: 3.4375rem; }
      .split.button.large span:after {
        border-top-style: solid;
        border-width: 0.3125rem;
        top: 48%;
        margin-left: -0.375rem; }
  .split.button.expand {
    padding-left: 2rem; }
  .split.button.secondary span:after {
    border-color: #333333 transparent transparent transparent; }
  .split.button.radius span {
    -webkit-border-bottom-right-radius: 3px;
    -webkit-border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
    border-top-right-radius: 3px; }
  .split.button.round span {
    -webkit-border-bottom-right-radius: 1000px;
    -webkit-border-top-right-radius: 1000px;
    border-bottom-right-radius: 1000px;
    border-top-right-radius: 1000px; }
  .split.button.no-pip span:before {
    border-style: none; }
  .split.button.no-pip span:after {
    border-style: none; }
  .split.button.no-pip span > i {
    top: 50%;
    display: block;
    position: absolute;
    left: 50%;
    margin-left: -0.28889em;
    margin-top: -0.48889em; }

.sub-nav {
  display: block;
  width: auto;
  overflow: hidden;
  margin-bottom: -0.25rem 0 1.125rem;
  padding-top: 0.25rem; }
  .sub-nav dt {
    text-transform: uppercase; }
  .sub-nav dt, .sub-nav dd, .sub-nav li {
    float: left;
    margin-left: 1rem;
    margin-bottom: 0;
    font-family: arial, sans-serif;
    font-weight: 400;
    font-size: 0.875rem;
    color: #999999; }
    .sub-nav dt a, .sub-nav dd a, .sub-nav li a {
      text-decoration: none;
      color: #999999;
      padding: 0.1875rem 1rem; }
      .sub-nav dt a:hover, .sub-nav dd a:hover, .sub-nav li a:hover {
        color: #737373; }
    .sub-nav dt.active a, .sub-nav dd.active a, .sub-nav li.active a {
      border-radius: 3px;
      font-weight: 400;
      background: #1f5c87;
      padding: 0.1875rem 1rem;
      cursor: default;
      color: #FFFFFF; }
      .sub-nav dt.active a:hover, .sub-nav dd.active a:hover, .sub-nav li.active a:hover {
        background: #db8a00; }

.switch {
  padding: 0;
  border: none;
  position: relative;
  outline: 0;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none; }
  .switch label {
    display: block;
    margin-bottom: 1rem;
    position: relative;
    color: transparent;
    background: #DDDDDD;
    text-indent: 100%;
    width: 4rem;
    height: 2rem;
    cursor: pointer;
    transition: left 0.15s ease-out; }
  .switch input {
    opacity: 0;
    position: absolute;
    top: 9px;
    left: 10px;
    padding: 0; }
    .switch input + label {
      margin-left: 0;
      margin-right: 0; }
  .switch label:after {
    content: "";
    display: block;
    background: #FFFFFF;
    position: absolute;
    top: .25rem;
    left: .25rem;
    width: 1.5rem;
    height: 1.5rem;
    -webkit-transition: left 0.15s ease-out;
    -moz-transition: left 0.15s ease-out;
    -o-transition: translate3d(0, 0, 0);
    transition: left 0.15s ease-out;
    -webkit-transform: translate3d(0, 0, 0);
    -moz-transform: translate3d(0, 0, 0);
    -o-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0); }
  .switch input:checked + label {
    background: #1f5c87; }
  .switch input:checked + label:after {
    left: 2.25rem; }
  .switch label {
    width: 4rem;
    height: 2rem; }
  .switch label:after {
    width: 1.5rem;
    height: 1.5rem; }
  .switch input:checked + label:after {
    left: 2.25rem; }
  .switch label {
    color: transparent;
    background: #DDDDDD; }
  .switch label:after {
    background: #FFFFFF; }
  .switch input:checked + label {
    background: #1f5c87; }
  .switch.large label {
    width: 5rem;
    height: 2.5rem; }
  .switch.large label:after {
    width: 2rem;
    height: 2rem; }
  .switch.large input:checked + label:after {
    left: 2.75rem; }
  .switch.small label {
    width: 3.5rem;
    height: 1.75rem; }
  .switch.small label:after {
    width: 1.25rem;
    height: 1.25rem; }
  .switch.small input:checked + label:after {
    left: 2rem; }
  .switch.tiny label {
    width: 3rem;
    height: 1.5rem; }
  .switch.tiny label:after {
    width: 1rem;
    height: 1rem; }
  .switch.tiny input:checked + label:after {
    left: 1.75rem; }
  .switch.radius label {
    border-radius: 4px; }
  .switch.radius label:after {
    border-radius: 3px; }
  .switch.round {
    border-radius: 1000px; }
    .switch.round label {
      border-radius: 2rem; }
    .switch.round label:after {
      border-radius: 2rem; }

table {
  background: #FFFFFF;
  margin-bottom: 1.25rem;
  border: solid 1px #DDDDDD;
  table-layout: auto; }
  table caption {
    background: transparent;
    color: #222222;
    font-size: 1rem;
    font-weight: bold; }
  table thead {
    background: #F5F5F5; }
    table thead tr th, table thead tr td {
      padding: 0.5rem 0.625rem 0.625rem;
      font-size: 0.875rem;
      font-weight: bold;
      color: #222222; }
  table tfoot {
    background: #F5F5F5; }
    table tfoot tr th, table tfoot tr td {
      padding: 0.5rem 0.625rem 0.625rem;
      font-size: 0.875rem;
      font-weight: bold;
      color: #222222; }
  table tr th, table tr td {
    padding: 0.5625rem 0.625rem;
    font-size: 0.875rem;
    color: #222222;
    text-align: left; }
  table tr.even, table tr.alt, table tr:nth-of-type(even) {
    background: #F9F9F9; }
  table thead tr th, table tfoot tr th, table tfoot tr td, table tbody tr th, table tbody tr td, table tr td {
    display: table-cell;
    line-height: 1.125rem; }

.tabs {
  margin-bottom: 0 !important;
  margin-left: 0; }
  .tabs:before, .tabs:after {
    content: " ";
    display: table; }
  .tabs:after {
    clear: both; }
  .tabs dd, .tabs .tab-title {
    position: relative;
    margin-bottom: 0 !important;
    list-style: none;
    float: left; }
    .tabs dd > a, .tabs .tab-title > a {
      display: block;
      background-color: #EFEFEF;
      color: #222222;
      padding: 1rem 2rem;
      font-family: arial, sans-serif;
      font-size: 1rem; }
      .tabs dd > a:hover, .tabs .tab-title > a:hover {
        background-color: #e1e1e1; }
      .tabs dd > a:focus, .tabs .tab-title > a:focus {
        outline: none; }
    .tabs dd.active a, .tabs .tab-title.active a {
      background-color: #FFFFFF;
      color: #222222; }
  .tabs.radius dd:first-child a, .tabs.radius .tab:first-child a {
    -webkit-border-bottom-left-radius: 3px;
    -webkit-border-top-left-radius: 3px;
    border-bottom-left-radius: 3px;
    border-top-left-radius: 3px; }
  .tabs.radius dd:last-child a, .tabs.radius .tab:last-child a {
    -webkit-border-bottom-right-radius: 3px;
    -webkit-border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
    border-top-right-radius: 3px; }
  .tabs.vertical dd, .tabs.vertical .tab-title {
    position: inherit;
    float: none;
    display: block;
    top: auto; }

.tabs-content {
  margin-bottom: 1.5rem;
  width: 100%; }
  .tabs-content:before, .tabs-content:after {
    content: " ";
    display: table; }
  .tabs-content:after {
    clear: both; }
  .tabs-content > .content {
    display: none;
    float: left;
    padding: 0.9375rem 0;
    width: 100%; }
    .tabs-content > .content.active {
      display: block;
      float: none; }
    .tabs-content > .content.contained {
      padding: 0.9375rem; }
  .tabs-content.vertical {
    display: block; }
    .tabs-content.vertical > .content {
      padding: 0 0.9375rem; }

@media only screen and (min-width:40.063em) {
  .tabs.vertical {
    width: 20%;
    max-width: 20%;
    float: left;
    margin: 0 0 1.25rem; }
  .tabs-content.vertical {
    width: 80%;
    max-width: 80%;
    float: left;
    margin-left: -1px;
    padding-left: 1rem; } }

.no-js .tabs-content > .content {
  display: block;
  float: none; }

/* Image Thumbnails */
.th {
  line-height: 0;
  display: inline-block;
  border: solid 4px #FFFFFF;
  max-width: 100%;
  box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.2);
  transition: all 200ms ease-out; }
  .th:hover, .th:focus {
    box-shadow: 0 0 6px 1px rgba(255, 161, 0, 0.5); }
  .th.radius {
    border-radius: 3px; }

/* Tooltips */
.has-tip {
  border-bottom: dotted 1px #565656;
  cursor: help;
  font-weight: bold;
  color: #333333; }
  .has-tip:hover, .has-tip:focus {
    border-bottom: dotted 1px #734800;
    color: #1f5c87; }
  .has-tip.tip-left, .has-tip.tip-right {
    float: none !important; }

.tooltip {
  display: none;
  position: absolute;
  z-index: 1006;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.3;
  padding: 0.75rem;
  max-width: 300px;
  left: 50%;
  width: 100%;
  color: #FFFFFF;
  background: #333333; }
  .tooltip > .nub {
    display: block;
    left: 5px;
    position: absolute;
    width: 0;
    height: 0;
    border: solid 5px;
    border-color: transparent transparent #333333 transparent;
    top: -10px;
    pointer-events: none; }
    .tooltip > .nub.rtl {
      left: auto;
      right: 5px; }
  .tooltip.radius {
    border-radius: 3px; }
  .tooltip.round {
    border-radius: 1000px; }
    .tooltip.round > .nub {
      left: 2rem; }
  .tooltip.opened {
    color: #1f5c87 !important;
    border-bottom: dotted 1px #734800 !important; }

.tap-to-close {
  display: block;
  font-size: 0.625rem;
  color: #777777;
  font-weight: 400; }

@media only screen and (min-width:40.063em) {
  .tooltip > .nub {
    border-color: transparent transparent #333333 transparent;
    top: -10px; }
  .tooltip.tip-top > .nub {
    border-color: #333333 transparent transparent transparent;
    top: auto;
    bottom: -10px; }
  .tooltip.tip-left, .tooltip.tip-right {
    float: none !important; }
  .tooltip.tip-left > .nub {
    border-color: transparent transparent transparent #333333;
    right: -10px;
    left: auto;
    top: 50%;
    margin-top: -5px; }
  .tooltip.tip-right > .nub {
    border-color: transparent #333333 transparent transparent;
    right: auto;
    left: -10px;
    top: 50%;
    margin-top: -5px; } }

meta.foundation-mq-topbar {
  font-family: "/only screen and (min-width:40.063em)/";
  width: 40.063em; }

/* Wrapped around .top-bar to contain to grid width */
.contain-to-grid {
  width: 100%;
  background: #333333; }
  .contain-to-grid .top-bar {
    margin-bottom: 0; }

.fixed {
  width: 100%;
  left: 0;
  position: fixed;
  top: 0;
  z-index: 99; }
  .fixed.expanded:not(.top-bar) {
    overflow-y: auto;
    height: auto;
    width: 100%;
    max-height: 100%; }
    .fixed.expanded:not(.top-bar) .title-area {
      position: fixed;
      width: 100%;
      z-index: 99; }
    .fixed.expanded:not(.top-bar) .top-bar-section {
      z-index: 98;
      margin-top: 2.8125rem; }

.top-bar {
  overflow: hidden;
  height: 2.8125rem;
  line-height: 2.8125rem;
  position: relative;
  background: #333333;
  margin-bottom: 0; }
  .top-bar ul {
    margin-bottom: 0;
    list-style: none; }
  .top-bar .row {
    max-width: none; }
  .top-bar form, .top-bar input {
    margin-bottom: 0; }
  .top-bar input {
    height: 1.75rem;
    padding-top: .35rem;
    padding-bottom: .35rem;
    font-size: 0.75rem; }
  .top-bar .button, .top-bar button {
    padding-top: .4125rem;
    padding-bottom: .4125rem;
    margin-bottom: 0;
    font-size: 0.75rem; }
    @media only screen and (max-width: 40em) {
      .top-bar .button, .top-bar button {
        position: relative;
        top: -1px; } }
  .top-bar .title-area {
    position: relative;
    margin: 0; }
  .top-bar .name {
    height: 2.8125rem;
    margin: 0;
    font-size: 16px; }
    .top-bar .name h1, .top-bar .name h2, .top-bar .name h3, .top-bar .name h4, .top-bar .name p, .top-bar .name span {
      line-height: 2.8125rem;
      font-size: 1.0625rem;
      margin: 0; }
      .top-bar .name h1 a, .top-bar .name h2 a, .top-bar .name h3 a, .top-bar .name h4 a, .top-bar .name p a, .top-bar .name span a {
        font-weight: 400;
        color: #FFFFFF;
        width: 75%;
        display: block;
        padding: 0 0.9375rem; }
  .top-bar .toggle-topbar {
    position: absolute;
    right: 0;
    top: 0; }
    .top-bar .toggle-topbar a {
      color: #FFFFFF;
      text-transform: uppercase;
      font-size: 0.8125rem;
      font-weight: bold;
      position: relative;
      display: block;
      padding: 0 0.9375rem;
      height: 2.8125rem;
      line-height: 2.8125rem; }
    .top-bar .toggle-topbar.menu-icon {
      top: 50%;
      margin-top: -16px; }
      .top-bar .toggle-topbar.menu-icon a {
        height: 34px;
        line-height: 33px;
        padding: 0 2.5rem 0 0.9375rem;
        color: #FFFFFF;
        position: relative; }
        .top-bar .toggle-topbar.menu-icon a span::after {
          content: "";
          position: absolute;
          display: block;
          height: 0;
          top: 50%;
          margin-top: -8px;
          right: 0.9375rem;
          box-shadow: 0 0 0 1px #FFFFFF, 0 7px 0 1px #FFFFFF, 0 14px 0 1px #FFFFFF;
          width: 16px; }
        .top-bar .toggle-topbar.menu-icon a span:hover:after {
          box-shadow: 0 0 0 1px "", 0 7px 0 1px "", 0 14px 0 1px ""; }
  .top-bar.expanded {
    height: auto;
    background: transparent; }
    .top-bar.expanded .title-area {
      background: #333333; }
    .top-bar.expanded .toggle-topbar a {
      color: #888888; }
      .top-bar.expanded .toggle-topbar a span::after {
        box-shadow: 0 0 0 1px #888888, 0 7px 0 1px #888888, 0 14px 0 1px #888888; }

.top-bar-section {
  left: 0;
  position: relative;
  width: auto;
  transition: left 300ms ease-out; }
  .top-bar-section ul {
    padding: 0;
    width: 100%;
    height: auto;
    display: block;
    font-size: 16px;
    margin: 0; }
  .top-bar-section .divider, .top-bar-section [role="separator"] {
    border-top: solid 1px #1a1a1a;
    clear: both;
    height: 1px;
    width: 100%; }
  .top-bar-section ul li {
    background: #333333; }
    .top-bar-section ul li > a {
      display: block;
      width: 100%;
      color: #FFFFFF;
      padding: 12px 0 12px 0;
      padding-left: 0.9375rem;
      font-family: arial, sans-serif;
      font-size: 0.8125rem;
      font-weight: 400;
      text-transform: none; }
      .top-bar-section ul li > a.button {
        font-size: 0.8125rem;
        padding-right: 0.9375rem;
        padding-left: 0.9375rem;
        background-color: #1f5c87;
        border-color: #cc8100;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button:hover, .top-bar-section ul li > a.button:focus {
          background-color: #cc8100; }
        .top-bar-section ul li > a.button:hover, .top-bar-section ul li > a.button:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > a.button.secondary {
        background-color: #E7E7E7;
        border-color: #b9b9b9;
        color: #333333; }
        .top-bar-section ul li > a.button.secondary:hover, .top-bar-section ul li > a.button.secondary:focus {
          background-color: #b9b9b9; }
        .top-bar-section ul li > a.button.secondary:hover, .top-bar-section ul li > a.button.secondary:focus {
          color: #333333; }
      .top-bar-section ul li > a.button.success {
        background-color: #43AC6A;
        border-color: #368a55;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button.success:hover, .top-bar-section ul li > a.button.success:focus {
          background-color: #368a55; }
        .top-bar-section ul li > a.button.success:hover, .top-bar-section ul li > a.button.success:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > a.button.alert {
        background-color: #f04124;
        border-color: #cf2a0e;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button.alert:hover, .top-bar-section ul li > a.button.alert:focus {
          background-color: #cf2a0e; }
        .top-bar-section ul li > a.button.alert:hover, .top-bar-section ul li > a.button.alert:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > a.button.warning {
        background-color: #f08a24;
        border-color: #cf6e0e;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button.warning:hover, .top-bar-section ul li > a.button.warning:focus {
          background-color: #cf6e0e; }
        .top-bar-section ul li > a.button.warning:hover, .top-bar-section ul li > a.button.warning:focus {
          color: #FFFFFF; }
    .top-bar-section ul li > button {
      font-size: 0.8125rem;
      padding-right: 0.9375rem;
      padding-left: 0.9375rem;
      background-color: #1f5c87;
      border-color: #cc8100;
      color: #FFFFFF; }
      .top-bar-section ul li > button:hover, .top-bar-section ul li > button:focus {
        background-color: #cc8100; }
      .top-bar-section ul li > button:hover, .top-bar-section ul li > button:focus {
        color: #FFFFFF; }
      .top-bar-section ul li > button.secondary {
        background-color: #E7E7E7;
        border-color: #b9b9b9;
        color: #333333; }
        .top-bar-section ul li > button.secondary:hover, .top-bar-section ul li > button.secondary:focus {
          background-color: #b9b9b9; }
        .top-bar-section ul li > button.secondary:hover, .top-bar-section ul li > button.secondary:focus {
          color: #333333; }
      .top-bar-section ul li > button.success {
        background-color: #43AC6A;
        border-color: #368a55;
        color: #FFFFFF; }
        .top-bar-section ul li > button.success:hover, .top-bar-section ul li > button.success:focus {
          background-color: #368a55; }
        .top-bar-section ul li > button.success:hover, .top-bar-section ul li > button.success:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > button.alert {
        background-color: #f04124;
        border-color: #cf2a0e;
        color: #FFFFFF; }
        .top-bar-section ul li > button.alert:hover, .top-bar-section ul li > button.alert:focus {
          background-color: #cf2a0e; }
        .top-bar-section ul li > button.alert:hover, .top-bar-section ul li > button.alert:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > button.warning {
        background-color: #f08a24;
        border-color: #cf6e0e;
        color: #FFFFFF; }
        .top-bar-section ul li > button.warning:hover, .top-bar-section ul li > button.warning:focus {
          background-color: #cf6e0e; }
        .top-bar-section ul li > button.warning:hover, .top-bar-section ul li > button.warning:focus {
          color: #FFFFFF; }
    .top-bar-section ul li:hover:not(.has-form) > a {
      background-color: #555555;
      background: #333333;
      color: #FFFFFF; }
    .top-bar-section ul li.active > a {
      background: #1f5c87;
      color: #FFFFFF; }
      .top-bar-section ul li.active > a:hover {
        background: #db8a00;
        color: #FFFFFF; }
  .top-bar-section .has-form {
    padding: 0.9375rem; }
  .top-bar-section .has-dropdown {
    position: relative; }
    .top-bar-section .has-dropdown > a:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 5px;
      border-color: transparent transparent transparent rgba(255, 255, 255, 0.4);
      border-left-style: solid;
      margin-right: 0.9375rem;
      margin-top: -4.5px;
      position: absolute;
      top: 50%;
      right: 0; }
    .top-bar-section .has-dropdown.moved {
      position: static; }
      .top-bar-section .has-dropdown.moved > .dropdown {
        display: block;
        position: static !important;
        height: auto;
        width: auto;
        overflow: visible;
        clip: auto;
        position: absolute !important;
        width: 100%; }
      .top-bar-section .has-dropdown.moved > a:after {
        display: none; }
  .top-bar-section .dropdown {
    padding: 0;
    position: absolute;
    left: 100%;
    top: 0;
    z-index: 99;
    display: block;
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
    .top-bar-section .dropdown li {
      width: 100%;
      height: auto; }
      .top-bar-section .dropdown li a {
        font-weight: 400;
        padding: 8px 0.9375rem; }
        .top-bar-section .dropdown li a.parent-link {
          font-weight: 400; }
      .top-bar-section .dropdown li.title h5, .top-bar-section .dropdown li.parent-link {
        margin-bottom: 0;
        margin-top: 0;
        font-size: 1.125rem; }
        .top-bar-section .dropdown li.title h5 a, .top-bar-section .dropdown li.parent-link a {
          color: #FFFFFF;
          display: block; }
          .top-bar-section .dropdown li.title h5 a:hover, .top-bar-section .dropdown li.parent-link a:hover {
            background: none; }
      .top-bar-section .dropdown li.has-form {
        padding: 8px 0.9375rem; }
      .top-bar-section .dropdown li .button, .top-bar-section .dropdown li button {
        top: auto; }
    .top-bar-section .dropdown label {
      padding: 8px 0.9375rem 2px;
      margin-bottom: 0;
      text-transform: uppercase;
      color: #777777;
      font-weight: bold;
      font-size: 0.625rem; }

.js-generated {
  display: block; }

@media only screen and (min-width:40.063em) {
  .top-bar {
    background: #333333;
    overflow: visible; }
    .top-bar:before, .top-bar:after {
      content: " ";
      display: table; }
    .top-bar:after {
      clear: both; }
    .top-bar .toggle-topbar {
      display: none; }
    .top-bar .title-area {
      float: left; }
    .top-bar .name h1 a, .top-bar .name h2 a, .top-bar .name h3 a, .top-bar .name h4 a, .top-bar .name h5 a, .top-bar .name h6 a {
      width: auto; }
    .top-bar input, .top-bar .button, .top-bar button {
      font-size: 0.875rem;
      position: relative;
      height: 1.75rem;
      top: 0.53125rem; }
    .top-bar.expanded {
      background: #333333; }
  .contain-to-grid .top-bar {
    max-width: 68.75rem;
    margin: 0 auto;
    margin-bottom: 0; }
  .top-bar-section {
    transition: none 0 0;
    left: 0 !important; }
    .top-bar-section ul {
      width: auto;
      height: auto !important;
      display: inline; }
      .top-bar-section ul li {
        float: left; }
        .top-bar-section ul li .js-generated {
          display: none; }
    .top-bar-section li.hover > a:not(.button) {
      background-color: #555555;
      background: #333333;
      color: #FFFFFF; }
    .top-bar-section li:not(.has-form) a:not(.button) {
      padding: 0 0.9375rem;
      line-height: 2.8125rem;
      background: #333333; }
      .top-bar-section li:not(.has-form) a:not(.button):hover {
        background-color: #555555;
        background: #333333; }
    .top-bar-section li.active:not(.has-form) a:not(.button) {
      padding: 0 0.9375rem;
      line-height: 2.8125rem;
      color: #FFFFFF;
      background: #1f5c87; }
      .top-bar-section li.active:not(.has-form) a:not(.button):hover {
        background: #db8a00;
        color: #FFFFFF; }
    .top-bar-section .has-dropdown > a {
      padding-right: 2.1875rem !important; }
      .top-bar-section .has-dropdown > a:after {
        content: "";
        display: block;
        width: 0;
        height: 0;
        border: inset 5px;
        border-color: rgba(255, 255, 255, 0.4) transparent transparent transparent;
        border-top-style: solid;
        margin-top: -2.5px;
        top: 1.40625rem; }
    .top-bar-section .has-dropdown.moved {
      position: relative; }
      .top-bar-section .has-dropdown.moved > .dropdown {
        display: block;
        position: absolute !important;
        height: 1px;
        width: 1px;
        overflow: hidden;
        clip: rect(1px, 1px, 1px, 1px); }
    .top-bar-section .has-dropdown.hover > .dropdown, .top-bar-section .has-dropdown.not-click:hover > .dropdown {
      display: block;
      position: static !important;
      height: auto;
      width: auto;
      overflow: visible;
      clip: auto;
      position: absolute !important; }
    .top-bar-section .has-dropdown > a:focus + .dropdown {
      display: block;
      position: static !important;
      height: auto;
      width: auto;
      overflow: visible;
      clip: auto;
      position: absolute !important; }
    .top-bar-section .has-dropdown .dropdown li.has-dropdown > a:after {
      border: none;
      content: "\00bb";
      top: 1rem;
      margin-top: -1px;
      right: 5px;
      line-height: 1.2; }
    .top-bar-section .dropdown {
      left: 0;
      top: auto;
      background: transparent;
      min-width: 100%; }
      .top-bar-section .dropdown li a {
        color: #FFFFFF;
        line-height: 2.8125rem;
        white-space: nowrap;
        padding: 12px 0.9375rem;
        background: #333333; }
      .top-bar-section .dropdown li:not(.has-form):not(.active) > a:not(.button) {
        color: #FFFFFF;
        background: #333333; }
      .top-bar-section .dropdown li:not(.has-form):not(.active):hover > a:not(.button) {
        color: #FFFFFF;
        background-color: #555555;
        background: #333333; }
      .top-bar-section .dropdown li label {
        white-space: nowrap;
        background: #333333; }
      .top-bar-section .dropdown li .dropdown {
        left: 100%;
        top: 0; }
    .top-bar-section > ul > .divider, .top-bar-section > ul > [role="separator"] {
      border-bottom: none;
      border-top: none;
      border-right: solid 1px #4e4e4e;
      clear: none;
      height: 2.8125rem;
      width: 0; }
    .top-bar-section .has-form {
      background: #333333;
      padding: 0 0.9375rem;
      height: 2.8125rem; }
    .top-bar-section .right li .dropdown {
      left: auto;
      right: 0; }
      .top-bar-section .right li .dropdown li .dropdown {
        right: 100%; }
    .top-bar-section .left li .dropdown {
      right: auto;
      left: 0; }
      .top-bar-section .left li .dropdown li .dropdown {
        left: 100%; }
  .no-js .top-bar-section ul li:hover > a {
    background-color: #555555;
    background: #333333;
    color: #FFFFFF; }
  .no-js .top-bar-section ul li:active > a {
    background: #1f5c87;
    color: #FFFFFF; }
  .no-js .top-bar-section .has-dropdown:hover > .dropdown {
    display: block;
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto;
    position: absolute !important; }
  .no-js .top-bar-section .has-dropdown > a:focus + .dropdown {
    display: block;
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto;
    position: absolute !important; } }

.text-left {
  text-align: left !important; }

.text-right {
  text-align: right !important; }

.text-center {
  text-align: center !important; }

.text-justify {
  text-align: justify !important; }

@media only screen and (max-width: 40em) {
  .small-only-text-left {
    text-align: left !important; }
  .small-only-text-right {
    text-align: right !important; }
  .small-only-text-center {
    text-align: center !important; }
  .small-only-text-justify {
    text-align: justify !important; } }

@media only screen {
  .small-text-left {
    text-align: left !important; }
  .small-text-right {
    text-align: right !important; }
  .small-text-center {
    text-align: center !important; }
  .small-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:40.063em) and (max-width:64em) {
  .medium-only-text-left {
    text-align: left !important; }
  .medium-only-text-right {
    text-align: right !important; }
  .medium-only-text-center {
    text-align: center !important; }
  .medium-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:40.063em) {
  .medium-text-left {
    text-align: left !important; }
  .medium-text-right {
    text-align: right !important; }
  .medium-text-center {
    text-align: center !important; }
  .medium-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:64.063em) and (max-width:90em) {
  .large-only-text-left {
    text-align: left !important; }
  .large-only-text-right {
    text-align: right !important; }
  .large-only-text-center {
    text-align: center !important; }
  .large-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:64.063em) {
  .large-text-left {
    text-align: left !important; }
  .large-text-right {
    text-align: right !important; }
  .large-text-center {
    text-align: center !important; }
  .large-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:90.063em) and (max-width:120em) {
  .xlarge-only-text-left {
    text-align: left !important; }
  .xlarge-only-text-right {
    text-align: right !important; }
  .xlarge-only-text-center {
    text-align: center !important; }
  .xlarge-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:90.063em) {
  .xlarge-text-left {
    text-align: left !important; }
  .xlarge-text-right {
    text-align: right !important; }
  .xlarge-text-center {
    text-align: center !important; }
  .xlarge-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:120.063em) and (max-width:99999999em) {
  .xxlarge-only-text-left {
    text-align: left !important; }
  .xxlarge-only-text-right {
    text-align: right !important; }
  .xxlarge-only-text-center {
    text-align: center !important; }
  .xxlarge-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:120.063em) {
  .xxlarge-text-left {
    text-align: left !important; }
  .xxlarge-text-right {
    text-align: right !important; }
  .xxlarge-text-center {
    text-align: center !important; }
  .xxlarge-text-justify {
    text-align: justify !important; } }

/* Typography resets */
div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, p, blockquote, th, td {
  margin: 0;
  padding: 0; }

/* Default Link Styles */
a {
  color: #1f5c87;
  text-decoration: none;
  line-height: inherit; }
  a:hover, a:focus {
    color: #1f5c87; 
    text-decoration: underline;}
  a img {
    border: none; }

/* Default paragraph styles */
p {
  font-family: inherit;
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.6;
  margin-bottom: 1.25rem;
  text-rendering: optimizeLegibility; }
  p.lead {
    font-size: 1.21875rem;
    line-height: 1.6; }
  p aside {
    font-size: 0.875rem;
    line-height: 1.35;
    font-style: italic; }

/* Default header styles */
h1, h2, h3, h4, h5, h6 {
  font-family: arial, sans-serif;
  font-weight: 400;
  font-style: normal;
  color: #222222;
  text-rendering: optimizeLegibility;
  margin-top: 0.2rem;
  margin-bottom: 0.5rem;
  line-height: 1.2; }
  h1 small, h2 small, h3 small, h4 small, h5 small, h6 small {
    font-size: 60%;
    color: #6f6f6f;
    line-height: 0; }

h1 {
  font-size: 2.125rem; }

h2 {
  font-size: 1.6875rem; }

h3 {
  font-size: 1.375rem; }

h4 {
  font-size: 1.125rem; }

h5 {
  font-size: 1.125rem; }

h6 {
  font-size: 1rem; }

.subheader {
  line-height: 1.4;
  color: #6f6f6f;
  font-weight: 400;
  margin-top: 0.2rem;
  margin-bottom: 0.5rem; }

hr {
  border: solid #DDDDDD;
  border-width: 1px 0 0;
  clear: both;
  margin: 1.25rem 0 1.1875rem;
  height: 0; }

/* Helpful Typography Defaults */
em, i {
  font-style: italic;
  line-height: inherit; }

strong, b {
  font-weight: bold;
  line-height: inherit; }

small {
  font-size: 60%;
  line-height: inherit; }

code {
  font-family: Consolas, "Liberation Mono", Courier, monospace;
  font-weight: 400;
  color: #333333;
  background-color: #f8f8f8;
  border-width: 1px;
  border-style: solid;
  border-color: #dfdfdf;
  padding: 0.125rem 0.3125rem 0.0625rem; }

/* Lists */
ul, ol, dl {
  font-size: 1rem;
  line-height: 1.6;
  margin-bottom: 1.25rem;
  list-style-position: outside;
  font-family: inherit; }

ul {
  margin-left: 1.1rem; }
  ul.no-bullet {
    margin-left: 0; }
    ul.no-bullet li ul, ul.no-bullet li ol {
      margin-left: 1.25rem;
      margin-bottom: 0;
      list-style: none; }

/* Unordered Lists */
ul li ul, ul li ol {
  margin-left: 1.25rem;
  margin-bottom: 0; }
ul.square li ul, ul.circle li ul, ul.disc li ul {
  list-style: inherit; }
ul.square {
  list-style-type: square;
  margin-left: 1.1rem; }
ul.circle {
  list-style-type: circle;
  margin-left: 1.1rem; }
ul.disc {
  list-style-type: disc;
  margin-left: 1.1rem; }
ul.no-bullet {
  list-style: none; }

/* Ordered Lists */
ol {
  margin-left: 1.4rem; }
  ol li ul, ol li ol {
    margin-left: 1.25rem;
    margin-bottom: 0; }

/* Definition Lists */
dl dt {
  margin-bottom: 0.3rem;
  font-weight: bold; }
dl dd {
  margin-bottom: 0.75rem; }

/* Abbreviations */
abbr, acronym {
  text-transform: uppercase;
  font-size: 90%;
  color: #565656;
  cursor: help; }

abbr {
  text-transform: none; }
  abbr[title] {
    border-bottom: 1px dotted #DDDDDD; }

/* Blockquotes */
blockquote {
  margin: 0 0 1.25rem;
  padding: 0.5625rem 1.25rem 0 1.1875rem;
  border-left: 1px solid #DDDDDD; }
  blockquote cite {
    display: block;
    font-size: 0.8125rem;
    color: #555555; }
    blockquote cite:before {
      content: "\2014 \0020"; }
    blockquote cite a, blockquote cite a:visited {
      color: #555555; }

blockquote, blockquote p {
  line-height: 1.6;
  color: #6f6f6f; }

/* Microformats */
.vcard {
  display: inline-block;
  margin: 0 0 1.25rem 0;
  border: 1px solid #DDDDDD;
  padding: 0.625rem 0.75rem; }
  .vcard li {
    margin: 0;
    display: block; }
  .vcard .fn {
    font-weight: bold;
    font-size: 0.9375rem; }

.vevent .summary {
  font-weight: bold; }
.vevent abbr {
  cursor: default;
  text-decoration: none;
  font-weight: bold;
  border: none;
  padding: 0 0.0625rem; }

@media only screen and (min-width:40.063em) {
  h1, h2, h3, h4, h5, h6 {
    line-height: 1.2; }
  h1 {
    font-size: 2.75rem; }
  h2 {
    font-size: 2.3125rem; }
  h3 {
    font-size: 1.6875rem; }
  h4 {
    font-size: 1.4375rem; }
  h5 {
    font-size: 1.125rem; }
  h6 {
    font-size: 1rem; } }

.off-canvas-wrap {
  -webkit-backface-visibility: hidden;
  position: relative;
  width: 100%;
  overflow: hidden; }
  .off-canvas-wrap.move-right, .off-canvas-wrap.move-left {
    min-height: 100%;
    -webkit-overflow-scrolling: touch; }

.inner-wrap {
  position: relative;
  width: 100%;
  -webkit-transition: -webkit-transform 500ms ease;
  -moz-transition: -moz-transform 500ms ease;
  -ms-transition: -ms-transform 500ms ease;
  -o-transition: -o-transform 500ms ease;
  transition: transform 500ms ease; }
  .inner-wrap:before, .inner-wrap:after {
    content: " ";
    display: table; }
  .inner-wrap:after {
    clear: both; }

.tab-bar {
  -webkit-backface-visibility: hidden;
  background: #333333;
  color: #FFFFFF;
  height: 2.8125rem;
  line-height: 2.8125rem;
  position: relative; }
  .tab-bar h1, .tab-bar h2, .tab-bar h3, .tab-bar h4, .tab-bar h5, .tab-bar h6 {
    color: #FFFFFF;
    font-weight: bold;
    line-height: 2.8125rem;
    margin: 0; }
  .tab-bar h1, .tab-bar h2, .tab-bar h3, .tab-bar h4 {
    font-size: 1.125rem; }

.left-small {
  width: 2.8125rem;
  height: 2.8125rem;
  position: absolute;
  top: 0;
  border-right: solid 1px #1a1a1a;
  left: 0; }

.right-small {
  width: 2.8125rem;
  height: 2.8125rem;
  position: absolute;
  top: 0;
  border-left: solid 1px #1a1a1a;
  right: 0; }

.tab-bar-section {
  padding: 0 0.625rem;
  position: absolute;
  text-align: center;
  height: 2.8125rem;
  top: 0; }
  @media only screen and (min-width:40.063em) {
    .tab-bar-section.left {
      text-align: left; }
    .tab-bar-section.right {
      text-align: right; } }
  .tab-bar-section.left {
    left: 0;
    right: 2.8125rem; }
  .tab-bar-section.right {
    left: 2.8125rem;
    right: 0; }
  .tab-bar-section.middle {
    left: 2.8125rem;
    right: 2.8125rem; }

.tab-bar .menu-icon {
  text-indent: 2.1875rem;
  width: 2.8125rem;
  height: 2.8125rem;
  display: block;
  padding: 0;
  color: #FFFFFF;
  position: relative;
  transform: translate3d(0, 0, 0); }
  .tab-bar .menu-icon span::after {
    content: "";
    position: absolute;
    display: block;
    height: 0;
    top: 50%;
    margin-top: -0.5rem;
    left: 0.90625rem;
    box-shadow: 0 0 0 1px #FFFFFF, 0 7px 0 1px #FFFFFF, 0 14px 0 1px #FFFFFF;
    width: 1rem; }
  .tab-bar .menu-icon span:hover:after {
    box-shadow: 0 0 0 1px #b3b3b3, 0 7px 0 1px #b3b3b3, 0 14px 0 1px #b3b3b3; }

.left-off-canvas-menu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1001;
  box-sizing: content-box;
  transition: transform 500ms ease 0s;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar;
  -ms-transform: translate(-100%, 0);
  -webkit-transform: translate3d(-100%, 0, 0);
  -moz-transform: translate3d(-100%, 0, 0);
  -ms-transform: translate3d(-100%, 0, 0);
  -o-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
  left: 0; }
  .left-off-canvas-menu * {
    -webkit-backface-visibility: hidden; }

.right-off-canvas-menu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1001;
  box-sizing: content-box;
  transition: transform 500ms ease 0s;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar;
  -ms-transform: translate(100%, 0);
  -webkit-transform: translate3d(100%, 0, 0);
  -moz-transform: translate3d(100%, 0, 0);
  -ms-transform: translate3d(100%, 0, 0);
  -o-transform: translate3d(100%, 0, 0);
  transform: translate3d(100%, 0, 0);
  right: 0; }
  .right-off-canvas-menu * {
    -webkit-backface-visibility: hidden; }

ul.off-canvas-list {
  list-style-type: none;
  padding: 0;
  margin: 0; }
  ul.off-canvas-list li label {
    display: block;
    padding: 0.3rem 0.9375rem;
    color: #999999;
    text-transform: uppercase;
    font-size: 0.75rem;
    font-weight: bold;
    background: #444444;
    border-top: 1px solid #5e5e5e;
    border-bottom: none;
    margin: 0; }
  ul.off-canvas-list li a {
    display: block;
    padding: 0.6666666667rem;
    color: rgba(255, 255, 255, 0.7);
    border-bottom: 1px solid #262626;
    transition: background 300ms ease; }
    ul.off-canvas-list li a:hover {
      background: #242424; }

.move-right > .inner-wrap {
  -ms-transform: translate(15.625rem, 0);
  -webkit-transform: translate3d(15.625rem, 0, 0);
  -moz-transform: translate3d(15.625rem, 0, 0);
  -ms-transform: translate3d(15.625rem, 0, 0);
  -o-transform: translate3d(15.625rem, 0, 0);
  transform: translate3d(15.625rem, 0, 0); }
.move-right .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .move-right .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.move-left > .inner-wrap {
  -ms-transform: translate(-15.625rem, 0);
  -webkit-transform: translate3d(-15.625rem, 0, 0);
  -moz-transform: translate3d(-15.625rem, 0, 0);
  -ms-transform: translate3d(-15.625rem, 0, 0);
  -o-transform: translate3d(-15.625rem, 0, 0);
  transform: translate3d(-15.625rem, 0, 0); }
.move-left .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .move-left .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.offcanvas-overlap .left-off-canvas-menu, .offcanvas-overlap .right-off-canvas-menu {
  -ms-transform: none;
  -webkit-transform: none;
  -moz-transform: none;
  -o-transform: none;
  transform: none;
  z-index: 1003; }
.offcanvas-overlap .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .offcanvas-overlap .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.offcanvas-overlap-left .right-off-canvas-menu {
  -ms-transform: none;
  -webkit-transform: none;
  -moz-transform: none;
  -o-transform: none;
  transform: none;
  z-index: 1003; }
.offcanvas-overlap-left .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .offcanvas-overlap-left .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.offcanvas-overlap-right .left-off-canvas-menu {
  -ms-transform: none;
  -webkit-transform: none;
  -moz-transform: none;
  -o-transform: none;
  transform: none;
  z-index: 1003; }
.offcanvas-overlap-right .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .offcanvas-overlap-right .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.no-csstransforms .left-off-canvas-menu {
  left: -15.625rem; }
.no-csstransforms .right-off-canvas-menu {
  right: -15.625rem; }
.no-csstransforms .move-left > .inner-wrap {
  right: 15.625rem; }
.no-csstransforms .move-right > .inner-wrap {
  left: 15.625rem; }

.left-submenu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  margin: 0;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1002;
  box-sizing: content-box;
  -webkit-overflow-scrolling: touch;
  -ms-transform: translate(-100%, 0);
  -webkit-transform: translate3d(-100%, 0, 0);
  -moz-transform: translate3d(-100%, 0, 0);
  -ms-transform: translate3d(-100%, 0, 0);
  -o-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
  left: 0;
  -webkit-transition: -webkit-transform 500ms ease;
  -moz-transition: -moz-transform 500ms ease;
  -ms-transition: -ms-transform 500ms ease;
  -o-transition: -o-transform 500ms ease;
  transition: transform 500ms ease; }
  .left-submenu * {
    -webkit-backface-visibility: hidden; }
  .left-submenu .back > a {
    padding: 0.3rem 0.9375rem;
    color: #999999;
    text-transform: uppercase;
    font-weight: bold;
    background: #444;
    border-top: 1px solid #5e5e5e;
    border-bottom: none;
    margin: 0; }
    .left-submenu .back > a:hover {
      background: #303030;
      border-top: 1px solid #5e5e5e;
      border-bottom: none; }
    .left-submenu .back > a:before {
      content: "\AB";
      margin-right: 0.5rem;
      display: inline; }
  .left-submenu.move-right, .left-submenu.offcanvas-overlap-right, .left-submenu.offcanvas-overlap {
    -ms-transform: translate(0%, 0);
    -webkit-transform: translate3d(0%, 0, 0);
    -moz-transform: translate3d(0%, 0, 0);
    -ms-transform: translate3d(0%, 0, 0);
    -o-transform: translate3d(0%, 0, 0);
    transform: translate3d(0%, 0, 0); }

.right-submenu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  margin: 0;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1002;
  box-sizing: content-box;
  -webkit-overflow-scrolling: touch;
  -ms-transform: translate(100%, 0);
  -webkit-transform: translate3d(100%, 0, 0);
  -moz-transform: translate3d(100%, 0, 0);
  -ms-transform: translate3d(100%, 0, 0);
  -o-transform: translate3d(100%, 0, 0);
  transform: translate3d(100%, 0, 0);
  right: 0;
  -webkit-transition: -webkit-transform 500ms ease;
  -moz-transition: -moz-transform 500ms ease;
  -ms-transition: -ms-transform 500ms ease;
  -o-transition: -o-transform 500ms ease;
  transition: transform 500ms ease; }
  .right-submenu * {
    -webkit-backface-visibility: hidden; }
  .right-submenu .back > a {
    padding: 0.3rem 0.9375rem;
    color: #999999;
    text-transform: uppercase;
    font-weight: bold;
    background: #444;
    border-top: 1px solid #5e5e5e;
    border-bottom: none;
    margin: 0; }
    .right-submenu .back > a:hover {
      background: #303030;
      border-top: 1px solid #5e5e5e;
      border-bottom: none; }
    .right-submenu .back > a:after {
      content: "\BB";
      margin-left: 0.5rem;
      display: inline; }
  .right-submenu.move-left, .right-submenu.offcanvas-overlap-left, .right-submenu.offcanvas-overlap {
    -ms-transform: translate(0%, 0);
    -webkit-transform: translate3d(0%, 0, 0);
    -moz-transform: translate3d(0%, 0, 0);
    -ms-transform: translate3d(0%, 0, 0);
    -o-transform: translate3d(0%, 0, 0);
    transform: translate3d(0%, 0, 0); }

.left-off-canvas-menu ul.off-canvas-list li.has-submenu > a:after {
  content: "\BB";
  margin-left: 0.5rem;
  display: inline; }

.right-off-canvas-menu ul.off-canvas-list li.has-submenu > a:before {
  content: "\AB";
  margin-right: 0.5rem;
  display: inline; }

/* small displays */
@media only screen {
  .show-for-small-only, .show-for-small-up, .show-for-small, .show-for-small-down, .hide-for-medium-only, .hide-for-medium-up, .hide-for-medium, .show-for-medium-down, .hide-for-large-only, .hide-for-large-up, .hide-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .hide-for-small-only, .hide-for-small-up, .hide-for-small, .hide-for-small-down, .show-for-medium-only, .show-for-medium-up, .show-for-medium, .hide-for-medium-down, .show-for-large-only, .show-for-large-up, .show-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .visible-for-small-only, .visible-for-small-up, .visible-for-small, .visible-for-small-down, .hidden-for-medium-only, .hidden-for-medium-up, .hidden-for-medium, .visible-for-medium-down, .hidden-for-large-only, .hidden-for-large-up, .hidden-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .hidden-for-small-only, .hidden-for-small-up, .hidden-for-small, .hidden-for-small-down, .visible-for-medium-only, .visible-for-medium-up, .visible-for-medium, .hidden-for-medium-down, .visible-for-large-only, .visible-for-large-up, .visible-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.show-for-small-only, table.show-for-small-up, table.show-for-small, table.show-for-small-down, table.hide-for-medium-only, table.hide-for-medium-up, table.hide-for-medium, table.show-for-medium-down, table.hide-for-large-only, table.hide-for-large-up, table.hide-for-large, table.show-for-large-down, table.hide-for-xlarge-only, table.hide-for-xlarge-up, table.hide-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.show-for-small-only, thead.show-for-small-up, thead.show-for-small, thead.show-for-small-down, thead.hide-for-medium-only, thead.hide-for-medium-up, thead.hide-for-medium, thead.show-for-medium-down, thead.hide-for-large-only, thead.hide-for-large-up, thead.hide-for-large, thead.show-for-large-down, thead.hide-for-xlarge-only, thead.hide-for-xlarge-up, thead.hide-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.show-for-small-only, tbody.show-for-small-up, tbody.show-for-small, tbody.show-for-small-down, tbody.hide-for-medium-only, tbody.hide-for-medium-up, tbody.hide-for-medium, tbody.show-for-medium-down, tbody.hide-for-large-only, tbody.hide-for-large-up, tbody.hide-for-large, tbody.show-for-large-down, tbody.hide-for-xlarge-only, tbody.hide-for-xlarge-up, tbody.hide-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.show-for-small-only, tr.show-for-small-up, tr.show-for-small, tr.show-for-small-down, tr.hide-for-medium-only, tr.hide-for-medium-up, tr.hide-for-medium, tr.show-for-medium-down, tr.hide-for-large-only, tr.hide-for-large-up, tr.hide-for-large, tr.show-for-large-down, tr.hide-for-xlarge-only, tr.hide-for-xlarge-up, tr.hide-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.show-for-small-only, td.show-for-small-only, th.show-for-small-up, td.show-for-small-up, th.show-for-small, td.show-for-small, th.show-for-small-down, td.show-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.hide-for-medium-up, td.hide-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.show-for-medium-down, td.show-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.hide-for-large-up, td.hide-for-large-up, th.hide-for-large, td.hide-for-large, th.show-for-large-down, td.show-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.hide-for-xlarge-up, td.hide-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* medium displays */
@media only screen and (min-width:40.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .show-for-medium-only, .show-for-medium-up, .show-for-medium, .show-for-medium-down, .hide-for-large-only, .hide-for-large-up, .hide-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .hide-for-medium-only, .hide-for-medium-up, .hide-for-medium, .hide-for-medium-down, .show-for-large-only, .show-for-large-up, .show-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .visible-for-medium-only, .visible-for-medium-up, .visible-for-medium, .visible-for-medium-down, .hidden-for-large-only, .hidden-for-large-up, .hidden-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .hidden-for-medium-only, .hidden-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .visible-for-large-only, .visible-for-large-up, .visible-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.show-for-medium-only, table.show-for-medium-up, table.show-for-medium, table.show-for-medium-down, table.hide-for-large-only, table.hide-for-large-up, table.hide-for-large, table.show-for-large-down, table.hide-for-xlarge-only, table.hide-for-xlarge-up, table.hide-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.show-for-medium-only, thead.show-for-medium-up, thead.show-for-medium, thead.show-for-medium-down, thead.hide-for-large-only, thead.hide-for-large-up, thead.hide-for-large, thead.show-for-large-down, thead.hide-for-xlarge-only, thead.hide-for-xlarge-up, thead.hide-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.show-for-medium-only, tbody.show-for-medium-up, tbody.show-for-medium, tbody.show-for-medium-down, tbody.hide-for-large-only, tbody.hide-for-large-up, tbody.hide-for-large, tbody.show-for-large-down, tbody.hide-for-xlarge-only, tbody.hide-for-xlarge-up, tbody.hide-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.show-for-medium-only, tr.show-for-medium-up, tr.show-for-medium, tr.show-for-medium-down, tr.hide-for-large-only, tr.hide-for-large-up, tr.hide-for-large, tr.show-for-large-down, tr.hide-for-xlarge-only, tr.hide-for-xlarge-up, tr.hide-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.show-for-medium-only, td.show-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.show-for-medium, td.show-for-medium, th.show-for-medium-down, td.show-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.hide-for-large-up, td.hide-for-large-up, th.hide-for-large, td.hide-for-large, th.show-for-large-down, td.show-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.hide-for-xlarge-up, td.hide-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* large displays */
@media only screen and (min-width:64.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .hide-for-medium-only, .show-for-medium-up, .hide-for-medium, .hide-for-medium-down, .show-for-large-only, .show-for-large-up, .show-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .show-for-medium-only, .hide-for-medium-up, .show-for-medium, .show-for-medium-down, .hide-for-large-only, .hide-for-large-up, .hide-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .hidden-for-medium-only, .visible-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .visible-for-large-only, .visible-for-large-up, .visible-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .visible-for-medium-only, .hidden-for-medium-up, .visible-for-medium, .visible-for-medium-down, .hidden-for-large-only, .hidden-for-large-up, .hidden-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.hide-for-medium-only, table.show-for-medium-up, table.hide-for-medium, table.hide-for-medium-down, table.show-for-large-only, table.show-for-large-up, table.show-for-large, table.show-for-large-down, table.hide-for-xlarge-only, table.hide-for-xlarge-up, table.hide-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.hide-for-medium-only, thead.show-for-medium-up, thead.hide-for-medium, thead.hide-for-medium-down, thead.show-for-large-only, thead.show-for-large-up, thead.show-for-large, thead.show-for-large-down, thead.hide-for-xlarge-only, thead.hide-for-xlarge-up, thead.hide-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.hide-for-medium-only, tbody.show-for-medium-up, tbody.hide-for-medium, tbody.hide-for-medium-down, tbody.show-for-large-only, tbody.show-for-large-up, tbody.show-for-large, tbody.show-for-large-down, tbody.hide-for-xlarge-only, tbody.hide-for-xlarge-up, tbody.hide-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.hide-for-medium-only, tr.show-for-medium-up, tr.hide-for-medium, tr.hide-for-medium-down, tr.show-for-large-only, tr.show-for-large-up, tr.show-for-large, tr.show-for-large-down, tr.hide-for-xlarge-only, tr.hide-for-xlarge-up, tr.hide-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.hide-for-medium-down, td.hide-for-medium-down, th.show-for-large-only, td.show-for-large-only, th.show-for-large-up, td.show-for-large-up, th.show-for-large, td.show-for-large, th.show-for-large-down, td.show-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.hide-for-xlarge-up, td.hide-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* xlarge displays */
@media only screen and (min-width:90.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .hide-for-medium-only, .show-for-medium-up, .hide-for-medium, .hide-for-medium-down, .hide-for-large-only, .show-for-large-up, .hide-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .show-for-medium-only, .hide-for-medium-up, .show-for-medium, .show-for-medium-down, .show-for-large-only, .hide-for-large-up, .show-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .hidden-for-medium-only, .visible-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .hidden-for-large-only, .visible-for-large-up, .hidden-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .visible-for-medium-only, .hidden-for-medium-up, .visible-for-medium, .visible-for-medium-down, .visible-for-large-only, .hidden-for-large-up, .visible-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.hide-for-medium-only, table.show-for-medium-up, table.hide-for-medium, table.hide-for-medium-down, table.hide-for-large-only, table.show-for-large-up, table.hide-for-large, table.hide-for-large-down, table.show-for-xlarge-only, table.show-for-xlarge-up, table.show-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.hide-for-medium-only, thead.show-for-medium-up, thead.hide-for-medium, thead.hide-for-medium-down, thead.hide-for-large-only, thead.show-for-large-up, thead.hide-for-large, thead.hide-for-large-down, thead.show-for-xlarge-only, thead.show-for-xlarge-up, thead.show-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.hide-for-medium-only, tbody.show-for-medium-up, tbody.hide-for-medium, tbody.hide-for-medium-down, tbody.hide-for-large-only, tbody.show-for-large-up, tbody.hide-for-large, tbody.hide-for-large-down, tbody.show-for-xlarge-only, tbody.show-for-xlarge-up, tbody.show-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.hide-for-medium-only, tr.show-for-medium-up, tr.hide-for-medium, tr.hide-for-medium-down, tr.hide-for-large-only, tr.show-for-large-up, tr.hide-for-large, tr.hide-for-large-down, tr.show-for-xlarge-only, tr.show-for-xlarge-up, tr.show-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.hide-for-medium-down, td.hide-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.show-for-large-up, td.show-for-large-up, th.hide-for-large, td.hide-for-large, th.hide-for-large-down, td.hide-for-large-down, th.show-for-xlarge-only, td.show-for-xlarge-only, th.show-for-xlarge-up, td.show-for-xlarge-up, th.show-for-xlarge, td.show-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* xxlarge displays */
@media only screen and (min-width:120.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .hide-for-medium-only, .show-for-medium-up, .hide-for-medium, .hide-for-medium-down, .hide-for-large-only, .show-for-large-up, .hide-for-large, .hide-for-large-down, .hide-for-xlarge-only, .show-for-xlarge-up, .hide-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .show-for-medium-only, .hide-for-medium-up, .show-for-medium, .show-for-medium-down, .show-for-large-only, .hide-for-large-up, .show-for-large, .show-for-large-down, .show-for-xlarge-only, .hide-for-xlarge-up, .show-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .hidden-for-medium-only, .visible-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .hidden-for-large-only, .visible-for-large-up, .hidden-for-large, .hidden-for-large-down, .hidden-for-xlarge-only, .visible-for-xlarge-up, .hidden-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .visible-for-medium-only, .hidden-for-medium-up, .visible-for-medium, .visible-for-medium-down, .visible-for-large-only, .hidden-for-large-up, .visible-for-large, .visible-for-large-down, .visible-for-xlarge-only, .hidden-for-xlarge-up, .visible-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.hide-for-medium-only, table.show-for-medium-up, table.hide-for-medium, table.hide-for-medium-down, table.hide-for-large-only, table.show-for-large-up, table.hide-for-large, table.hide-for-large-down, table.hide-for-xlarge-only, table.show-for-xlarge-up, table.hide-for-xlarge, table.hide-for-xlarge-down, table.show-for-xxlarge-only, table.show-for-xxlarge-up, table.show-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.hide-for-medium-only, thead.show-for-medium-up, thead.hide-for-medium, thead.hide-for-medium-down, thead.hide-for-large-only, thead.show-for-large-up, thead.hide-for-large, thead.hide-for-large-down, thead.hide-for-xlarge-only, thead.show-for-xlarge-up, thead.hide-for-xlarge, thead.hide-for-xlarge-down, thead.show-for-xxlarge-only, thead.show-for-xxlarge-up, thead.show-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.hide-for-medium-only, tbody.show-for-medium-up, tbody.hide-for-medium, tbody.hide-for-medium-down, tbody.hide-for-large-only, tbody.show-for-large-up, tbody.hide-for-large, tbody.hide-for-large-down, tbody.hide-for-xlarge-only, tbody.show-for-xlarge-up, tbody.hide-for-xlarge, tbody.hide-for-xlarge-down, tbody.show-for-xxlarge-only, tbody.show-for-xxlarge-up, tbody.show-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.hide-for-medium-only, tr.show-for-medium-up, tr.hide-for-medium, tr.hide-for-medium-down, tr.hide-for-large-only, tr.show-for-large-up, tr.hide-for-large, tr.hide-for-large-down, tr.hide-for-xlarge-only, tr.show-for-xlarge-up, tr.hide-for-xlarge, tr.hide-for-xlarge-down, tr.show-for-xxlarge-only, tr.show-for-xxlarge-up, tr.show-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.hide-for-medium-down, td.hide-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.show-for-large-up, td.show-for-large-up, th.hide-for-large, td.hide-for-large, th.hide-for-large-down, td.hide-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.show-for-xlarge-up, td.show-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.hide-for-xlarge-down, td.hide-for-xlarge-down, th.show-for-xxlarge-only, td.show-for-xxlarge-only, th.show-for-xxlarge-up, td.show-for-xxlarge-up, th.show-for-xxlarge, td.show-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* Orientation targeting */
.show-for-landscape, .hide-for-portrait {
  display: inherit !important; }

.hide-for-landscape, .show-for-portrait {
  display: none !important; }

/* Specific visibility for tables */
table.hide-for-landscape, table.show-for-portrait {
  display: table !important; }

thead.hide-for-landscape, thead.show-for-portrait {
  display: table-header-group !important; }

tbody.hide-for-landscape, tbody.show-for-portrait {
  display: table-row-group !important; }

tr.hide-for-landscape, tr.show-for-portrait {
  display: table-row !important; }

td.hide-for-landscape, td.show-for-portrait, th.hide-for-landscape, th.show-for-portrait {
  display: table-cell !important; }

@media only screen and (orientation: landscape) {
  .show-for-landscape, .hide-for-portrait {
    display: inherit !important; }
  .hide-for-landscape, .show-for-portrait {
    display: none !important; }
  /* Specific visibility for tables */
  table.show-for-landscape, table.hide-for-portrait {
    display: table !important; }
  thead.show-for-landscape, thead.hide-for-portrait {
    display: table-header-group !important; }
  tbody.show-for-landscape, tbody.hide-for-portrait {
    display: table-row-group !important; }
  tr.show-for-landscape, tr.hide-for-portrait {
    display: table-row !important; }
  td.show-for-landscape, td.hide-for-portrait, th.show-for-landscape, th.hide-for-portrait {
    display: table-cell !important; } }

@media only screen and (orientation: portrait) {
  .show-for-portrait, .hide-for-landscape {
    display: inherit !important; }
  .hide-for-portrait, .show-for-landscape {
    display: none !important; }
  /* Specific visibility for tables */
  table.show-for-portrait, table.hide-for-landscape {
    display: table !important; }
  thead.show-for-portrait, thead.hide-for-landscape {
    display: table-header-group !important; }
  tbody.show-for-portrait, tbody.hide-for-landscape {
    display: table-row-group !important; }
  tr.show-for-portrait, tr.hide-for-landscape {
    display: table-row !important; }
  td.show-for-portrait, td.hide-for-landscape, th.show-for-portrait, th.hide-for-landscape {
    display: table-cell !important; } }

/* Touch-enabled device targeting */
.show-for-touch {
  display: none !important; }

.hide-for-touch {
  display: inherit !important; }

.touch .show-for-touch {
  display: inherit !important; }

.touch .hide-for-touch {
  display: none !important; }

/* Specific visibility for tables */
table.hide-for-touch {
  display: table !important; }

.touch table.show-for-touch {
  display: table !important; }

thead.hide-for-touch {
  display: table-header-group !important; }

.touch thead.show-for-touch {
  display: table-header-group !important; }

tbody.hide-for-touch {
  display: table-row-group !important; }

.touch tbody.show-for-touch {
  display: table-row-group !important; }

tr.hide-for-touch {
  display: table-row !important; }

.touch tr.show-for-touch {
  display: table-row !important; }

td.hide-for-touch {
  display: table-cell !important; }

.touch td.show-for-touch {
  display: table-cell !important; }

th.hide-for-touch {
  display: table-cell !important; }

.touch th.show-for-touch {
  display: table-cell !important; }

/*
       * Print styles.
       *
       * Inlined to avoid required HTTP connection: www.phpied.com/delay-loading-your-print-css/
       * Credit to Paul Irish and HTML5 Boilerplate (html5boilerplate.com)
      */
.print-only {
  display: none !important; }

@media print {
  * {
    background: transparent !important;
    color: #000000 !important;
    /* Black prints faster: h5bp.com/s */
    box-shadow: none !important;
    text-shadow: none !important; }
  .show-for-print {
    display: block; }
  .hide-for-print {
    display: none; }
  table.show-for-print {
    display: table !important; }
  thead.show-for-print {
    display: table-header-group !important; }
  tbody.show-for-print {
    display: table-row-group !important; }
  tr.show-for-print {
    display: table-row !important; }
  td.show-for-print {
    display: table-cell !important; }
  th.show-for-print {
    display: table-cell !important; }
  a, a:visited {
    text-decoration: underline; }
  a[href]:after {
    content: " (" attr(href) ")"; }
  abbr[title]:after {
    content: " (" attr(title) ")"; }
  .ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after {
    content: ""; }
  pre, blockquote {
    border: 1px solid #999999;
    page-break-inside: avoid; }
  thead {
    display: table-header-group;
    /* h5bp.com/t */ }
  tr, img {
    page-break-inside: avoid; }
  img {
    max-width: 100% !important; }
  @page {
    margin: 0.5cm; }

  p, h2, h3 {
    orphans: 3;
    widows: 3; }
  h2, h3 {
    page-break-after: avoid; }
  .hide-on-print {
    display: none !important; }
  .print-only {
    display: block !important; }
  .hide-for-print {
    display: none !important; }
  .show-for-print {
    display: inherit !important; } }

/* Print visibility */
@media print {
  .show-for-print {
    display: block; }
  .hide-for-print {
    display: none; }
  table.show-for-print {
    display: table !important; }
  thead.show-for-print {
    display: table-header-group !important; }
  tbody.show-for-print {
    display: table-row-group !important; }
  tr.show-for-print {
    display: table-row !important; }
  td.show-for-print {
    display: table-cell !important; }
  th.show-for-print {
    display: table-cell !important; } }

/* 
  Font Awesome - (http://fontawesome.io/) :
  Feel free to remove the import statement below if you don't plan to use icon-fonts in your project
*/
/*!
 *  Font Awesome 4.3.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('./assets/fontawesome/fonts/fontawesome-webfont.eot?v=4.3.0');
  src: url('./assets/fontawesome/fonts/fontawesome-webfont.eot?#iefix&v=4.3.0') format('embedded-opentype'), url('./assets/fontawesome/fonts/fontawesome-webfont.woff2?v=4.3.0') format('woff2'), url('./assets/fontawesome/fonts/fontawesome-webfont.woff?v=4.3.0') format('woff'), url('./assets/fontawesome/fonts/fontawesome-webfont.ttf?v=4.3.0') format('truetype'), url('./assets/fontawesome/fonts/fontawesome-webfont.svg?v=4.3.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal; }

.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  transform: translate(0, 0); }

/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.3333333333em;
  line-height: 0.75em;
  vertical-align: -15%; }

.fa-2x {
  font-size: 2em; }

.fa-3x {
  font-size: 3em; }

.fa-4x {
  font-size: 4em; }

.fa-5x {
  font-size: 5em; }

.fa-fw {
  width: 1.2857142857em;
  text-align: center; }

.fa-ul {
  padding-left: 0;
  margin-left: 2.1428571429em;
  list-style-type: none; }
  .fa-ul > li {
    position: relative; }

.fa-li {
  position: absolute;
  left: -2.1428571429em;
  width: 2.1428571429em;
  top: 0.1428571429em;
  text-align: center; }
  .fa-li.fa-lg {
    left: -1.8571428571em; }

.fa-border {
  padding: .2em .25em .15em;
  border: solid .08em #eee;
  border-radius: .1em; }

.pull-right {
  float: right; }

.pull-left {
  float: left; }

.fa.pull-left {
  margin-right: .3em; }
.fa.pull-right {
  margin-left: .3em; }

.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear; }

.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8); }

@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg); }

  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg); } }

@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg); }

  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg); } }

.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg); }

.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg); }

.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg); }

.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1); }

.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1); }

:root .fa-rotate-90, :root .fa-rotate-180, :root .fa-rotate-270, :root .fa-flip-horizontal, :root .fa-flip-vertical {
  filter: none; }

.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle; }

.fa-stack-1x, .fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center; }

.fa-stack-1x {
  line-height: inherit; }

.fa-stack-2x {
  font-size: 2em; }

.fa-inverse {
  color: #fff; }

/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000"; }

.fa-music:before {
  content: "\f001"; }

.fa-search:before {
  content: "\f002"; }

.fa-envelope-o:before {
  content: "\f003"; }

.fa-heart:before {
  content: "\f004"; }

.fa-star:before {
  content: "\f005"; }

.fa-star-o:before {
  content: "\f006"; }

.fa-user:before {
  content: "\f007"; }

.fa-film:before {
  content: "\f008"; }

.fa-th-large:before {
  content: "\f009"; }

.fa-th:before {
  content: "\f00a"; }

.fa-th-list:before {
  content: "\f00b"; }

.fa-check:before {
  content: "\f00c"; }

.fa-remove:before, .fa-close:before, .fa-times:before {
  content: "\f00d"; }

.fa-search-plus:before {
  content: "\f00e"; }

.fa-search-minus:before {
  content: "\f010"; }

.fa-power-off:before {
  content: "\f011"; }

.fa-signal:before {
  content: "\f012"; }

.fa-gear:before, .fa-cog:before {
  content: "\f013"; }

.fa-trash-o:before {
  content: "\f014"; }

.fa-home:before {
  content: "\f015"; }

.fa-file-o:before {
  content: "\f016"; }

.fa-clock-o:before {
  content: "\f017"; }

.fa-road:before {
  content: "\f018"; }

.fa-download:before {
  content: "\f019"; }

.fa-arrow-circle-o-down:before {
  content: "\f01a"; }

.fa-arrow-circle-o-up:before {
  content: "\f01b"; }

.fa-inbox:before {
  content: "\f01c"; }

.fa-play-circle-o:before {
  content: "\f01d"; }

.fa-rotate-right:before, .fa-repeat:before {
  content: "\f01e"; }

.fa-refresh:before {
  content: "\f021"; }

.fa-list-alt:before {
  content: "\f022"; }

.fa-lock:before {
  content: "\f023"; }

.fa-flag:before {
  content: "\f024"; }

.fa-headphones:before {
  content: "\f025"; }

.fa-volume-off:before {
  content: "\f026"; }

.fa-volume-down:before {
  content: "\f027"; }

.fa-volume-up:before {
  content: "\f028"; }

.fa-qrcode:before {
  content: "\f029"; }

.fa-barcode:before {
  content: "\f02a"; }

.fa-tag:before {
  content: "\f02b"; }

.fa-tags:before {
  content: "\f02c"; }

.fa-book:before {
  content: "\f02d"; }

.fa-bookmark:before {
  content: "\f02e"; }

.fa-print:before {
  content: "\f02f"; }

.fa-camera:before {
  content: "\f030"; }

.fa-font:before {
  content: "\f031"; }

.fa-bold:before {
  content: "\f032"; }

.fa-italic:before {
  content: "\f033"; }

.fa-text-height:before {
  content: "\f034"; }

.fa-text-width:before {
  content: "\f035"; }

.fa-align-left:before {
  content: "\f036"; }

.fa-align-center:before {
  content: "\f037"; }

.fa-align-right:before {
  content: "\f038"; }

.fa-align-justify:before {
  content: "\f039"; }

.fa-list:before {
  content: "\f03a"; }

.fa-dedent:before, .fa-outdent:before {
  content: "\f03b"; }

.fa-indent:before {
  content: "\f03c"; }

.fa-video-camera:before {
  content: "\f03d"; }

.fa-photo:before, .fa-image:before, .fa-picture-o:before {
  content: "\f03e"; }

.fa-pencil:before {
  content: "\f040"; }

.fa-map-marker:before {
  content: "\f041"; }

.fa-adjust:before {
  content: "\f042"; }

.fa-tint:before {
  content: "\f043"; }

.fa-edit:before, .fa-pencil-square-o:before {
  content: "\f044"; }

.fa-share-square-o:before {
  content: "\f045"; }

.fa-check-square-o:before {
  content: "\f046"; }

.fa-arrows:before {
  content: "\f047"; }

.fa-step-backward:before {
  content: "\f048"; }

.fa-fast-backward:before {
  content: "\f049"; }

.fa-backward:before {
  content: "\f04a"; }

.fa-play:before {
  content: "\f04b"; }

.fa-pause:before {
  content: "\f04c"; }

.fa-stop:before {
  content: "\f04d"; }

.fa-forward:before {
  content: "\f04e"; }

.fa-fast-forward:before {
  content: "\f050"; }

.fa-step-forward:before {
  content: "\f051"; }

.fa-eject:before {
  content: "\f052"; }

.fa-chevron-left:before {
  content: "\f053"; }

.fa-chevron-right:before {
  content: "\f054"; }

.fa-plus-circle:before {
  content: "\f055"; }

.fa-minus-circle:before {
  content: "\f056"; }

.fa-times-circle:before {
  content: "\f057"; }

.fa-check-circle:before {
  content: "\f058"; }

.fa-question-circle:before {
  content: "\f059"; }

.fa-info-circle:before {
  content: "\f05a"; }

.fa-crosshairs:before {
  content: "\f05b"; }

.fa-times-circle-o:before {
  content: "\f05c"; }

.fa-check-circle-o:before {
  content: "\f05d"; }

.fa-ban:before {
  content: "\f05e"; }

.fa-arrow-left:before {
  content: "\f060"; }

.fa-arrow-right:before {
  content: "\f061"; }

.fa-arrow-up:before {
  content: "\f062"; }

.fa-arrow-down:before {
  content: "\f063"; }

.fa-mail-forward:before, .fa-share:before {
  content: "\f064"; }

.fa-expand:before {
  content: "\f065"; }

.fa-compress:before {
  content: "\f066"; }

.fa-plus:before {
  content: "\f067"; }

.fa-minus:before {
  content: "\f068"; }

.fa-asterisk:before {
  content: "\f069"; }

.fa-exclamation-circle:before {
  content: "\f06a"; }

.fa-gift:before {
  content: "\f06b"; }

.fa-leaf:before {
  content: "\f06c"; }

.fa-fire:before {
  content: "\f06d"; }

.fa-eye:before {
  content: "\f06e"; }

.fa-eye-slash:before {
  content: "\f070"; }

.fa-warning:before, .fa-exclamation-triangle:before {
  content: "\f071"; }

.fa-plane:before {
  content: "\f072"; }

.fa-calendar:before {
  content: "\f073"; }

.fa-random:before {
  content: "\f074"; }

.fa-comment:before {
  content: "\f075"; }

.fa-magnet:before {
  content: "\f076"; }

.fa-chevron-up:before {
  content: "\f077"; }

.fa-chevron-down:before {
  content: "\f078"; }

.fa-retweet:before {
  content: "\f079"; }

.fa-shopping-cart:before {
  content: "\f07a"; }

.fa-folder:before {
  content: "\f07b"; }

.fa-folder-open:before {
  content: "\f07c"; }

.fa-arrows-v:before {
  content: "\f07d"; }

.fa-arrows-h:before {
  content: "\f07e"; }

.fa-bar-chart-o:before, .fa-bar-chart:before {
  content: "\f080"; }

.fa-twitter-square:before {
  content: "\f081"; }

.fa-facebook-square:before {
  content: "\f082"; }

.fa-camera-retro:before {
  content: "\f083"; }

.fa-key:before {
  content: "\f084"; }

.fa-gears:before, .fa-cogs:before {
  content: "\f085"; }

.fa-comments:before {
  content: "\f086"; }

.fa-thumbs-o-up:before {
  content: "\f087"; }

.fa-thumbs-o-down:before {
  content: "\f088"; }

.fa-star-half:before {
  content: "\f089"; }

.fa-heart-o:before {
  content: "\f08a"; }

.fa-sign-out:before {
  content: "\f08b"; }

.fa-linkedin-square:before {
  content: "\f08c"; }

.fa-thumb-tack:before {
  content: "\f08d"; }

.fa-external-link:before {
  content: "\f08e"; }

.fa-sign-in:before {
  content: "\f090"; }

.fa-trophy:before {
  content: "\f091"; }

.fa-github-square:before {
  content: "\f092"; }

.fa-upload:before {
  content: "\f093"; }

.fa-lemon-o:before {
  content: "\f094"; }

.fa-phone:before {
  content: "\f095"; }

.fa-square-o:before {
  content: "\f096"; }

.fa-bookmark-o:before {
  content: "\f097"; }

.fa-phone-square:before {
  content: "\f098"; }

.fa-twitter:before {
  content: "\f099"; }

.fa-facebook-f:before, .fa-facebook:before {
  content: "\f09a"; }

.fa-github:before {
  content: "\f09b"; }

.fa-unlock:before {
  content: "\f09c"; }

.fa-credit-card:before {
  content: "\f09d"; }

.fa-rss:before {
  content: "\f09e"; }

.fa-hdd-o:before {
  content: "\f0a0"; }

.fa-bullhorn:before {
  content: "\f0a1"; }

.fa-bell:before {
  content: "\f0f3"; }

.fa-certificate:before {
  content: "\f0a3"; }

.fa-hand-o-right:before {
  content: "\f0a4"; }

.fa-hand-o-left:before {
  content: "\f0a5"; }

.fa-hand-o-up:before {
  content: "\f0a6"; }

.fa-hand-o-down:before {
  content: "\f0a7"; }

.fa-arrow-circle-left:before {
  content: "\f0a8"; }

.fa-arrow-circle-right:before {
  content: "\f0a9"; }

.fa-arrow-circle-up:before {
  content: "\f0aa"; }

.fa-arrow-circle-down:before {
  content: "\f0ab"; }

.fa-globe:before {
  content: "\f0ac"; }

.fa-wrench:before {
  content: "\f0ad"; }

.fa-tasks:before {
  content: "\f0ae"; }

.fa-filter:before {
  content: "\f0b0"; }

.fa-briefcase:before {
  content: "\f0b1"; }

.fa-arrows-alt:before {
  content: "\f0b2"; }

.fa-group:before, .fa-users:before {
  content: "\f0c0"; }

.fa-chain:before, .fa-link:before {
  content: "\f0c1"; }

.fa-cloud:before {
  content: "\f0c2"; }

.fa-flask:before {
  content: "\f0c3"; }

.fa-cut:before, .fa-scissors:before {
  content: "\f0c4"; }

.fa-copy:before, .fa-files-o:before {
  content: "\f0c5"; }

.fa-paperclip:before {
  content: "\f0c6"; }

.fa-save:before, .fa-floppy-o:before {
  content: "\f0c7"; }

.fa-square:before {
  content: "\f0c8"; }

.fa-navicon:before, .fa-reorder:before, .fa-bars:before {
  content: "\f0c9"; }

.fa-list-ul:before {
  content: "\f0ca"; }

.fa-list-ol:before {
  content: "\f0cb"; }

.fa-strikethrough:before {
  content: "\f0cc"; }

.fa-underline:before {
  content: "\f0cd"; }

.fa-table:before {
  content: "\f0ce"; }

.fa-magic:before {
  content: "\f0d0"; }

.fa-truck:before {
  content: "\f0d1"; }

.fa-pinterest:before {
  content: "\f0d2"; }

.fa-pinterest-square:before {
  content: "\f0d3"; }

.fa-google-plus-square:before {
  content: "\f0d4"; }

.fa-google-plus:before {
  content: "\f0d5"; }

.fa-money:before {
  content: "\f0d6"; }

.fa-caret-down:before {
  content: "\f0d7"; }

.fa-caret-up:before {
  content: "\f0d8"; }

.fa-caret-left:before {
  content: "\f0d9"; }

.fa-caret-right:before {
  content: "\f0da"; }

.fa-columns:before {
  content: "\f0db"; }

.fa-unsorted:before, .fa-sort:before {
  content: "\f0dc"; }

.fa-sort-down:before, .fa-sort-desc:before {
  content: "\f0dd"; }

.fa-sort-up:before, .fa-sort-asc:before {
  content: "\f0de"; }

.fa-envelope:before {
  content: "\f0e0"; }

.fa-linkedin:before {
  content: "\f0e1"; }

.fa-rotate-left:before, .fa-undo:before {
  content: "\f0e2"; }

.fa-legal:before, .fa-gavel:before {
  content: "\f0e3"; }

.fa-dashboard:before, .fa-tachometer:before {
  content: "\f0e4"; }

.fa-comment-o:before {
  content: "\f0e5"; }

.fa-comments-o:before {
  content: "\f0e6"; }

.fa-flash:before, .fa-bolt:before {
  content: "\f0e7"; }

.fa-sitemap:before {
  content: "\f0e8"; }

.fa-umbrella:before {
  content: "\f0e9"; }

.fa-paste:before, .fa-clipboard:before {
  content: "\f0ea"; }

.fa-lightbulb-o:before {
  content: "\f0eb"; }

.fa-exchange:before {
  content: "\f0ec"; }

.fa-cloud-download:before {
  content: "\f0ed"; }

.fa-cloud-upload:before {
  content: "\f0ee"; }

.fa-user-md:before {
  content: "\f0f0"; }

.fa-stethoscope:before {
  content: "\f0f1"; }

.fa-suitcase:before {
  content: "\f0f2"; }

.fa-bell-o:before {
  content: "\f0a2"; }

.fa-coffee:before {
  content: "\f0f4"; }

.fa-cutlery:before {
  content: "\f0f5"; }

.fa-file-text-o:before {
  content: "\f0f6"; }

.fa-building-o:before {
  content: "\f0f7"; }

.fa-hospital-o:before {
  content: "\f0f8"; }

.fa-ambulance:before {
  content: "\f0f9"; }

.fa-medkit:before {
  content: "\f0fa"; }

.fa-fighter-jet:before {
  content: "\f0fb"; }

.fa-beer:before {
  content: "\f0fc"; }

.fa-h-square:before {
  content: "\f0fd"; }

.fa-plus-square:before {
  content: "\f0fe"; }

.fa-angle-double-left:before {
  content: "\f100"; }

.fa-angle-double-right:before {
  content: "\f101"; }

.fa-angle-double-up:before {
  content: "\f102"; }

.fa-angle-double-down:before {
  content: "\f103"; }

.fa-angle-left:before {
  content: "\f104"; }

.fa-angle-right:before {
  content: "\f105"; }

.fa-angle-up:before {
  content: "\f106"; }

.fa-angle-down:before {
  content: "\f107"; }

.fa-desktop:before {
  content: "\f108"; }

.fa-laptop:before {
  content: "\f109"; }

.fa-tablet:before {
  content: "\f10a"; }

.fa-mobile-phone:before, .fa-mobile:before {
  content: "\f10b"; }

.fa-circle-o:before {
  content: "\f10c"; }

.fa-quote-left:before {
  content: "\f10d"; }

.fa-quote-right:before {
  content: "\f10e"; }

.fa-spinner:before {
  content: "\f110"; }

.fa-circle:before {
  content: "\f111"; }

.fa-mail-reply:before, .fa-reply:before {
  content: "\f112"; }

.fa-github-alt:before {
  content: "\f113"; }

.fa-folder-o:before {
  content: "\f114"; }

.fa-folder-open-o:before {
  content: "\f115"; }

.fa-smile-o:before {
  content: "\f118"; }

.fa-frown-o:before {
  content: "\f119"; }

.fa-meh-o:before {
  content: "\f11a"; }

.fa-gamepad:before {
  content: "\f11b"; }

.fa-keyboard-o:before {
  content: "\f11c"; }

.fa-flag-o:before {
  content: "\f11d"; }

.fa-flag-checkered:before {
  content: "\f11e"; }

.fa-terminal:before {
  content: "\f120"; }

.fa-code:before {
  content: "\f121"; }

.fa-mail-reply-all:before, .fa-reply-all:before {
  content: "\f122"; }

.fa-star-half-empty:before, .fa-star-half-full:before, .fa-star-half-o:before {
  content: "\f123"; }

.fa-location-arrow:before {
  content: "\f124"; }

.fa-crop:before {
  content: "\f125"; }

.fa-code-fork:before {
  content: "\f126"; }

.fa-unlink:before, .fa-chain-broken:before {
  content: "\f127"; }

.fa-question:before {
  content: "\f128"; }

.fa-info:before {
  content: "\f129"; }

.fa-exclamation:before {
  content: "\f12a"; }

.fa-superscript:before {
  content: "\f12b"; }

.fa-subscript:before {
  content: "\f12c"; }

.fa-eraser:before {
  content: "\f12d"; }

.fa-puzzle-piece:before {
  content: "\f12e"; }

.fa-microphone:before {
  content: "\f130"; }

.fa-microphone-slash:before {
  content: "\f131"; }

.fa-shield:before {
  content: "\f132"; }

.fa-calendar-o:before {
  content: "\f133"; }

.fa-fire-extinguisher:before {
  content: "\f134"; }

.fa-rocket:before {
  content: "\f135"; }

.fa-maxcdn:before {
  content: "\f136"; }

.fa-chevron-circle-left:before {
  content: "\f137"; }

.fa-chevron-circle-right:before {
  content: "\f138"; }

.fa-chevron-circle-up:before {
  content: "\f139"; }

.fa-chevron-circle-down:before {
  content: "\f13a"; }

.fa-html5:before {
  content: "\f13b"; }

.fa-css3:before {
  content: "\f13c"; }

.fa-anchor:before {
  content: "\f13d"; }

.fa-unlock-alt:before {
  content: "\f13e"; }

.fa-bullseye:before {
  content: "\f140"; }

.fa-ellipsis-h:before {
  content: "\f141"; }

.fa-ellipsis-v:before {
  content: "\f142"; }

.fa-rss-square:before {
  content: "\f143"; }

.fa-play-circle:before {
  content: "\f144"; }

.fa-ticket:before {
  content: "\f145"; }

.fa-minus-square:before {
  content: "\f146"; }

.fa-minus-square-o:before {
  content: "\f147"; }

.fa-level-up:before {
  content: "\f148"; }

.fa-level-down:before {
  content: "\f149"; }

.fa-check-square:before {
  content: "\f14a"; }

.fa-pencil-square:before {
  content: "\f14b"; }

.fa-external-link-square:before {
  content: "\f14c"; }

.fa-share-square:before {
  content: "\f14d"; }

.fa-compass:before {
  content: "\f14e"; }

.fa-toggle-down:before, .fa-caret-square-o-down:before {
  content: "\f150"; }

.fa-toggle-up:before, .fa-caret-square-o-up:before {
  content: "\f151"; }

.fa-toggle-right:before, .fa-caret-square-o-right:before {
  content: "\f152"; }

.fa-euro:before, .fa-eur:before {
  content: "\f153"; }

.fa-gbp:before {
  content: "\f154"; }

.fa-dollar:before, .fa-usd:before {
  content: "\f155"; }

.fa-rupee:before, .fa-inr:before {
  content: "\f156"; }

.fa-cny:before, .fa-rmb:before, .fa-yen:before, .fa-jpy:before {
  content: "\f157"; }

.fa-ruble:before, .fa-rouble:before, .fa-rub:before {
  content: "\f158"; }

.fa-won:before, .fa-krw:before {
  content: "\f159"; }

.fa-bitcoin:before, .fa-btc:before {
  content: "\f15a"; }

.fa-file:before {
  content: "\f15b"; }

.fa-file-text:before {
  content: "\f15c"; }

.fa-sort-alpha-asc:before {
  content: "\f15d"; }

.fa-sort-alpha-desc:before {
  content: "\f15e"; }

.fa-sort-amount-asc:before {
  content: "\f160"; }

.fa-sort-amount-desc:before {
  content: "\f161"; }

.fa-sort-numeric-asc:before {
  content: "\f162"; }

.fa-sort-numeric-desc:before {
  content: "\f163"; }

.fa-thumbs-up:before {
  content: "\f164"; }

.fa-thumbs-down:before {
  content: "\f165"; }

.fa-youtube-square:before {
  content: "\f166"; }

.fa-youtube:before {
  content: "\f167"; }

.fa-xing:before {
  content: "\f168"; }

.fa-xing-square:before {
  content: "\f169"; }

.fa-youtube-play:before {
  content: "\f16a"; }

.fa-dropbox:before {
  content: "\f16b"; }

.fa-stack-overflow:before {
  content: "\f16c"; }

.fa-instagram:before {
  content: "\f16d"; }

.fa-flickr:before {
  content: "\f16e"; }

.fa-adn:before {
  content: "\f170"; }

.fa-bitbucket:before {
  content: "\f171"; }

.fa-bitbucket-square:before {
  content: "\f172"; }

.fa-tumblr:before {
  content: "\f173"; }

.fa-tumblr-square:before {
  content: "\f174"; }

.fa-long-arrow-down:before {
  content: "\f175"; }

.fa-long-arrow-up:before {
  content: "\f176"; }

.fa-long-arrow-left:before {
  content: "\f177"; }

.fa-long-arrow-right:before {
  content: "\f178"; }

.fa-apple:before {
  content: "\f179"; }

.fa-windows:before {
  content: "\f17a"; }

.fa-android:before {
  content: "\f17b"; }

.fa-linux:before {
  content: "\f17c"; }

.fa-dribbble:before {
  content: "\f17d"; }

.fa-skype:before {
  content: "\f17e"; }

.fa-foursquare:before {
  content: "\f180"; }

.fa-trello:before {
  content: "\f181"; }

.fa-female:before {
  content: "\f182"; }

.fa-male:before {
  content: "\f183"; }

.fa-gittip:before, .fa-gratipay:before {
  content: "\f184"; }

.fa-sun-o:before {
  content: "\f185"; }

.fa-moon-o:before {
  content: "\f186"; }

.fa-archive:before {
  content: "\f187"; }

.fa-bug:before {
  content: "\f188"; }

.fa-vk:before {
  content: "\f189"; }

.fa-weibo:before {
  content: "\f18a"; }

.fa-renren:before {
  content: "\f18b"; }

.fa-pagelines:before {
  content: "\f18c"; }

.fa-stack-exchange:before {
  content: "\f18d"; }

.fa-arrow-circle-o-right:before {
  content: "\f18e"; }

.fa-arrow-circle-o-left:before {
  content: "\f190"; }

.fa-toggle-left:before, .fa-caret-square-o-left:before {
  content: "\f191"; }

.fa-dot-circle-o:before {
  content: "\f192"; }

.fa-wheelchair:before {
  content: "\f193"; }

.fa-vimeo-square:before {
  content: "\f194"; }

.fa-turkish-lira:before, .fa-try:before {
  content: "\f195"; }

.fa-plus-square-o:before {
  content: "\f196"; }

.fa-space-shuttle:before {
  content: "\f197"; }

.fa-slack:before {
  content: "\f198"; }

.fa-envelope-square:before {
  content: "\f199"; }

.fa-wordpress:before {
  content: "\f19a"; }

.fa-openid:before {
  content: "\f19b"; }

.fa-institution:before, .fa-bank:before, .fa-university:before {
  content: "\f19c"; }

.fa-mortar-board:before, .fa-graduation-cap:before {
  content: "\f19d"; }

.fa-yahoo:before {
  content: "\f19e"; }

.fa-google:before {
  content: "\f1a0"; }

.fa-reddit:before {
  content: "\f1a1"; }

.fa-reddit-square:before {
  content: "\f1a2"; }

.fa-stumbleupon-circle:before {
  content: "\f1a3"; }

.fa-stumbleupon:before {
  content: "\f1a4"; }

.fa-delicious:before {
  content: "\f1a5"; }

.fa-digg:before {
  content: "\f1a6"; }

.fa-pied-piper:before {
  content: "\f1a7"; }

.fa-pied-piper-alt:before {
  content: "\f1a8"; }

.fa-drupal:before {
  content: "\f1a9"; }

.fa-joomla:before {
  content: "\f1aa"; }

.fa-language:before {
  content: "\f1ab"; }

.fa-fax:before {
  content: "\f1ac"; }

.fa-building:before {
  content: "\f1ad"; }

.fa-child:before {
  content: "\f1ae"; }

.fa-paw:before {
  content: "\f1b0"; }

.fa-spoon:before {
  content: "\f1b1"; }

.fa-cube:before {
  content: "\f1b2"; }

.fa-cubes:before {
  content: "\f1b3"; }

.fa-behance:before {
  content: "\f1b4"; }

.fa-behance-square:before {
  content: "\f1b5"; }

.fa-steam:before {
  content: "\f1b6"; }

.fa-steam-square:before {
  content: "\f1b7"; }

.fa-recycle:before {
  content: "\f1b8"; }

.fa-automobile:before, .fa-car:before {
  content: "\f1b9"; }

.fa-cab:before, .fa-taxi:before {
  content: "\f1ba"; }

.fa-tree:before {
  content: "\f1bb"; }

.fa-spotify:before {
  content: "\f1bc"; }

.fa-deviantart:before {
  content: "\f1bd"; }

.fa-soundcloud:before {
  content: "\f1be"; }

.fa-database:before {
  content: "\f1c0"; }

.fa-file-pdf-o:before {
  content: "\f1c1"; }

.fa-file-word-o:before {
  content: "\f1c2"; }

.fa-file-excel-o:before {
  content: "\f1c3"; }

.fa-file-powerpoint-o:before {
  content: "\f1c4"; }

.fa-file-photo-o:before, .fa-file-picture-o:before, .fa-file-image-o:before {
  content: "\f1c5"; }

.fa-file-zip-o:before, .fa-file-archive-o:before {
  content: "\f1c6"; }

.fa-file-sound-o:before, .fa-file-audio-o:before {
  content: "\f1c7"; }

.fa-file-movie-o:before, .fa-file-video-o:before {
  content: "\f1c8"; }

.fa-file-code-o:before {
  content: "\f1c9"; }

.fa-vine:before {
  content: "\f1ca"; }

.fa-codepen:before {
  content: "\f1cb"; }

.fa-jsfiddle:before {
  content: "\f1cc"; }

.fa-life-bouy:before, .fa-life-buoy:before, .fa-life-saver:before, .fa-support:before, .fa-life-ring:before {
  content: "\f1cd"; }

.fa-circle-o-notch:before {
  content: "\f1ce"; }

.fa-ra:before, .fa-rebel:before {
  content: "\f1d0"; }

.fa-ge:before, .fa-empire:before {
  content: "\f1d1"; }

.fa-git-square:before {
  content: "\f1d2"; }

.fa-git:before {
  content: "\f1d3"; }

.fa-hacker-news:before {
  content: "\f1d4"; }

.fa-tencent-weibo:before {
  content: "\f1d5"; }

.fa-qq:before {
  content: "\f1d6"; }

.fa-wechat:before, .fa-weixin:before {
  content: "\f1d7"; }

.fa-send:before, .fa-paper-plane:before {
  content: "\f1d8"; }

.fa-send-o:before, .fa-paper-plane-o:before {
  content: "\f1d9"; }

.fa-history:before {
  content: "\f1da"; }

.fa-genderless:before, .fa-circle-thin:before {
  content: "\f1db"; }

.fa-header:before {
  content: "\f1dc"; }

.fa-paragraph:before {
  content: "\f1dd"; }

.fa-sliders:before {
  content: "\f1de"; }

.fa-share-alt:before {
  content: "\f1e0"; }

.fa-share-alt-square:before {
  content: "\f1e1"; }

.fa-bomb:before {
  content: "\f1e2"; }

.fa-soccer-ball-o:before, .fa-futbol-o:before {
  content: "\f1e3"; }

.fa-tty:before {
  content: "\f1e4"; }

.fa-binoculars:before {
  content: "\f1e5"; }

.fa-plug:before {
  content: "\f1e6"; }

.fa-slideshare:before {
  content: "\f1e7"; }

.fa-twitch:before {
  content: "\f1e8"; }

.fa-yelp:before {
  content: "\f1e9"; }

.fa-newspaper-o:before {
  content: "\f1ea"; }

.fa-wifi:before {
  content: "\f1eb"; }

.fa-calculator:before {
  content: "\f1ec"; }

.fa-paypal:before {
  content: "\f1ed"; }

.fa-google-wallet:before {
  content: "\f1ee"; }

.fa-cc-visa:before {
  content: "\f1f0"; }

.fa-cc-mastercard:before {
  content: "\f1f1"; }

.fa-cc-discover:before {
  content: "\f1f2"; }

.fa-cc-amex:before {
  content: "\f1f3"; }

.fa-cc-paypal:before {
  content: "\f1f4"; }

.fa-cc-stripe:before {
  content: "\f1f5"; }

.fa-bell-slash:before {
  content: "\f1f6"; }

.fa-bell-slash-o:before {
  content: "\f1f7"; }

.fa-trash:before {
  content: "\f1f8"; }

.fa-copyright:before {
  content: "\f1f9"; }

.fa-at:before {
  content: "\f1fa"; }

.fa-eyedropper:before {
  content: "\f1fb"; }

.fa-paint-brush:before {
  content: "\f1fc"; }

.fa-birthday-cake:before {
  content: "\f1fd"; }

.fa-area-chart:before {
  content: "\f1fe"; }

.fa-pie-chart:before {
  content: "\f200"; }

.fa-line-chart:before {
  content: "\f201"; }

.fa-lastfm:before {
  content: "\f202"; }

.fa-lastfm-square:before {
  content: "\f203"; }

.fa-toggle-off:before {
  content: "\f204"; }

.fa-toggle-on:before {
  content: "\f205"; }

.fa-bicycle:before {
  content: "\f206"; }

.fa-bus:before {
  content: "\f207"; }

.fa-ioxhost:before {
  content: "\f208"; }

.fa-angellist:before {
  content: "\f209"; }

.fa-cc:before {
  content: "\f20a"; }

.fa-shekel:before, .fa-sheqel:before, .fa-ils:before {
  content: "\f20b"; }

.fa-meanpath:before {
  content: "\f20c"; }

.fa-buysellads:before {
  content: "\f20d"; }

.fa-connectdevelop:before {
  content: "\f20e"; }

.fa-dashcube:before {
  content: "\f210"; }

.fa-forumbee:before {
  content: "\f211"; }

.fa-leanpub:before {
  content: "\f212"; }

.fa-sellsy:before {
  content: "\f213"; }

.fa-shirtsinbulk:before {
  content: "\f214"; }

.fa-simplybuilt:before {
  content: "\f215"; }

.fa-skyatlas:before {
  content: "\f216"; }

.fa-cart-plus:before {
  content: "\f217"; }

.fa-cart-arrow-down:before {
  content: "\f218"; }

.fa-diamond:before {
  content: "\f219"; }

.fa-ship:before {
  content: "\f21a"; }

.fa-user-secret:before {
  content: "\f21b"; }

.fa-motorcycle:before {
  content: "\f21c"; }

.fa-street-view:before {
  content: "\f21d"; }

.fa-heartbeat:before {
  content: "\f21e"; }

.fa-venus:before {
  content: "\f221"; }

.fa-mars:before {
  content: "\f222"; }

.fa-mercury:before {
  content: "\f223"; }

.fa-transgender:before {
  content: "\f224"; }

.fa-transgender-alt:before {
  content: "\f225"; }

.fa-venus-double:before {
  content: "\f226"; }

.fa-mars-double:before {
  content: "\f227"; }

.fa-venus-mars:before {
  content: "\f228"; }

.fa-mars-stroke:before {
  content: "\f229"; }

.fa-mars-stroke-v:before {
  content: "\f22a"; }

.fa-mars-stroke-h:before {
  content: "\f22b"; }

.fa-neuter:before {
  content: "\f22c"; }

.fa-facebook-official:before {
  content: "\f230"; }

.fa-pinterest-p:before {
  content: "\f231"; }

.fa-whatsapp:before {
  content: "\f232"; }

.fa-server:before {
  content: "\f233"; }

.fa-user-plus:before {
  content: "\f234"; }

.fa-user-times:before {
  content: "\f235"; }

.fa-hotel:before, .fa-bed:before {
  content: "\f236"; }

.fa-viacoin:before {
  content: "\f237"; }

.fa-train:before {
  content: "\f238"; }

.fa-subway:before {
  content: "\f239"; }

.fa-medium:before {
  content: "\f23a"; }

/* 
  My custom styles:
  Add your own folders and scss files for your project and import them below
*/
body {
  color: #6C6C6C;
  font-family: arial, sans-serif; }
  body h1, body h2, body h3, body h4, body h5, body h6 {
    color: #6C6C6C; }
  body a {
    color: #1f5c87; }
  body .author {
    text-transform: uppercase; }
  body input[type=submit] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    font-size: 1.25em;
    background-color: transparent;
    padding: .25em .25em .25em 0;
    border: none;
    margin-top: 3px; }

body .Masthead {
  padding-top: 15px; }
  body .Masthead div.MastheadLogo {
    padding-bottom: 15px; }
  body .Masthead .social {
    text-align: right; }
    body .Masthead .social .social-links {
      font-size: 1.5em;
      text-align: right; }
      body .Masthead .social .social-links a {
        color: #989898; }
        body .Masthead .social .social-links a:hover {
          color: #1f5c87; }
  body .Masthead form.search div div div:last-child {
    padding-left: 0;
    margin-left: 0; }
  body .Masthead form.search div div div input[type=submit] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    font-size: 1.25em;
    background-color: transparent;
    padding: .25em .25em .25em 0;
    border: none;
    margin-top: 3px; }
  body .Masthead nav.navigation ul {
    list-style: none;
    margin-bottom: .25rem; }
    body .Masthead nav.navigation ul li {
      font-size: 1em;
      display: inline-block;
      vertical-align: top;
      padding: 5px 10px; }
      body .Masthead nav.navigation ul li a {
        color: #000000; }
      body .Masthead nav.navigation ul li a:hover {
        color: #1f5c87; }
      body .Masthead nav.navigation ul li ul li {
        display: block; }
  body .Masthead .mobile-nav {
    font-size: 2em;
    text-align: right;
    padding-right: 5px; }
  body .Masthead .right-off-canvas-menu {
    background: #000000; }
    body .Masthead .right-off-canvas-menu ul {
      list-style: none; }
      body .Masthead .right-off-canvas-menu ul li {
        font-size: 1.5em;
        border: none;
        padding: 15px 0; }
        body .Masthead .right-off-canvas-menu ul li a {
          color: #FFFFFF; }
body .title {
  background-color: #000;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  display: table;
  height: 400px;
  width: 100%;
  margin-bottom: 35px; }
  body .title .row {
    display: table-cell;
    vertical-align: middle; }
    body .title .row header {
      display: block;
      max-width: 68.75rem;
      margin: 0 auto; }
      body .title .row header h1, body .title .row header h5, body .title .row header a {
        color: #FFFFFF; }
      body .title .row header h1 {
        font-size: 2.75em;
        line-height: 1;
        margin-bottom: 0; }
      body .title .row header h5 {
        color: #FFFFFF;
        font-family: Arial, san-serif;
        display: inline-block; }
        body .title .row header h5:first-child:after {
          content: '|';
          margin: 0 5px; }
body .content {
  margin-bottom: 100px; }
  body .content main header h3 {
    color: #BABABA;
    font-family: Arial, san-serif;
    font-size: 2em;
    text-transform: uppercase;
    margin-bottom: 10px; }
  body .content main ul {
    margin-left: 0; }
  body .content main article header h4 {
    font-size: 2em; }
  body .content main article header .author h5 {
    font-family: Arial, san-serif;
    font-size: 1em;
    line-height: 1;
    display: inline-block;
    padding-bottom: 0; }
    body .content main article header .author h5:first-child:after {
      content: '|';
      margin: 0 5px; }
  body .content main article section {
    margin-top: 5px; }
  body .content main .alm-btn-wrap {
    text-align: center; }
    body .content main .alm-btn-wrap #load-more {
      color: #6C6C6C;
      font-size: 1.25em;
      background-color: #E7E7E7; }
  body .content aside#sidebar h3 {
    color: #BABABA;
    font-family: Arial, san-serif;
    font-size: 1.5em;
    text-transform: uppercase;
    margin-bottom: 10px; }
  body .content aside#sidebar ul {
    list-style-type: none;
    padding: 0;
    margin: 0; }
    body .content aside#sidebar ul li {
      margin-bottom: 35px; }
      body .content aside#sidebar ul li:last-child {
        margin-bottom: 0; }
      body .content aside#sidebar ul li h4 {
        font-size: 1.25em; }
      body .content aside#sidebar ul li h5 {
        font-family: Arial, san-serif;
        font-size: 1em;
        line-height: 1;
        padding-bottom: 0; }
  body .content aside#sidebar .feature-block {
    margin: 45px 0; }
    body .content aside#sidebar .feature-block img {
      display: block;
      height: auto;
      max-height: 250px;
      width: 100%;
      max-width: 300px;
      margin: 0 auto; }
body #footer {
  padding-top: 35px;
  background-color: #E7E7E7;
  max-width: 100%; }
  body #footer nav ul, body #footer .menu-footer-nav-container ul {
    list-style: none;
    padding: 0;
    margin: 0; }
    body #footer nav ul li, body #footer .menu-footer-nav-container ul li {
      display: inline-block;
      vertical-align: top;
      padding: 5px 30px 5px 0; }
  body #footer .social-links {
    font-size: 1.5em;
    float: right; }

@media only screen and (min-width: 48rem) {
  body .Masthead .mobile-nav {
    display: none; } }

@media only screen and (max-width: 48rem) {
  body .social {
    display: none; }
  body .Masthead div, body .Masthead nav {
    height: 100%; }
    body .Masthead div div.search, body .Masthead nav div.search {
      display: none; }
    body .Masthead div nav.navigation, body .Masthead nav nav.navigation {
      display: none; }
    body .Masthead div .social, body .Masthead nav .social {
      text-align: center; }
  body #footer .navigation li {
    display: block;
    padding: 15px 0; }
  body #footer .social-links {
    display: none; } }

body.archive .title > div {
  background-color: rgba(0, 0, 0, 0.5); }
body.archive main header h1 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  text-transform: uppercase; }

body.home .content main h2 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  font-size: 2.5em;
  text-transform: uppercase;
  margin-bottom: 20px; }

body.page .title {
  height: auto;
  padding-top: 35px;
  padding-bottom: 35px; }
body.page article h2 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  font-size: 1.5em;
  text-transform: uppercase; }

body.search .title, body.error404 .title {
  height: auto;
  padding-top: 35px;
  padding-bottom: 35px; }

body.single .title > div {
  background-color: rgba(0, 0, 0, 0.5); }
body.single article h2 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  font-size: 1.5em;
  text-transform: uppercase; }
body.single article .addthis-toolbox {
  margin: 15px 0; }

body .featured-boxes {
  margin-top: 35px;
  margin-bottom: 35px; }
  body .featured-boxes .featured-box {
    height: 300px;
    padding: 10px; }
    body .featured-boxes .featured-box:hover > .wrapper {
      // background-image: none !important;
      // background-color: #1f5c87; }
    body .featured-boxes .featured-box .wrapper {
      background-color: #E7E7E7;
      background-color: #000;
      background-repeat: no-repeat;
      background-position: center center;
      background-size: cover;
      height: 100%;
      width: 100%; }
      body .featured-boxes .featured-box .wrapper article {
        color: #FFFFFF;
        background-color: rgba(0,0,0,.5);
        padding: 15px;
        height: 100%;
        width: 100%; }
        body .featured-boxes .featured-box .wrapper article a {
          display: table;
          height: 100%;
          width: 100%; }
        body .featured-boxes .featured-box .wrapper article h4, body .featured-boxes .featured-box .wrapper article h5, body .featured-boxes .featured-box .wrapper article a {
          font-size: 1.125rem;
          color: #FFFFFF;
          line-height: 1rem; }
        body .featured-boxes .featured-box .wrapper article .article-title {
          display: table-cell;
          vertical-align: bottom; }
          body .featured-boxes .featured-box .wrapper article .article-title h4 {
            font-family: arial, sans-serif; }
          body .featured-boxes .featured-box .wrapper article .article-title h4:hover {
            text-decoration: underline; }  
          body .featured-boxes .featured-box .wrapper article .article-title .author h5, body .featured-boxes .featured-box .wrapper article .article-title .author a {
            line-height: 1rem;
            margin-bottom: 0;
            font-size: 1rem;
            font-family: Arial, sans-serif;
            text-transform: none; }

body .featured-slideshow {
  max-width: 100%; }
  body .featured-slideshow .orbit-container {
    background-color: #FFF;
    height: 400px;
    width: 100%; }
    body .featured-slideshow .orbit-container ul {
      height: inherit;
      background-color: #1f5c87; }
      body .featured-slideshow .orbit-container ul li {
        height: inherit;
        background-color: #000;
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover; }
        body .featured-slideshow .orbit-container ul li a {
          color: #FFFFFF;
          background-color: rgba(0, 0, 0, 0.5);
          height: inherit;
          display: table;
          width: 100%; }
          body .featured-slideshow .orbit-container ul li a:hover h1 {
            text-decoration: underline; }
          body .featured-slideshow .orbit-container ul li a section {
          	text-align: center;
            display: table-cell;
            vertical-align: middle; }
            body .featured-slideshow .orbit-container ul li a section h1 {
              color: #FFFFFF;
              display: block;
              max-width: 68.75rem;
              padding: 0 30px;
              margin: 0 auto; }
            body .featured-slideshow .orbit-container ul li a section span {
              display: block;
              max-width: 68.75rem;
              padding: 0 30px;
              margin: 0 auto; }
            body .featured-slideshow .orbit-container ul li a section h4 {
              color: #FFFFFF; }
            body .featured-slideshow .orbit-container ul li a section h5 {
              color: #FFFFFF;
              display: inline-block;
              font-family: Arial, sans-serif; }
              body .featured-slideshow .orbit-container ul li a section h5:first-child:after {
                content: '|';
                margin: 0 5px; }
  body .featured-slideshow .slide-controls {
    background-color: #000000; }
    body .featured-slideshow .slide-controls .disc {
      max-width: 68.75rem;
      margin-left: auto;
      margin-right: auto; }
      body .featured-slideshow .slide-controls .disc .slide-control {
        background-color: transparent;
        height: 1px;
        padding-top: 0;
        padding-bottom: 0; }
        body .featured-slideshow .slide-controls .disc .slide-control.active {
          background-color: #1f5c87; }
  body .featured-slideshow .slide-titles {
    background-color: #000000; }
    body .featured-slideshow .slide-titles .disc {
      list-style: none;
      height: 100%;
      max-width: 68.75rem;
      margin-right: auto;
      margin-left: auto; }
      body .featured-slideshow .slide-titles .disc .slide-title {
      	text-align: center;
        padding: 35px; }
        body .featured-slideshow .slide-titles .disc .slide-title a {
          position: relative; }
          body .featured-slideshow .slide-titles .disc .slide-title a h5 {
            color: #FFFFFF;
            font-family: Arial, sans-serif;
            font-size: 1em; }
          body .featured-slideshow .slide-titles .disc .slide-title a .author h5 {
            color: #FFFFFF;
            font-family: arial, sans-serif;
            font-size: .9em;
            line-height: 1.25;
            text-transform: none;
            margin: 0; }

@media screen and (max-width: 48rem) {
  body .featured-slideshow .slide-control {
    display: none; } }

/*# sourceMappingURL=style.css.map *//*
Theme Name:         NewsCred General
Description:        NewsCred General is the CMC Starter Theme
Version:            1.0
Author:             Gregory Maher
Author URI:         http://looknorthinc.com/

License:            MIT License
License URI:        http://www.opensource.org/licenses/mit-license.php
*/
/* ---------------------------------------------------------------------------- 
  
  Unfortunately WordPress will require a style.css file
  located in the theme's root folder for stuff to work.

  However, we will not be using vanilla CSS. We're using Sass.

  Sass is a superset of CSS that adds in amazing features
  such as variables, nested selectors and loops. It's also
  the easiest way to customize Foundation.

  All Sass files are located in the /scss folder.

  Please read the README.md file before getting started. More info on how
  to use Sass with Foundation can be found here:
  http://foundation.zurb.com/docs/sass.html

  If you for some reason would like to write plain css instead of using Sass,
  you could just enqueue this file (style.css) to the header and add your styles in this file

---------------------------------------------------------------------------- */
/*! normalize.css v3.0.2 | MIT License | git.io/normalize */
/*! normalize.css v3.0.2 | MIT License | git.io/normalize */
/**
 * 1. Set default font family to sans-serif.
 * 2. Prevent iOS text size adjust after orientation change, without disabling
 *    user zoom.
 */
html {
  font-family: sans-serif;
  /* 1 */
  -ms-text-size-adjust: 100%;
  /* 2 */
  -webkit-text-size-adjust: 100%;
  /* 2 */ }

/**
 * Remove default margin.
 */
body {
  margin: 0; }

/* HTML5 display definitions
   ========================================================================== */
/**
 * Correct `block` display not defined for any HTML5 element in IE 8/9.
 * Correct `block` display not defined for `details` or `summary` in IE 10/11
 * and Firefox.
 * Correct `block` display not defined for `main` in IE 11.
 */
article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary {
  display: block; }

/**
 * 1. Correct `inline-block` display not defined in IE 8/9.
 * 2. Normalize vertical alignment of `progress` in Chrome, Firefox, and Opera.
 */
audio, canvas, progress, video {
  display: inline-block;
  /* 1 */
  vertical-align: baseline;
  /* 2 */ }

/**
 * Prevent modern browsers from displaying `audio` without controls.
 * Remove excess height in iOS 5 devices.
 */
audio:not([controls]) {
  display: none;
  height: 0; }

/**
 * Address `[hidden]` styling not present in IE 8/9/10.
 * Hide the `template` element in IE 8/9/11, Safari, and Firefox < 22.
 */
[hidden], template {
  display: none; }

/* Links
   ========================================================================== */
/**
 * Remove the gray background color from active links in IE 10.
 */
a {
  background-color: transparent; }

/**
 * Improve readability when focused and also mouse hovered in all browsers.
 */
a:active, a:hover {
  outline: 0; }

/* Text-level semantics
   ========================================================================== */
/**
 * Address styling not present in IE 8/9/10/11, Safari, and Chrome.
 */
abbr[title] {
  border-bottom: 1px dotted; }

/**
 * Address style set to `bolder` in Firefox 4+, Safari, and Chrome.
 */
b, strong {
  font-weight: bold; }

/**
 * Address styling not present in Safari and Chrome.
 */
dfn {
  font-style: italic; }

/**
 * Address variable `h1` font-size and margin within `section` and `article`
 * contexts in Firefox 4+, Safari, and Chrome.
 */
h1 {
  font-size: 2em;
  margin: 0.67em 0; }

/**
 * Address styling not present in IE 8/9.
 */
mark {
  background: #ff0;
  color: #000; }

/**
 * Address inconsistent and variable font size in all browsers.
 */
small {
  font-size: 80%; }

/**
 * Prevent `sub` and `sup` affecting `line-height` in all browsers.
 */
sub, sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline; }

sup {
  top: -0.5em; }

sub {
  bottom: -0.25em; }

/* Embedded content
   ========================================================================== */
/**
 * Remove border when inside `a` element in IE 8/9/10.
 */
img {
  border: 0; }

/**
 * Correct overflow not hidden in IE 9/10/11.
 */
svg:not(:root) {
  overflow: hidden; }

/* Grouping content
   ========================================================================== */
/**
 * Address margin not present in IE 8/9 and Safari.
 */
figure {
  margin: 1em 40px; }

/**
 * Address differences between Firefox and other browsers.
 */
hr {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
  height: 0; }

/**
 * Contain overflow in all browsers.
 */
pre {
  overflow: auto; }

/**
 * Address odd `em`-unit font size rendering in all browsers.
 */
code, kbd, pre, samp {
  font-family: monospace, monospace;
  font-size: 1em; }

/* Forms
   ========================================================================== */
/**
 * Known limitation: by default, Chrome and Safari on OS X allow very limited
 * styling of `select`, unless a `border` property is set.
 */
/**
 * 1. Correct color not being inherited.
 *    Known issue: affects color of disabled elements.
 * 2. Correct font properties not being inherited.
 * 3. Address margins set differently in Firefox 4+, Safari, and Chrome.
 */
button, input, optgroup, select, textarea {
  color: inherit;
  /* 1 */
  font: inherit;
  /* 2 */
  margin: 0;
  /* 3 */ }

/**
 * Address `overflow` set to `hidden` in IE 8/9/10/11.
 */
button {
  overflow: visible; }

/**
 * Address inconsistent `text-transform` inheritance for `button` and `select`.
 * All other form control elements do not inherit `text-transform` values.
 * Correct `button` style inheritance in Firefox, IE 8/9/10/11, and Opera.
 * Correct `select` style inheritance in Firefox.
 */
button, select {
  text-transform: none; }

/**
 * 1. Avoid the WebKit bug in Android 4.0.* where (2) destroys native `audio`
 *    and `video` controls.
 * 2. Correct inability to style clickable `input` types in iOS.
 * 3. Improve usability and consistency of cursor style between image-type
 *    `input` and others.
 */
button, html input[type="button"], input[type="reset"], input[type="submit"] {
  -webkit-appearance: button;
  /* 2 */
  cursor: pointer;
  /* 3 */ }

/**
 * Re-set default cursor for disabled elements.
 */
button[disabled], html input[disabled] {
  cursor: default; }

/**
 * Remove inner padding and border in Firefox 4+.
 */
button::-moz-focus-inner, input::-moz-focus-inner {
  border: 0;
  padding: 0; }

/**
 * Address Firefox 4+ setting `line-height` on `input` using `!important` in
 * the UA stylesheet.
 */
input {
  line-height: normal; }

/**
 * It's recommended that you don't attempt to style these elements.
 * Firefox's implementation doesn't respect box-sizing, padding, or width.
 *
 * 1. Address box sizing set to `content-box` in IE 8/9/10.
 * 2. Remove excess padding in IE 8/9/10.
 */
input[type="checkbox"], input[type="radio"] {
  box-sizing: border-box;
  /* 1 */
  padding: 0;
  /* 2 */ }

/**
 * Fix the cursor style for Chrome's increment/decrement buttons. For certain
 * `font-size` values of the `input`, it causes the cursor style of the
 * decrement button to change from `default` to `text`.
 */
input[type="number"]::-webkit-inner-spin-button, input[type="number"]::-webkit-outer-spin-button {
  height: auto; }

/**
 * 1. Address `appearance` set to `searchfield` in Safari and Chrome.
 * 2. Address `box-sizing` set to `border-box` in Safari and Chrome
 *    (include `-moz` to future-proof).
 */
input[type="search"] {
  -webkit-appearance: textfield;
  /* 1 */
  -moz-box-sizing: content-box;
  -webkit-box-sizing: content-box;
  /* 2 */
  box-sizing: content-box; }

/**
 * Remove inner padding and search cancel button in Safari and Chrome on OS X.
 * Safari (but not Chrome) clips the cancel button when the search input has
 * padding (and `textfield` appearance).
 */
input[type="search"]::-webkit-search-cancel-button, input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none; }

/**
 * Define consistent border, margin, and padding.
 */
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em; }

/**
 * 1. Correct `color` not being inherited in IE 8/9/10/11.
 * 2. Remove padding so people aren't caught out if they zero out fieldsets.
 */
legend {
  border: 0;
  /* 1 */
  padding: 0;
  /* 2 */ }

/**
 * Remove default vertical scrollbar in IE 8/9/10/11.
 */
textarea {
  overflow: auto; }

/**
 * Don't inherit the `font-weight` (applied by a rule above).
 * NOTE: the default cannot safely be changed in Chrome and Safari on OS X.
 */
optgroup {
  font-weight: bold; }

/* Tables
   ========================================================================== */
/**
 * Remove most spacing between table cells.
 */
table {
  border-collapse: collapse;
  border-spacing: 0; }

td, th {
  padding: 0; }

/*  
  ZURB Foundation components:
  Import the building blocks you need for your project. 
  Reducing the number of imported components will optimize page speed.
*/
meta.foundation-version {
  font-family: "/5.5.1/"; }

meta.foundation-mq-small {
  font-family: "/only screen/";
  width: 0em; }

meta.foundation-mq-small-only {
  font-family: "/only screen and (max-width: 40em)/";
  width: 0em; }

meta.foundation-mq-medium {
  font-family: "/only screen and (min-width:40.063em)/";
  width: 40.063em; }

meta.foundation-mq-medium-only {
  font-family: "/only screen and (min-width:40.063em) and (max-width:64em)/";
  width: 40.063em; }

meta.foundation-mq-large {
  font-family: "/only screen and (min-width:64.063em)/";
  width: 64.063em; }

meta.foundation-mq-large-only {
  font-family: "/only screen and (min-width:64.063em) and (max-width:90em)/";
  width: 64.063em; }

meta.foundation-mq-xlarge {
  font-family: "/only screen and (min-width:90.063em)/";
  width: 90.063em; }

meta.foundation-mq-xlarge-only {
  font-family: "/only screen and (min-width:90.063em) and (max-width:120em)/";
  width: 90.063em; }

meta.foundation-mq-xxlarge {
  font-family: "/only screen and (min-width:120.063em)/";
  width: 120.063em; }

meta.foundation-data-attribute-namespace {
  font-family: false; }

html, body {
  height: 100%; }

*, *:before, *:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box; }

html, body {
  font-size: 100%; }

body {
  background: #fff;
  color: #565656;
  padding: 0;
  margin: 0;
  font-family: arial, sans-serif;;
  font-weight: 400;
  font-style: normal;
  line-height: 1.5;
  position: relative;
  cursor: auto; }

a:hover {
  cursor: pointer; }

img {
  max-width: 100%;
  height: auto; }

img {
  -ms-interpolation-mode: bicubic; }

#map_canvas img, #map_canvas embed, #map_canvas object, .map_canvas img, .map_canvas embed, .map_canvas object {
  max-width: none !important; }

.left {
  float: left !important; }

.right {
  float: right !important; }

.clearfix:before, .clearfix:after {
  content: " ";
  display: table; }
.clearfix:after {
  clear: both; }

.hide {
  display: none; }

.invisible {
  visibility: hidden; }

.antialiased {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; }

img {
  display: inline-block;
  vertical-align: middle; }

textarea {
  height: auto;
  min-height: 50px; }

select {
  width: 100%; }

.row {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 0;
  margin-bottom: 0;
  max-width: 68.75rem; }
  .row:before, .row:after {
    content: " ";
    display: table; }
  .row:after {
    clear: both; }
  .row.collapse > .column, .row.collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row .row {
    width: auto;
    margin-left: -0.9375rem;
    margin-right: -0.9375rem;
    margin-top: 0;
    margin-bottom: 0;
    max-width: none; }
    .row .row:before, .row .row:after {
      content: " ";
      display: table; }
    .row .row:after {
      clear: both; }
    .row .row.collapse {
      width: auto;
      margin: 0;
      max-width: none; }
      .row .row.collapse:before, .row .row.collapse:after {
        content: " ";
        display: table; }
      .row .row.collapse:after {
        clear: both; }

.column, .columns {
  padding-left: 0.9375rem;
  padding-right: 0.9375rem;
  width: 100%;
  float: left; }

[class*="column"] + [class*="column"]:last-child {
  float: right; }

[class*="column"] + [class*="column"].end {
  float: left; }

@media only screen {
  .small-push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .small-pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .small-push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .small-pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .small-push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .small-pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .small-push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .small-pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .small-push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .small-pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .small-push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .small-pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .small-push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .small-pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .small-push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .small-pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .small-push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .small-pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .small-push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .small-pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .small-push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .small-pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .small-push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .small-pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .small-push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .small-pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .small-push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .small-pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .small-push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .small-pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .small-push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .small-pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; }
  .column, .columns {
    position: relative;
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .small-1 {
    width: 6.25%; }
  .small-2 {
    width: 12.5%; }
  .small-3 {
    width: 18.75%; }
  .small-4 {
    width: 25%; }
  .small-5 {
    width: 31.25%; }
  .small-6 {
    width: 37.5%; }
  .small-7 {
    width: 43.75%; }
  .small-8 {
    width: 50%; }
  .small-9 {
    width: 56.25%; }
  .small-10 {
    width: 62.5%; }
  .small-11 {
    width: 68.75%; }
  .small-12 {
    width: 75%; }
  .small-13 {
    width: 81.25%; }
  .small-14 {
    width: 87.5%; }
  .small-15 {
    width: 93.75%; }
  .small-16 {
    width: 100%; }
  .small-offset-0 {
    margin-left: 0% !important; }
  .small-offset-1 {
    margin-left: 6.25% !important; }
  .small-offset-2 {
    margin-left: 12.5% !important; }
  .small-offset-3 {
    margin-left: 18.75% !important; }
  .small-offset-4 {
    margin-left: 25% !important; }
  .small-offset-5 {
    margin-left: 31.25% !important; }
  .small-offset-6 {
    margin-left: 37.5% !important; }
  .small-offset-7 {
    margin-left: 43.75% !important; }
  .small-offset-8 {
    margin-left: 50% !important; }
  .small-offset-9 {
    margin-left: 56.25% !important; }
  .small-offset-10 {
    margin-left: 62.5% !important; }
  .small-offset-11 {
    margin-left: 68.75% !important; }
  .small-offset-12 {
    margin-left: 75% !important; }
  .small-offset-13 {
    margin-left: 81.25% !important; }
  .small-offset-14 {
    margin-left: 87.5% !important; }
  .small-offset-15 {
    margin-left: 93.75% !important; }
  .small-reset-order {
    margin-left: 0;
    margin-right: 0;
    left: auto;
    right: auto;
    float: left; }
  .column.small-centered, .columns.small-centered {
    margin-left: auto;
    margin-right: auto;
    float: none; }
  .column.small-uncentered, .columns.small-uncentered {
    margin-left: 0;
    margin-right: 0;
    float: left; }
  .column.small-centered:last-child, .columns.small-centered:last-child {
    float: none; }
  .column.small-uncentered:last-child, .columns.small-uncentered:last-child {
    float: left; }
  .column.small-uncentered.opposite, .columns.small-uncentered.opposite {
    float: right; }
  .row.small-collapse > .column, .row.small-collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.small-collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row.small-uncollapse > .column, .row.small-uncollapse > .columns {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; } }

@media only screen and (min-width:40.063em) {
  .medium-push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .medium-pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .medium-push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .medium-pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .medium-push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .medium-pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .medium-push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .medium-pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .medium-push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .medium-pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .medium-push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .medium-pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .medium-push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .medium-pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .medium-push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .medium-pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .medium-push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .medium-pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .medium-push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .medium-pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .medium-push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .medium-pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .medium-push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .medium-pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .medium-push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .medium-pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .medium-push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .medium-pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .medium-push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .medium-pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .medium-push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .medium-pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; }
  .column, .columns {
    position: relative;
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .medium-1 {
    width: 6.25%; }
  .medium-2 {
    width: 12.5%; }
  .medium-3 {
    width: 18.75%; }
  .medium-4 {
    width: 25%; }
  .medium-5 {
    width: 31.25%; }
  .medium-6 {
    width: 37.5%; }
  .medium-7 {
    width: 43.75%; }
  .medium-8 {
    width: 50%; }
  .medium-9 {
    width: 56.25%; }
  .medium-10 {
    width: 62.5%; }
  .medium-11 {
    width: 68.75%; }
  .medium-12 {
    width: 75%; }
  .medium-13 {
    width: 81.25%; }
  .medium-14 {
    width: 87.5%; }
  .medium-15 {
    width: 93.75%; }
  .medium-16 {
    width: 100%; }
  .medium-offset-0 {
    margin-left: 0% !important; }
  .medium-offset-1 {
    margin-left: 6.25% !important; }
  .medium-offset-2 {
    margin-left: 12.5% !important; }
  .medium-offset-3 {
    margin-left: 18.75% !important; }
  .medium-offset-4 {
    margin-left: 25% !important; }
  .medium-offset-5 {
    margin-left: 31.25% !important; }
  .medium-offset-6 {
    margin-left: 37.5% !important; }
  .medium-offset-7 {
    margin-left: 43.75% !important; }
  .medium-offset-8 {
    margin-left: 50% !important; }
  .medium-offset-9 {
    margin-left: 56.25% !important; }
  .medium-offset-10 {
    margin-left: 62.5% !important; }
  .medium-offset-11 {
    margin-left: 68.75% !important; }
  .medium-offset-12 {
    margin-left: 75% !important; }
  .medium-offset-13 {
    margin-left: 81.25% !important; }
  .medium-offset-14 {
    margin-left: 87.5% !important; }
  .medium-offset-15 {
    margin-left: 93.75% !important; }
  .medium-reset-order {
    margin-left: 0;
    margin-right: 0;
    left: auto;
    right: auto;
    float: left; }
  .column.medium-centered, .columns.medium-centered {
    margin-left: auto;
    margin-right: auto;
    float: none; }
  .column.medium-uncentered, .columns.medium-uncentered {
    margin-left: 0;
    margin-right: 0;
    float: left; }
  .column.medium-centered:last-child, .columns.medium-centered:last-child {
    float: none; }
  .column.medium-uncentered:last-child, .columns.medium-uncentered:last-child {
    float: left; }
  .column.medium-uncentered.opposite, .columns.medium-uncentered.opposite {
    float: right; }
  .row.medium-collapse > .column, .row.medium-collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.medium-collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row.medium-uncollapse > .column, .row.medium-uncollapse > .columns {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; } }

@media only screen and (min-width:64.063em) {
  .large-push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .large-pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .large-push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .large-pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .large-push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .large-pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .large-push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .large-pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .large-push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .large-pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .large-push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .large-pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .large-push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .large-pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .large-push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .large-pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .large-push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .large-pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .large-push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .large-pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .large-push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .large-pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .large-push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .large-pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .large-push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .large-pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .large-push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .large-pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .large-push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .large-pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .large-push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .large-pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; }
  .column, .columns {
    position: relative;
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .large-1 {
    width: 6.25%; }
  .large-2 {
    width: 12.5%; }
  .large-3 {
    width: 18.75%; }
  .large-4 {
    width: 25%; }
  .large-5 {
    width: 31.25%; }
  .large-6 {
    width: 37.5%; }
  .large-7 {
    width: 43.75%; }
  .large-8 {
    width: 50%; }
  .large-9 {
    width: 56.25%; }
  .large-10 {
    width: 62.5%; }
  .large-11 {
    width: 68.75%; }
  .large-12 {
    width: 75%; }
  .large-13 {
    width: 81.25%; }
  .large-14 {
    width: 87.5%; }
  .large-15 {
    width: 93.75%; }
  .large-16 {
    width: 100%; }
  .large-offset-0 {
    margin-left: 0% !important; }
  .large-offset-1 {
    margin-left: 6.25% !important; }
  .large-offset-2 {
    margin-left: 12.5% !important; }
  .large-offset-3 {
    margin-left: 18.75% !important; }
  .large-offset-4 {
    margin-left: 25% !important; }
  .large-offset-5 {
    margin-left: 31.25% !important; }
  .large-offset-6 {
    margin-left: 37.5% !important; }
  .large-offset-7 {
    margin-left: 43.75% !important; }
  .large-offset-8 {
    margin-left: 50% !important; }
  .large-offset-9 {
    margin-left: 56.25% !important; }
  .large-offset-10 {
    margin-left: 62.5% !important; }
  .large-offset-11 {
    margin-left: 68.75% !important; }
  .large-offset-12 {
    margin-left: 75% !important; }
  .large-offset-13 {
    margin-left: 81.25% !important; }
  .large-offset-14 {
    margin-left: 87.5% !important; }
  .large-offset-15 {
    margin-left: 93.75% !important; }
  .large-reset-order {
    margin-left: 0;
    margin-right: 0;
    left: auto;
    right: auto;
    float: left; }
  .column.large-centered, .columns.large-centered {
    margin-left: auto;
    margin-right: auto;
    float: none; }
  .column.large-uncentered, .columns.large-uncentered {
    margin-left: 0;
    margin-right: 0;
    float: left; }
  .column.large-centered:last-child, .columns.large-centered:last-child {
    float: none; }
  .column.large-uncentered:last-child, .columns.large-uncentered:last-child {
    float: left; }
  .column.large-uncentered.opposite, .columns.large-uncentered.opposite {
    float: right; }
  .row.large-collapse > .column, .row.large-collapse > .columns {
    padding-left: 0;
    padding-right: 0; }
  .row.large-collapse .row {
    margin-left: 0;
    margin-right: 0; }
  .row.large-uncollapse > .column, .row.large-uncollapse > .columns {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    float: left; }
  .push-0 {
    position: relative;
    left: 0%;
    right: auto; }
  .pull-0 {
    position: relative;
    right: 0%;
    left: auto; }
  .push-1 {
    position: relative;
    left: 6.25%;
    right: auto; }
  .pull-1 {
    position: relative;
    right: 6.25%;
    left: auto; }
  .push-2 {
    position: relative;
    left: 12.5%;
    right: auto; }
  .pull-2 {
    position: relative;
    right: 12.5%;
    left: auto; }
  .push-3 {
    position: relative;
    left: 18.75%;
    right: auto; }
  .pull-3 {
    position: relative;
    right: 18.75%;
    left: auto; }
  .push-4 {
    position: relative;
    left: 25%;
    right: auto; }
  .pull-4 {
    position: relative;
    right: 25%;
    left: auto; }
  .push-5 {
    position: relative;
    left: 31.25%;
    right: auto; }
  .pull-5 {
    position: relative;
    right: 31.25%;
    left: auto; }
  .push-6 {
    position: relative;
    left: 37.5%;
    right: auto; }
  .pull-6 {
    position: relative;
    right: 37.5%;
    left: auto; }
  .push-7 {
    position: relative;
    left: 43.75%;
    right: auto; }
  .pull-7 {
    position: relative;
    right: 43.75%;
    left: auto; }
  .push-8 {
    position: relative;
    left: 50%;
    right: auto; }
  .pull-8 {
    position: relative;
    right: 50%;
    left: auto; }
  .push-9 {
    position: relative;
    left: 56.25%;
    right: auto; }
  .pull-9 {
    position: relative;
    right: 56.25%;
    left: auto; }
  .push-10 {
    position: relative;
    left: 62.5%;
    right: auto; }
  .pull-10 {
    position: relative;
    right: 62.5%;
    left: auto; }
  .push-11 {
    position: relative;
    left: 68.75%;
    right: auto; }
  .pull-11 {
    position: relative;
    right: 68.75%;
    left: auto; }
  .push-12 {
    position: relative;
    left: 75%;
    right: auto; }
  .pull-12 {
    position: relative;
    right: 75%;
    left: auto; }
  .push-13 {
    position: relative;
    left: 81.25%;
    right: auto; }
  .pull-13 {
    position: relative;
    right: 81.25%;
    left: auto; }
  .push-14 {
    position: relative;
    left: 87.5%;
    right: auto; }
  .pull-14 {
    position: relative;
    right: 87.5%;
    left: auto; }
  .push-15 {
    position: relative;
    left: 93.75%;
    right: auto; }
  .pull-15 {
    position: relative;
    right: 93.75%;
    left: auto; } }

.accordion {
  margin-bottom: 0; }
  .accordion:before, .accordion:after {
    content: " ";
    display: table; }
  .accordion:after {
    clear: both; }
  .accordion .accordion-navigation, .accordion dd {
    display: block;
    margin-bottom: 0 !important; }
    .accordion .accordion-navigation.active > a, .accordion dd.active > a {
      background: #e8e8e8; }
    .accordion .accordion-navigation > a, .accordion dd > a {
      background: #EFEFEF;
      color: #222222;
      padding: 1rem;
      display: block;
      font-family: arial, sans-serif;
      font-size: 1rem; }
      .accordion .accordion-navigation > a:hover, .accordion dd > a:hover {
        background: #e3e3e3; }
    .accordion .accordion-navigation > .content, .accordion dd > .content {
      display: none;
      padding: 0.9375rem; }
      .accordion .accordion-navigation > .content.active, .accordion dd > .content.active {
        display: block;
        background: #FFFFFF; }

.alert-box {
  border-style: solid;
  border-width: 1px;
  display: block;
  font-weight: 400;
  margin-bottom: 1.25rem;
  position: relative;
  padding: 0.875rem 1.5rem 0.875rem 0.875rem;
  font-size: 0.8125rem;
  transition: opacity 300ms ease-out;
  background-color: #1f5c87;
  border-color: #db8a00;
  color: #FFFFFF; }
  .alert-box .close {
    font-size: 1.375rem;
    padding: 0 6px 4px;
    line-height: .9;
    position: absolute;
    top: 50%;
    margin-top: -0.6875rem;
    right: 0.25rem;
    color: #333333;
    opacity: 0.3;
    background: inherit; }
    .alert-box .close:hover, .alert-box .close:focus {
      opacity: 0.5; }
  .alert-box.radius {
    border-radius: 3px; }
  .alert-box.round {
    border-radius: 1000px; }
  .alert-box.success {
    background-color: #43AC6A;
    border-color: #3a945b;
    color: #FFFFFF; }
  .alert-box.alert {
    background-color: #f04124;
    border-color: #de2d0f;
    color: #FFFFFF; }
  .alert-box.secondary {
    background-color: #E7E7E7;
    border-color: #c7c7c7;
    color: #4f4f4f; }
  .alert-box.warning {
    background-color: #f08a24;
    border-color: #de770f;
    color: #FFFFFF; }
  .alert-box.info {
    background-color: #a0d3e8;
    border-color: #74bfdd;
    color: #4f4f4f; }
  .alert-box.alert-close {
    opacity: 0; }

[class*="block-grid-"] {
  display: block;
  padding: 0;
  margin: 0 -0.625rem; }
  [class*="block-grid-"]:before, [class*="block-grid-"]:after {
    content: " ";
    display: table; }
  [class*="block-grid-"]:after {
    clear: both; }
  [class*="block-grid-"] > li {
    display: block;
    height: auto;
    float: left;
    padding: 0 0.625rem 1.25rem; }

@media only screen {
  .small-block-grid-1 > li {
    width: 100%;
    list-style: none; }
    .small-block-grid-1 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-1 > li:nth-of-type(1n+1) {
      clear: both; }
  .small-block-grid-2 > li {
    width: 50%;
    list-style: none; }
    .small-block-grid-2 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-2 > li:nth-of-type(2n+1) {
      clear: both; }
  .small-block-grid-3 > li {
    width: 33.3333333333%;
    list-style: none; }
    .small-block-grid-3 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-3 > li:nth-of-type(3n+1) {
      clear: both; }
  .small-block-grid-4 > li {
    width: 25%;
    list-style: none; }
    .small-block-grid-4 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-4 > li:nth-of-type(4n+1) {
      clear: both; }
  .small-block-grid-5 > li {
    width: 20%;
    list-style: none; }
    .small-block-grid-5 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-5 > li:nth-of-type(5n+1) {
      clear: both; }
  .small-block-grid-6 > li {
    width: 16.6666666667%;
    list-style: none; }
    .small-block-grid-6 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-6 > li:nth-of-type(6n+1) {
      clear: both; }
  .small-block-grid-7 > li {
    width: 14.2857142857%;
    list-style: none; }
    .small-block-grid-7 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-7 > li:nth-of-type(7n+1) {
      clear: both; }
  .small-block-grid-8 > li {
    width: 12.5%;
    list-style: none; }
    .small-block-grid-8 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-8 > li:nth-of-type(8n+1) {
      clear: both; }
  .small-block-grid-9 > li {
    width: 11.1111111111%;
    list-style: none; }
    .small-block-grid-9 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-9 > li:nth-of-type(9n+1) {
      clear: both; }
  .small-block-grid-10 > li {
    width: 10%;
    list-style: none; }
    .small-block-grid-10 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-10 > li:nth-of-type(10n+1) {
      clear: both; }
  .small-block-grid-11 > li {
    width: 9.0909090909%;
    list-style: none; }
    .small-block-grid-11 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-11 > li:nth-of-type(11n+1) {
      clear: both; }
  .small-block-grid-12 > li {
    width: 8.3333333333%;
    list-style: none; }
    .small-block-grid-12 > li:nth-of-type(1n) {
      clear: none; }
    .small-block-grid-12 > li:nth-of-type(12n+1) {
      clear: both; } }

@media only screen and (min-width:40.063em) {
  .medium-block-grid-1 > li {
    width: 100%;
    list-style: none; }
    .medium-block-grid-1 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-1 > li:nth-of-type(1n+1) {
      clear: both; }
  .medium-block-grid-2 > li {
    width: 50%;
    list-style: none; }
    .medium-block-grid-2 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-2 > li:nth-of-type(2n+1) {
      clear: both; }
  .medium-block-grid-3 > li {
    width: 33.3333333333%;
    list-style: none; }
    .medium-block-grid-3 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-3 > li:nth-of-type(3n+1) {
      clear: both; }
  .medium-block-grid-4 > li {
    width: 25%;
    list-style: none; }
    .medium-block-grid-4 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-4 > li:nth-of-type(4n+1) {
      clear: both; }
  .medium-block-grid-5 > li {
    width: 20%;
    list-style: none; }
    .medium-block-grid-5 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-5 > li:nth-of-type(5n+1) {
      clear: both; }
  .medium-block-grid-6 > li {
    width: 16.6666666667%;
    list-style: none; }
    .medium-block-grid-6 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-6 > li:nth-of-type(6n+1) {
      clear: both; }
  .medium-block-grid-7 > li {
    width: 14.2857142857%;
    list-style: none; }
    .medium-block-grid-7 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-7 > li:nth-of-type(7n+1) {
      clear: both; }
  .medium-block-grid-8 > li {
    width: 12.5%;
    list-style: none; }
    .medium-block-grid-8 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-8 > li:nth-of-type(8n+1) {
      clear: both; }
  .medium-block-grid-9 > li {
    width: 11.1111111111%;
    list-style: none; }
    .medium-block-grid-9 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-9 > li:nth-of-type(9n+1) {
      clear: both; }
  .medium-block-grid-10 > li {
    width: 10%;
    list-style: none; }
    .medium-block-grid-10 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-10 > li:nth-of-type(10n+1) {
      clear: both; }
  .medium-block-grid-11 > li {
    width: 9.0909090909%;
    list-style: none; }
    .medium-block-grid-11 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-11 > li:nth-of-type(11n+1) {
      clear: both; }
  .medium-block-grid-12 > li {
    width: 8.3333333333%;
    list-style: none; }
    .medium-block-grid-12 > li:nth-of-type(1n) {
      clear: none; }
    .medium-block-grid-12 > li:nth-of-type(12n+1) {
      clear: both; } }

@media only screen and (min-width:64.063em) {
  .large-block-grid-1 > li {
    width: 100%;
    list-style: none; }
    .large-block-grid-1 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-1 > li:nth-of-type(1n+1) {
      clear: both; }
  .large-block-grid-2 > li {
    width: 50%;
    list-style: none; }
    .large-block-grid-2 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-2 > li:nth-of-type(2n+1) {
      clear: both; }
  .large-block-grid-3 > li {
    width: 33.3333333333%;
    list-style: none; }
    .large-block-grid-3 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-3 > li:nth-of-type(3n+1) {
      clear: both; }
  .large-block-grid-4 > li {
    width: 25%;
    list-style: none; }
    .large-block-grid-4 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-4 > li:nth-of-type(4n+1) {
      clear: both; }
  .large-block-grid-5 > li {
    width: 20%;
    list-style: none; }
    .large-block-grid-5 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-5 > li:nth-of-type(5n+1) {
      clear: both; }
  .large-block-grid-6 > li {
    width: 16.6666666667%;
    list-style: none; }
    .large-block-grid-6 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-6 > li:nth-of-type(6n+1) {
      clear: both; }
  .large-block-grid-7 > li {
    width: 14.2857142857%;
    list-style: none; }
    .large-block-grid-7 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-7 > li:nth-of-type(7n+1) {
      clear: both; }
  .large-block-grid-8 > li {
    width: 12.5%;
    list-style: none; }
    .large-block-grid-8 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-8 > li:nth-of-type(8n+1) {
      clear: both; }
  .large-block-grid-9 > li {
    width: 11.1111111111%;
    list-style: none; }
    .large-block-grid-9 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-9 > li:nth-of-type(9n+1) {
      clear: both; }
  .large-block-grid-10 > li {
    width: 10%;
    list-style: none; }
    .large-block-grid-10 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-10 > li:nth-of-type(10n+1) {
      clear: both; }
  .large-block-grid-11 > li {
    width: 9.0909090909%;
    list-style: none; }
    .large-block-grid-11 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-11 > li:nth-of-type(11n+1) {
      clear: both; }
  .large-block-grid-12 > li {
    width: 8.3333333333%;
    list-style: none; }
    .large-block-grid-12 > li:nth-of-type(1n) {
      clear: none; }
    .large-block-grid-12 > li:nth-of-type(12n+1) {
      clear: both; } }

.breadcrumbs {
  display: block;
  padding: 0.5625rem 0.875rem 0.5625rem;
  overflow: hidden;
  margin-left: 0;
  list-style: none;
  border-style: solid;
  border-width: 1px;
  background-color: #f4f4f4;
  border-color: gainsboro;
  border-radius: 3px; }
  .breadcrumbs > * {
    margin: 0;
    float: left;
    font-size: 0.6875rem;
    line-height: 0.6875rem;
    text-transform: uppercase;
    color: #1f5c87; }
    .breadcrumbs > *:hover a, .breadcrumbs > *:focus a {
      text-decoration: underline; }
    .breadcrumbs > * a {
      color: #1f5c87; }
    .breadcrumbs > *.current {
      cursor: default;
      color: #333333; }
      .breadcrumbs > *.current a {
        cursor: default;
        color: #333333; }
      .breadcrumbs > *.current:hover, .breadcrumbs > *.current:hover a, .breadcrumbs > *.current:focus, .breadcrumbs > *.current:focus a {
        text-decoration: none; }
    .breadcrumbs > *.unavailable {
      color: #999999; }
      .breadcrumbs > *.unavailable a {
        color: #999999; }
      .breadcrumbs > *.unavailable:hover, .breadcrumbs > *.unavailable:hover a, .breadcrumbs > *.unavailable:focus, .breadcrumbs > *.unavailable a:focus {
        text-decoration: none;
        color: #999999;
        cursor: false; }
    .breadcrumbs > *:before {
      content: "/";
      color: #AAAAAA;
      margin: 0 0.75rem;
      position: relative;
      top: 1px; }
    .breadcrumbs > *:first-child:before {
      content: " ";
      margin: 0; }

/* Accessibility - hides the forward slash */
[aria-label="breadcrumbs"] [aria-hidden="true"]:after {
  content: "/"; }

button, .button {
  border-style: solid;
  border-width: 0;
  cursor: pointer;
  font-family: arial, sans-serif;
  font-weight: 400;
  line-height: normal;
  margin: 0 0 1.25rem;
  position: relative;
  text-decoration: none;
  text-align: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  border-radius: 0;
  display: inline-block;
  padding-top: 1rem;
  padding-right: 2rem;
  padding-bottom: 1.0625rem;
  padding-left: 2rem;
  font-size: 1rem;
  background-color: #1f5c87;
  border-color: #cc8100;
  color: #FFFFFF;
  transition: background-color 300ms ease-out; }
  button:hover, button:focus, .button:hover, .button:focus {
    background-color: #cc8100; }
  button:hover, button:focus, .button:hover, .button:focus {
    color: #FFFFFF; }
  button.secondary, .button.secondary {
    background-color: #E7E7E7;
    border-color: #b9b9b9;
    color: #333333; }
    button.secondary:hover, button.secondary:focus, .button.secondary:hover, .button.secondary:focus {
      background-color: #b9b9b9; }
    button.secondary:hover, button.secondary:focus, .button.secondary:hover, .button.secondary:focus {
      color: #333333; }
  button.success, .button.success {
    background-color: #43AC6A;
    border-color: #368a55;
    color: #FFFFFF; }
    button.success:hover, button.success:focus, .button.success:hover, .button.success:focus {
      background-color: #368a55; }
    button.success:hover, button.success:focus, .button.success:hover, .button.success:focus {
      color: #FFFFFF; }
  button.alert, .button.alert {
    background-color: #f04124;
    border-color: #cf2a0e;
    color: #FFFFFF; }
    button.alert:hover, button.alert:focus, .button.alert:hover, .button.alert:focus {
      background-color: #cf2a0e; }
    button.alert:hover, button.alert:focus, .button.alert:hover, .button.alert:focus {
      color: #FFFFFF; }
  button.warning, .button.warning {
    background-color: #f08a24;
    border-color: #cf6e0e;
    color: #FFFFFF; }
    button.warning:hover, button.warning:focus, .button.warning:hover, .button.warning:focus {
      background-color: #cf6e0e; }
    button.warning:hover, button.warning:focus, .button.warning:hover, .button.warning:focus {
      color: #FFFFFF; }
  button.info, .button.info {
    background-color: #a0d3e8;
    border-color: #61b6d9;
    color: #333333; }
    button.info:hover, button.info:focus, .button.info:hover, .button.info:focus {
      background-color: #61b6d9; }
    button.info:hover, button.info:focus, .button.info:hover, .button.info:focus {
      color: #FFFFFF; }
  button.large, .button.large {
    padding-top: 1.125rem;
    padding-right: 2.25rem;
    padding-bottom: 1.1875rem;
    padding-left: 2.25rem;
    font-size: 1.25rem; }
  button.small, .button.small {
    padding-top: 0.875rem;
    padding-right: 1.75rem;
    padding-bottom: 0.9375rem;
    padding-left: 1.75rem;
    font-size: 0.8125rem; }
  button.tiny, .button.tiny {
    padding-top: 0.625rem;
    padding-right: 1.25rem;
    padding-bottom: 0.6875rem;
    padding-left: 1.25rem;
    font-size: 0.6875rem; }
  button.expand, .button.expand {
    padding-right: 0;
    padding-left: 0;
    width: 100%; }
  button.left-align, .button.left-align {
    text-align: left;
    text-indent: 0.75rem; }
  button.right-align, .button.right-align {
    text-align: right;
    padding-right: 0.75rem; }
  button.radius, .button.radius {
    border-radius: 3px; }
  button.round, .button.round {
    border-radius: 1000px; }
  button.disabled, button[disabled], .button.disabled, .button[disabled] {
    background-color: #1f5c87;
    border-color: #cc8100;
    color: #FFFFFF;
    cursor: default;
    opacity: 0.7;
    box-shadow: none; }
    button.disabled:hover, button.disabled:focus, button[disabled]:hover, button[disabled]:focus, .button.disabled:hover, .button.disabled:focus, .button[disabled]:hover, .button[disabled]:focus {
      background-color: #cc8100; }
    button.disabled:hover, button.disabled:focus, button[disabled]:hover, button[disabled]:focus, .button.disabled:hover, .button.disabled:focus, .button[disabled]:hover, .button[disabled]:focus {
      color: #FFFFFF; }
    button.disabled:hover, button.disabled:focus, button[disabled]:hover, button[disabled]:focus, .button.disabled:hover, .button.disabled:focus, .button[disabled]:hover, .button[disabled]:focus {
      background-color: #1f5c87; }
    button.disabled.secondary, button[disabled].secondary, .button.disabled.secondary, .button[disabled].secondary {
      background-color: #E7E7E7;
      border-color: #b9b9b9;
      color: #333333;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.secondary:hover, button.disabled.secondary:focus, button[disabled].secondary:hover, button[disabled].secondary:focus, .button.disabled.secondary:hover, .button.disabled.secondary:focus, .button[disabled].secondary:hover, .button[disabled].secondary:focus {
        background-color: #b9b9b9; }
      button.disabled.secondary:hover, button.disabled.secondary:focus, button[disabled].secondary:hover, button[disabled].secondary:focus, .button.disabled.secondary:hover, .button.disabled.secondary:focus, .button[disabled].secondary:hover, .button[disabled].secondary:focus {
        color: #333333; }
      button.disabled.secondary:hover, button.disabled.secondary:focus, button[disabled].secondary:hover, button[disabled].secondary:focus, .button.disabled.secondary:hover, .button.disabled.secondary:focus, .button[disabled].secondary:hover, .button[disabled].secondary:focus {
        background-color: #E7E7E7; }
    button.disabled.success, button[disabled].success, .button.disabled.success, .button[disabled].success {
      background-color: #43AC6A;
      border-color: #368a55;
      color: #FFFFFF;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.success:hover, button.disabled.success:focus, button[disabled].success:hover, button[disabled].success:focus, .button.disabled.success:hover, .button.disabled.success:focus, .button[disabled].success:hover, .button[disabled].success:focus {
        background-color: #368a55; }
      button.disabled.success:hover, button.disabled.success:focus, button[disabled].success:hover, button[disabled].success:focus, .button.disabled.success:hover, .button.disabled.success:focus, .button[disabled].success:hover, .button[disabled].success:focus {
        color: #FFFFFF; }
      button.disabled.success:hover, button.disabled.success:focus, button[disabled].success:hover, button[disabled].success:focus, .button.disabled.success:hover, .button.disabled.success:focus, .button[disabled].success:hover, .button[disabled].success:focus {
        background-color: #43AC6A; }
    button.disabled.alert, button[disabled].alert, .button.disabled.alert, .button[disabled].alert {
      background-color: #f04124;
      border-color: #cf2a0e;
      color: #FFFFFF;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.alert:hover, button.disabled.alert:focus, button[disabled].alert:hover, button[disabled].alert:focus, .button.disabled.alert:hover, .button.disabled.alert:focus, .button[disabled].alert:hover, .button[disabled].alert:focus {
        background-color: #cf2a0e; }
      button.disabled.alert:hover, button.disabled.alert:focus, button[disabled].alert:hover, button[disabled].alert:focus, .button.disabled.alert:hover, .button.disabled.alert:focus, .button[disabled].alert:hover, .button[disabled].alert:focus {
        color: #FFFFFF; }
      button.disabled.alert:hover, button.disabled.alert:focus, button[disabled].alert:hover, button[disabled].alert:focus, .button.disabled.alert:hover, .button.disabled.alert:focus, .button[disabled].alert:hover, .button[disabled].alert:focus {
        background-color: #f04124; }
    button.disabled.warning, button[disabled].warning, .button.disabled.warning, .button[disabled].warning {
      background-color: #f08a24;
      border-color: #cf6e0e;
      color: #FFFFFF;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.warning:hover, button.disabled.warning:focus, button[disabled].warning:hover, button[disabled].warning:focus, .button.disabled.warning:hover, .button.disabled.warning:focus, .button[disabled].warning:hover, .button[disabled].warning:focus {
        background-color: #cf6e0e; }
      button.disabled.warning:hover, button.disabled.warning:focus, button[disabled].warning:hover, button[disabled].warning:focus, .button.disabled.warning:hover, .button.disabled.warning:focus, .button[disabled].warning:hover, .button[disabled].warning:focus {
        color: #FFFFFF; }
      button.disabled.warning:hover, button.disabled.warning:focus, button[disabled].warning:hover, button[disabled].warning:focus, .button.disabled.warning:hover, .button.disabled.warning:focus, .button[disabled].warning:hover, .button[disabled].warning:focus {
        background-color: #f08a24; }
    button.disabled.info, button[disabled].info, .button.disabled.info, .button[disabled].info {
      background-color: #a0d3e8;
      border-color: #61b6d9;
      color: #333333;
      cursor: default;
      opacity: 0.7;
      box-shadow: none; }
      button.disabled.info:hover, button.disabled.info:focus, button[disabled].info:hover, button[disabled].info:focus, .button.disabled.info:hover, .button.disabled.info:focus, .button[disabled].info:hover, .button[disabled].info:focus {
        background-color: #61b6d9; }
      button.disabled.info:hover, button.disabled.info:focus, button[disabled].info:hover, button[disabled].info:focus, .button.disabled.info:hover, .button.disabled.info:focus, .button[disabled].info:hover, .button[disabled].info:focus {
        color: #FFFFFF; }
      button.disabled.info:hover, button.disabled.info:focus, button[disabled].info:hover, button[disabled].info:focus, .button.disabled.info:hover, .button.disabled.info:focus, .button[disabled].info:hover, .button[disabled].info:focus {
        background-color: #a0d3e8; }

button::-moz-focus-inner {
  border: 0;
  padding: 0; }

@media only screen and (min-width:40.063em) {
  button, .button {
    display: inline-block; } }

.button-group {
  list-style: none;
  margin: 0;
  left: 0; }
  .button-group:before, .button-group:after {
    content: " ";
    display: table; }
  .button-group:after {
    clear: both; }
  .button-group.even-2 li {
    margin: 0 -2px;
    display: inline-block;
    width: 50%; }
    .button-group.even-2 li > button, .button-group.even-2 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-2 li:first-child button, .button-group.even-2 li:first-child .button {
      border-left: 0; }
    .button-group.even-2 li button, .button-group.even-2 li .button {
      width: 100%; }
  .button-group.even-3 li {
    margin: 0 -2px;
    display: inline-block;
    width: 33.3333333333%; }
    .button-group.even-3 li > button, .button-group.even-3 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-3 li:first-child button, .button-group.even-3 li:first-child .button {
      border-left: 0; }
    .button-group.even-3 li button, .button-group.even-3 li .button {
      width: 100%; }
  .button-group.even-4 li {
    margin: 0 -2px;
    display: inline-block;
    width: 25%; }
    .button-group.even-4 li > button, .button-group.even-4 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-4 li:first-child button, .button-group.even-4 li:first-child .button {
      border-left: 0; }
    .button-group.even-4 li button, .button-group.even-4 li .button {
      width: 100%; }
  .button-group.even-5 li {
    margin: 0 -2px;
    display: inline-block;
    width: 20%; }
    .button-group.even-5 li > button, .button-group.even-5 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-5 li:first-child button, .button-group.even-5 li:first-child .button {
      border-left: 0; }
    .button-group.even-5 li button, .button-group.even-5 li .button {
      width: 100%; }
  .button-group.even-6 li {
    margin: 0 -2px;
    display: inline-block;
    width: 16.6666666667%; }
    .button-group.even-6 li > button, .button-group.even-6 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-6 li:first-child button, .button-group.even-6 li:first-child .button {
      border-left: 0; }
    .button-group.even-6 li button, .button-group.even-6 li .button {
      width: 100%; }
  .button-group.even-7 li {
    margin: 0 -2px;
    display: inline-block;
    width: 14.2857142857%; }
    .button-group.even-7 li > button, .button-group.even-7 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-7 li:first-child button, .button-group.even-7 li:first-child .button {
      border-left: 0; }
    .button-group.even-7 li button, .button-group.even-7 li .button {
      width: 100%; }
  .button-group.even-8 li {
    margin: 0 -2px;
    display: inline-block;
    width: 12.5%; }
    .button-group.even-8 li > button, .button-group.even-8 li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.even-8 li:first-child button, .button-group.even-8 li:first-child .button {
      border-left: 0; }
    .button-group.even-8 li button, .button-group.even-8 li .button {
      width: 100%; }
  .button-group > li {
    margin: 0 -2px;
    display: inline-block; }
    .button-group > li > button, .button-group > li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group > li:first-child button, .button-group > li:first-child .button {
      border-left: 0; }
  .button-group.stack > li {
    margin: 0 -2px;
    display: inline-block;
    display: block;
    margin: 0;
    float: none; }
    .button-group.stack > li > button, .button-group.stack > li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.stack > li:first-child button, .button-group.stack > li:first-child .button {
      border-left: 0; }
    .button-group.stack > li > button, .button-group.stack > li .button {
      border-top: 1px solid;
      border-color: rgba(255, 255, 255, 0.5);
      border-left-width: 0;
      margin: 0;
      display: block; }
    .button-group.stack > li > button {
      width: 100%; }
    .button-group.stack > li:first-child button, .button-group.stack > li:first-child .button {
      border-top: 0; }
  .button-group.stack-for-small > li {
    margin: 0 -2px;
    display: inline-block; }
    .button-group.stack-for-small > li > button, .button-group.stack-for-small > li .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.stack-for-small > li:first-child button, .button-group.stack-for-small > li:first-child .button {
      border-left: 0; }
    @media only screen and (max-width: 40em) {
      .button-group.stack-for-small > li {
        margin: 0 -2px;
        display: inline-block;
        display: block;
        margin: 0; }
        .button-group.stack-for-small > li > button, .button-group.stack-for-small > li .button {
          border-left: 1px solid;
          border-color: rgba(255, 255, 255, 0.5); }
        .button-group.stack-for-small > li:first-child button, .button-group.stack-for-small > li:first-child .button {
          border-left: 0; }
        .button-group.stack-for-small > li > button, .button-group.stack-for-small > li .button {
          border-top: 1px solid;
          border-color: rgba(255, 255, 255, 0.5);
          border-left-width: 0;
          margin: 0;
          display: block; }
        .button-group.stack-for-small > li > button {
          width: 100%; }
        .button-group.stack-for-small > li:first-child button, .button-group.stack-for-small > li:first-child .button {
          border-top: 0; } }
  .button-group.radius > * {
    margin: 0 -2px;
    display: inline-block; }
    .button-group.radius > * > button, .button-group.radius > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.radius > *:first-child button, .button-group.radius > *:first-child .button {
      border-left: 0; }
    .button-group.radius > *, .button-group.radius > * > a, .button-group.radius > * > button, .button-group.radius > * > .button {
      border-radius: 0; }
    .button-group.radius > *:first-child, .button-group.radius > *:first-child > a, .button-group.radius > *:first-child > button, .button-group.radius > *:first-child > .button {
      -webkit-border-bottom-left-radius: 3px;
      -webkit-border-top-left-radius: 3px;
      border-bottom-left-radius: 3px;
      border-top-left-radius: 3px; }
    .button-group.radius > *:last-child, .button-group.radius > *:last-child > a, .button-group.radius > *:last-child > button, .button-group.radius > *:last-child > .button {
      -webkit-border-bottom-right-radius: 3px;
      -webkit-border-top-right-radius: 3px;
      border-bottom-right-radius: 3px;
      border-top-right-radius: 3px; }
  .button-group.radius.stack > * {
    margin: 0 -2px;
    display: inline-block;
    display: block;
    margin: 0; }
    .button-group.radius.stack > * > button, .button-group.radius.stack > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.radius.stack > *:first-child button, .button-group.radius.stack > *:first-child .button {
      border-left: 0; }
    .button-group.radius.stack > * > button, .button-group.radius.stack > * .button {
      border-top: 1px solid;
      border-color: rgba(255, 255, 255, 0.5);
      border-left-width: 0;
      margin: 0;
      display: block; }
    .button-group.radius.stack > * > button {
      width: 100%; }
    .button-group.radius.stack > *:first-child button, .button-group.radius.stack > *:first-child .button {
      border-top: 0; }
    .button-group.radius.stack > *, .button-group.radius.stack > * > a, .button-group.radius.stack > * > button, .button-group.radius.stack > * > .button {
      border-radius: 0; }
    .button-group.radius.stack > *:first-child, .button-group.radius.stack > *:first-child > a, .button-group.radius.stack > *:first-child > button, .button-group.radius.stack > *:first-child > .button {
      -webkit-top-left-radius: 3px;
      -webkit-top-right-radius: 3px;
      border-top-left-radius: 3px;
      border-top-right-radius: 3px; }
    .button-group.radius.stack > *:last-child, .button-group.radius.stack > *:last-child > a, .button-group.radius.stack > *:last-child > button, .button-group.radius.stack > *:last-child > .button {
      -webkit-bottom-left-radius: 3px;
      -webkit-bottom-right-radius: 3px;
      border-bottom-left-radius: 3px;
      border-bottom-right-radius: 3px; }
  @media only screen and (min-width:40.063em) {
    .button-group.radius.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block; }
      .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.radius.stack-for-small > *:first-child button, .button-group.radius.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.radius.stack-for-small > *, .button-group.radius.stack-for-small > * > a, .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.radius.stack-for-small > *:first-child, .button-group.radius.stack-for-small > *:first-child > a, .button-group.radius.stack-for-small > *:first-child > button, .button-group.radius.stack-for-small > *:first-child > .button {
        -webkit-border-bottom-left-radius: 3px;
        -webkit-border-top-left-radius: 3px;
        border-bottom-left-radius: 3px;
        border-top-left-radius: 3px; }
      .button-group.radius.stack-for-small > *:last-child, .button-group.radius.stack-for-small > *:last-child > a, .button-group.radius.stack-for-small > *:last-child > button, .button-group.radius.stack-for-small > *:last-child > .button {
        -webkit-border-bottom-right-radius: 3px;
        -webkit-border-top-right-radius: 3px;
        border-bottom-right-radius: 3px;
        border-top-right-radius: 3px; } }
  @media only screen and (max-width: 40em) {
    .button-group.radius.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block;
      display: block;
      margin: 0; }
      .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.radius.stack-for-small > *:first-child button, .button-group.radius.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * .button {
        border-top: 1px solid;
        border-color: rgba(255, 255, 255, 0.5);
        border-left-width: 0;
        margin: 0;
        display: block; }
      .button-group.radius.stack-for-small > * > button {
        width: 100%; }
      .button-group.radius.stack-for-small > *:first-child button, .button-group.radius.stack-for-small > *:first-child .button {
        border-top: 0; }
      .button-group.radius.stack-for-small > *, .button-group.radius.stack-for-small > * > a, .button-group.radius.stack-for-small > * > button, .button-group.radius.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.radius.stack-for-small > *:first-child, .button-group.radius.stack-for-small > *:first-child > a, .button-group.radius.stack-for-small > *:first-child > button, .button-group.radius.stack-for-small > *:first-child > .button {
        -webkit-top-left-radius: 3px;
        -webkit-top-right-radius: 3px;
        border-top-left-radius: 3px;
        border-top-right-radius: 3px; }
      .button-group.radius.stack-for-small > *:last-child, .button-group.radius.stack-for-small > *:last-child > a, .button-group.radius.stack-for-small > *:last-child > button, .button-group.radius.stack-for-small > *:last-child > .button {
        -webkit-bottom-left-radius: 3px;
        -webkit-bottom-right-radius: 3px;
        border-bottom-left-radius: 3px;
        border-bottom-right-radius: 3px; } }
  .button-group.round > * {
    margin: 0 -2px;
    display: inline-block; }
    .button-group.round > * > button, .button-group.round > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.round > *:first-child button, .button-group.round > *:first-child .button {
      border-left: 0; }
    .button-group.round > *, .button-group.round > * > a, .button-group.round > * > button, .button-group.round > * > .button {
      border-radius: 0; }
    .button-group.round > *:first-child, .button-group.round > *:first-child > a, .button-group.round > *:first-child > button, .button-group.round > *:first-child > .button {
      -webkit-border-bottom-left-radius: 1000px;
      -webkit-border-top-left-radius: 1000px;
      border-bottom-left-radius: 1000px;
      border-top-left-radius: 1000px; }
    .button-group.round > *:last-child, .button-group.round > *:last-child > a, .button-group.round > *:last-child > button, .button-group.round > *:last-child > .button {
      -webkit-border-bottom-right-radius: 1000px;
      -webkit-border-top-right-radius: 1000px;
      border-bottom-right-radius: 1000px;
      border-top-right-radius: 1000px; }
  .button-group.round.stack > * {
    margin: 0 -2px;
    display: inline-block;
    display: block;
    margin: 0; }
    .button-group.round.stack > * > button, .button-group.round.stack > * .button {
      border-left: 1px solid;
      border-color: rgba(255, 255, 255, 0.5); }
    .button-group.round.stack > *:first-child button, .button-group.round.stack > *:first-child .button {
      border-left: 0; }
    .button-group.round.stack > * > button, .button-group.round.stack > * .button {
      border-top: 1px solid;
      border-color: rgba(255, 255, 255, 0.5);
      border-left-width: 0;
      margin: 0;
      display: block; }
    .button-group.round.stack > * > button {
      width: 100%; }
    .button-group.round.stack > *:first-child button, .button-group.round.stack > *:first-child .button {
      border-top: 0; }
    .button-group.round.stack > *, .button-group.round.stack > * > a, .button-group.round.stack > * > button, .button-group.round.stack > * > .button {
      border-radius: 0; }
    .button-group.round.stack > *:first-child, .button-group.round.stack > *:first-child > a, .button-group.round.stack > *:first-child > button, .button-group.round.stack > *:first-child > .button {
      -webkit-top-left-radius: 1rem;
      -webkit-top-right-radius: 1rem;
      border-top-left-radius: 1rem;
      border-top-right-radius: 1rem; }
    .button-group.round.stack > *:last-child, .button-group.round.stack > *:last-child > a, .button-group.round.stack > *:last-child > button, .button-group.round.stack > *:last-child > .button {
      -webkit-bottom-left-radius: 1rem;
      -webkit-bottom-right-radius: 1rem;
      border-bottom-left-radius: 1rem;
      border-bottom-right-radius: 1rem; }
  @media only screen and (min-width:40.063em) {
    .button-group.round.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block; }
      .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.round.stack-for-small > *:first-child button, .button-group.round.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.round.stack-for-small > *, .button-group.round.stack-for-small > * > a, .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.round.stack-for-small > *:first-child, .button-group.round.stack-for-small > *:first-child > a, .button-group.round.stack-for-small > *:first-child > button, .button-group.round.stack-for-small > *:first-child > .button {
        -webkit-border-bottom-left-radius: 1000px;
        -webkit-border-top-left-radius: 1000px;
        border-bottom-left-radius: 1000px;
        border-top-left-radius: 1000px; }
      .button-group.round.stack-for-small > *:last-child, .button-group.round.stack-for-small > *:last-child > a, .button-group.round.stack-for-small > *:last-child > button, .button-group.round.stack-for-small > *:last-child > .button {
        -webkit-border-bottom-right-radius: 1000px;
        -webkit-border-top-right-radius: 1000px;
        border-bottom-right-radius: 1000px;
        border-top-right-radius: 1000px; } }
  @media only screen and (max-width: 40em) {
    .button-group.round.stack-for-small > * {
      margin: 0 -2px;
      display: inline-block;
      display: block;
      margin: 0; }
      .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * .button {
        border-left: 1px solid;
        border-color: rgba(255, 255, 255, 0.5); }
      .button-group.round.stack-for-small > *:first-child button, .button-group.round.stack-for-small > *:first-child .button {
        border-left: 0; }
      .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * .button {
        border-top: 1px solid;
        border-color: rgba(255, 255, 255, 0.5);
        border-left-width: 0;
        margin: 0;
        display: block; }
      .button-group.round.stack-for-small > * > button {
        width: 100%; }
      .button-group.round.stack-for-small > *:first-child button, .button-group.round.stack-for-small > *:first-child .button {
        border-top: 0; }
      .button-group.round.stack-for-small > *, .button-group.round.stack-for-small > * > a, .button-group.round.stack-for-small > * > button, .button-group.round.stack-for-small > * > .button {
        border-radius: 0; }
      .button-group.round.stack-for-small > *:first-child, .button-group.round.stack-for-small > *:first-child > a, .button-group.round.stack-for-small > *:first-child > button, .button-group.round.stack-for-small > *:first-child > .button {
        -webkit-top-left-radius: 1rem;
        -webkit-top-right-radius: 1rem;
        border-top-left-radius: 1rem;
        border-top-right-radius: 1rem; }
      .button-group.round.stack-for-small > *:last-child, .button-group.round.stack-for-small > *:last-child > a, .button-group.round.stack-for-small > *:last-child > button, .button-group.round.stack-for-small > *:last-child > .button {
        -webkit-bottom-left-radius: 1rem;
        -webkit-bottom-right-radius: 1rem;
        border-bottom-left-radius: 1rem;
        border-bottom-right-radius: 1rem; } }

.button-bar:before, .button-bar:after {
  content: " ";
  display: table; }
.button-bar:after {
  clear: both; }
.button-bar .button-group {
  float: left;
  margin-right: 0.625rem; }
  .button-bar .button-group div {
    overflow: hidden; }

/* Clearing Styles */
.clearing-thumbs, [data-clearing] {
  margin-bottom: 0;
  margin-left: 0;
  list-style: none; }
  .clearing-thumbs:before, .clearing-thumbs:after, [data-clearing]:before, [data-clearing]:after {
    content: " ";
    display: table; }
  .clearing-thumbs:after, [data-clearing]:after {
    clear: both; }
  .clearing-thumbs li, [data-clearing] li {
    float: left;
    margin-right: 10px; }
  .clearing-thumbs[class*="block-grid-"] li, [data-clearing][class*="block-grid-"] li {
    margin-right: 0; }

.clearing-blackout {
  background: #333333;
  position: fixed;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  z-index: 998; }
  .clearing-blackout .clearing-close {
    display: block; }

.clearing-container {
  position: relative;
  z-index: 998;
  height: 100%;
  overflow: hidden;
  margin: 0; }

.clearing-touch-label {
  position: absolute;
  top: 50%;
  left: 50%;
  color: #AAAAAA;
  font-size: 0.6em; }

.visible-img {
  height: 95%;
  position: relative; }
  .visible-img img {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translateY(-50%) translateX(-50%);
    -webkit-transform: translateY(-50%) translateX(-50%);
    -ms-transform: translateY(-50%) translateX(-50%);
    max-height: 100%;
    max-width: 100%; }

.clearing-caption {
  color: #565656;
  font-size: 0.875em;
  line-height: 1.3;
  margin-bottom: 0;
  text-align: center;
  bottom: 0;
  background: #333333;
  width: 100%;
  padding: 10px 30px 20px;
  position: absolute;
  left: 0; }

.clearing-close {
  z-index: 999;
  padding-left: 20px;
  padding-top: 10px;
  font-size: 30px;
  line-height: 1;
  color: #565656;
  display: none; }
  .clearing-close:hover, .clearing-close:focus {
    color: #565656; }

.clearing-assembled .clearing-container {
  height: 100%; }
  .clearing-assembled .clearing-container .carousel > ul {
    display: none; }

.clearing-feature li {
  display: none; }
  .clearing-feature li.clearing-featured-img {
    display: block; }

@media only screen and (min-width:40.063em) {
  .clearing-main-prev, .clearing-main-next {
    position: absolute;
    height: 100%;
    width: 40px;
    top: 0; }
    .clearing-main-prev > span, .clearing-main-next > span {
      position: absolute;
      top: 50%;
      display: block;
      width: 0;
      height: 0;
      border: solid 12px; }
      .clearing-main-prev > span:hover, .clearing-main-next > span:hover {
        opacity: 0.8; }
  .clearing-main-prev {
    left: 0; }
    .clearing-main-prev > span {
      left: 5px;
      border-color: transparent;
      border-right-color: #565656; }
  .clearing-main-next {
    right: 0; }
    .clearing-main-next > span {
      border-color: transparent;
      border-left-color: #565656; }
  .clearing-main-prev.disabled, .clearing-main-next.disabled {
    opacity: 0.3; }
  .clearing-assembled .clearing-container .carousel {
    background: rgba(51, 51, 51, 0.8);
    height: 120px;
    margin-top: 10px;
    text-align: center; }
    .clearing-assembled .clearing-container .carousel > ul {
      display: inline-block;
      z-index: 999;
      height: 100%;
      position: relative;
      float: none; }
      .clearing-assembled .clearing-container .carousel > ul li {
        display: block;
        width: 120px;
        min-height: inherit;
        float: left;
        overflow: hidden;
        margin-right: 0;
        padding: 0;
        position: relative;
        cursor: pointer;
        opacity: 0.4;
        clear: none; }
        .clearing-assembled .clearing-container .carousel > ul li.fix-height img {
          height: 100%;
          max-width: none; }
        .clearing-assembled .clearing-container .carousel > ul li a.th {
          border: none;
          box-shadow: none;
          display: block; }
        .clearing-assembled .clearing-container .carousel > ul li img {
          cursor: pointer !important;
          width: 100% !important; }
        .clearing-assembled .clearing-container .carousel > ul li.visible {
          opacity: 1; }
        .clearing-assembled .clearing-container .carousel > ul li:hover {
          opacity: 0.8; }
  .clearing-assembled .clearing-container .visible-img {
    background: #333333;
    overflow: hidden;
    height: 85%; }
  .clearing-close {
    position: absolute;
    top: 10px;
    right: 20px;
    padding-left: 0;
    padding-top: 0; } }

/* Foundation Dropdowns */
.f-dropdown {
  position: absolute;
  left: -9999px;
  list-style: none;
  margin-left: 0;
  outline: none;
  width: 100%;
  max-height: none;
  height: auto;
  background: #FFFFFF;
  border: solid 1px #cccccc;
  font-size: 0.875rem;
  z-index: 89;
  margin-top: 2px;
  max-width: 200px; }
  .f-dropdown > *:first-child {
    margin-top: 0; }
  .f-dropdown > *:last-child {
    margin-bottom: 0; }
  .f-dropdown:before {
    content: "";
    display: block;
    width: 0;
    height: 0;
    border: inset 6px;
    border-color: transparent transparent #FFFFFF transparent;
    border-bottom-style: solid;
    position: absolute;
    top: -12px;
    left: 10px;
    z-index: 89; }
  .f-dropdown:after {
    content: "";
    display: block;
    width: 0;
    height: 0;
    border: inset 7px;
    border-color: transparent transparent #cccccc transparent;
    border-bottom-style: solid;
    position: absolute;
    top: -14px;
    left: 9px;
    z-index: 88; }
  .f-dropdown.right:before {
    left: auto;
    right: 10px; }
  .f-dropdown.right:after {
    left: auto;
    right: 9px; }
  .f-dropdown.drop-right {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    width: 100%;
    max-height: none;
    height: auto;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    margin-top: 0;
    margin-left: 2px;
    max-width: 200px; }
    .f-dropdown.drop-right > *:first-child {
      margin-top: 0; }
    .f-dropdown.drop-right > *:last-child {
      margin-bottom: 0; }
    .f-dropdown.drop-right:before {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 6px;
      border-color: transparent #FFFFFF transparent transparent;
      border-right-style: solid;
      position: absolute;
      top: 10px;
      left: -12px;
      z-index: 89; }
    .f-dropdown.drop-right:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 7px;
      border-color: transparent #cccccc transparent transparent;
      border-right-style: solid;
      position: absolute;
      top: 9px;
      left: -14px;
      z-index: 88; }
  .f-dropdown.drop-left {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    width: 100%;
    max-height: none;
    height: auto;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    margin-top: 0;
    margin-left: -2px;
    max-width: 200px; }
    .f-dropdown.drop-left > *:first-child {
      margin-top: 0; }
    .f-dropdown.drop-left > *:last-child {
      margin-bottom: 0; }
    .f-dropdown.drop-left:before {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 6px;
      border-color: transparent transparent transparent #FFFFFF;
      border-left-style: solid;
      position: absolute;
      top: 10px;
      right: -12px;
      left: auto;
      z-index: 89; }
    .f-dropdown.drop-left:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 7px;
      border-color: transparent transparent transparent #cccccc;
      border-left-style: solid;
      position: absolute;
      top: 9px;
      right: -14px;
      left: auto;
      z-index: 88; }
  .f-dropdown.drop-top {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    width: 100%;
    max-height: none;
    height: auto;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    margin-top: -2px;
    margin-left: 0;
    max-width: 200px; }
    .f-dropdown.drop-top > *:first-child {
      margin-top: 0; }
    .f-dropdown.drop-top > *:last-child {
      margin-bottom: 0; }
    .f-dropdown.drop-top:before {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 6px;
      border-color: #FFFFFF transparent transparent transparent;
      border-top-style: solid;
      position: absolute;
      top: auto;
      bottom: -12px;
      left: 10px;
      right: auto;
      z-index: 89; }
    .f-dropdown.drop-top:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 7px;
      border-color: #cccccc transparent transparent transparent;
      border-top-style: solid;
      position: absolute;
      top: auto;
      bottom: -14px;
      left: 9px;
      right: auto;
      z-index: 88; }
  .f-dropdown li {
    font-size: 0.875rem;
    cursor: pointer;
    line-height: 1.125rem;
    margin: 0; }
    .f-dropdown li:hover, .f-dropdown li:focus {
      background: #EEEEEE; }
    .f-dropdown li.radius {
      border-radius: 3px; }
    .f-dropdown li a {
      display: block;
      padding: 0.5rem;
      color: #555555; }
  .f-dropdown.content {
    position: absolute;
    left: -9999px;
    list-style: none;
    margin-left: 0;
    outline: none;
    padding: 1.25rem;
    width: 100%;
    height: auto;
    max-height: none;
    background: #FFFFFF;
    border: solid 1px #cccccc;
    font-size: 0.875rem;
    z-index: 89;
    max-width: 200px; }
    .f-dropdown.content > *:first-child {
      margin-top: 0; }
    .f-dropdown.content > *:last-child {
      margin-bottom: 0; }
  .f-dropdown.tiny {
    max-width: 200px; }
  .f-dropdown.small {
    max-width: 300px; }
  .f-dropdown.medium {
    max-width: 500px; }
  .f-dropdown.large {
    max-width: 800px; }
  .f-dropdown.mega {
    width: 100% !important;
    max-width: 100% !important; }
    .f-dropdown.mega.open {
      left: 0 !important; }

.dropdown.button, button.dropdown {
  position: relative;
  outline: none;
  padding-right: 3.5625rem; }
  .dropdown.button::after, button.dropdown::after {
    position: absolute;
    content: "";
    width: 0;
    height: 0;
    display: block;
    border-style: solid;
    border-color: #FFFFFF transparent transparent transparent;
    top: 50%; }
  .dropdown.button::after, button.dropdown::after {
    border-width: 0.375rem;
    right: 1.40625rem;
    margin-top: -0.15625rem; }
  .dropdown.button::after, button.dropdown::after {
    border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.tiny, button.dropdown.tiny {
    padding-right: 2.625rem; }
    .dropdown.button.tiny:after, button.dropdown.tiny:after {
      border-width: 0.375rem;
      right: 1.125rem;
      margin-top: -0.125rem; }
    .dropdown.button.tiny::after, button.dropdown.tiny::after {
      border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.small, button.dropdown.small {
    padding-right: 3.0625rem; }
    .dropdown.button.small::after, button.dropdown.small::after {
      border-width: 0.4375rem;
      right: 1.3125rem;
      margin-top: -0.15625rem; }
    .dropdown.button.small::after, button.dropdown.small::after {
      border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.large, button.dropdown.large {
    padding-right: 3.625rem; }
    .dropdown.button.large::after, button.dropdown.large::after {
      border-width: 0.3125rem;
      right: 1.71875rem;
      margin-top: -0.15625rem; }
    .dropdown.button.large::after, button.dropdown.large::after {
      border-color: #FFFFFF transparent transparent transparent; }
  .dropdown.button.secondary:after, button.dropdown.secondary:after {
    border-color: #333333 transparent transparent transparent; }

.flex-video {
  position: relative;
  padding-top: 1.5625rem;
  padding-bottom: 67.5%;
  height: 0;
  margin-bottom: 1rem;
  overflow: hidden; }
  .flex-video.widescreen {
    padding-bottom: 56.34%; }
  .flex-video.vimeo {
    padding-top: 0; }
  .flex-video iframe, .flex-video object, .flex-video embed, .flex-video video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%; }

/* Standard Forms */
form {
  margin: 0 0 1rem; }

/* Using forms within rows, we need to set some defaults */
form .row .row {
  margin: 0 -0.5rem; }
  form .row .row .column, form .row .row .columns {
    padding: 0 0.5rem; }
  form .row .row.collapse {
    margin: 0; }
    form .row .row.collapse .column, form .row .row.collapse .columns {
      padding: 0; }
    form .row .row.collapse input {
      -webkit-border-bottom-right-radius: 0;
      -webkit-border-top-right-radius: 0;
      border-bottom-right-radius: 0;
      border-top-right-radius: 0; }
form .row input.column, form .row input.columns, form .row textarea.column, form .row textarea.columns {
  padding-left: 0.5rem; }

/* Label Styles */
label {
  font-size: 0.875rem;
  color: #4d4d4d;
  cursor: pointer;
  display: block;
  font-weight: 400;
  line-height: 1.5;
  margin-bottom: 0;
  /* Styles for required inputs */ }
  label.right {
    float: none !important;
    text-align: right; }
  label.inline {
    margin: 0 0 1rem 0;
    padding: 0.5625rem 0; }
  label small {
    text-transform: capitalize;
    color: #676767; }

/* Attach elements to the beginning or end of an input */
.prefix, .postfix {
  display: block;
  position: relative;
  z-index: 2;
  text-align: center;
  width: 100%;
  padding-top: 0;
  padding-bottom: 0;
  border-style: solid;
  border-width: 1px;
  overflow: visible;
  font-size: 0.875rem;
  height: 2.3125rem;
  line-height: 2.3125rem; }

/* Adjust padding, alignment and radius if pre/post element is a button */
.postfix.button {
  padding-left: 0;
  padding-right: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
  border: none; }

.prefix.button {
  padding-left: 0;
  padding-right: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
  border: none; }

.prefix.button.radius {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }

.postfix.button.radius {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 3px;
  -webkit-border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }

.prefix.button.round {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 1000px;
  -webkit-border-top-left-radius: 1000px;
  border-bottom-left-radius: 1000px;
  border-top-left-radius: 1000px; }

.postfix.button.round {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 1000px;
  -webkit-border-top-right-radius: 1000px;
  border-bottom-right-radius: 1000px;
  border-top-right-radius: 1000px; }

/* Separate prefix and postfix styles when on span or label so buttons keep their own */
span.prefix, label.prefix {
  background: #f2f2f2;
  border-right: none;
  color: #333333;
  border-color: #cccccc; }

span.postfix, label.postfix {
  background: #f2f2f2;
  border-left: none;
  color: #333333;
  border-color: #cccccc; }

/* We use this to get basic styling on all basic form elements */
input[type="text"], input[type="password"], input[type="date"], input[type="datetime"], input[type="datetime-local"], input[type="month"], input[type="week"], input[type="email"], input[type="number"], input[type="search"], input[type="tel"], input[type="time"], input[type="url"], input[type="color"], textarea {
  -webkit-appearance: none;
  border-radius: 0;
  background-color: #FFFFFF;
  font-family: inherit;
  border-style: solid;
  border-width: 1px;
  border-color: #cccccc;
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  color: rgba(0, 0, 0, 0.75);
  display: block;
  font-size: 0.875rem;
  margin: 0 0 1rem 0;
  padding: 0.5rem;
  height: 2.3125rem;
  width: 100%;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  transition: all 0.15s linear; }
  input[type="text"]:focus, input[type="password"]:focus, input[type="date"]:focus, input[type="datetime"]:focus, input[type="datetime-local"]:focus, input[type="month"]:focus, input[type="week"]:focus, input[type="email"]:focus, input[type="number"]:focus, input[type="search"]:focus, input[type="tel"]:focus, input[type="time"]:focus, input[type="url"]:focus, input[type="color"]:focus, textarea:focus {
    background: #fafafa;
    border-color: #999999;
    outline: none; }
  input[type="text"]:disabled, input[type="password"]:disabled, input[type="date"]:disabled, input[type="datetime"]:disabled, input[type="datetime-local"]:disabled, input[type="month"]:disabled, input[type="week"]:disabled, input[type="email"]:disabled, input[type="number"]:disabled, input[type="search"]:disabled, input[type="tel"]:disabled, input[type="time"]:disabled, input[type="url"]:disabled, input[type="color"]:disabled, textarea:disabled {
    background-color: #DDDDDD;
    cursor: default; }
  input[type="text"][disabled], input[type="text"][readonly], fieldset[disabled] input[type="text"], input[type="password"][disabled], input[type="password"][readonly], fieldset[disabled] input[type="password"], input[type="date"][disabled], input[type="date"][readonly], fieldset[disabled] input[type="date"], input[type="datetime"][disabled], input[type="datetime"][readonly], fieldset[disabled] input[type="datetime"], input[type="datetime-local"][disabled], input[type="datetime-local"][readonly], fieldset[disabled] input[type="datetime-local"], input[type="month"][disabled], input[type="month"][readonly], fieldset[disabled] input[type="month"], input[type="week"][disabled], input[type="week"][readonly], fieldset[disabled] input[type="week"], input[type="email"][disabled], input[type="email"][readonly], fieldset[disabled] input[type="email"], input[type="number"][disabled], input[type="number"][readonly], fieldset[disabled] input[type="number"], input[type="search"][disabled], input[type="search"][readonly], fieldset[disabled] input[type="search"], input[type="tel"][disabled], input[type="tel"][readonly], fieldset[disabled] input[type="tel"], input[type="time"][disabled], input[type="time"][readonly], fieldset[disabled] input[type="time"], input[type="url"][disabled], input[type="url"][readonly], fieldset[disabled] input[type="url"], input[type="color"][disabled], input[type="color"][readonly], fieldset[disabled] input[type="color"], textarea[disabled], textarea[readonly], fieldset[disabled] textarea {
    background-color: #DDDDDD;
    cursor: default; }
  input[type="text"].radius, input[type="password"].radius, input[type="date"].radius, input[type="datetime"].radius, input[type="datetime-local"].radius, input[type="month"].radius, input[type="week"].radius, input[type="email"].radius, input[type="number"].radius, input[type="search"].radius, input[type="tel"].radius, input[type="time"].radius, input[type="url"].radius, input[type="color"].radius, textarea.radius {
    border-radius: 3px; }

form .row .prefix-radius.row.collapse input, form .row .prefix-radius.row.collapse textarea, form .row .prefix-radius.row.collapse select, form .row .prefix-radius.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 3px;
  -webkit-border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }
form .row .prefix-radius.row.collapse .prefix {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }
form .row .postfix-radius.row.collapse input, form .row .postfix-radius.row.collapse textarea, form .row .postfix-radius.row.collapse select, form .row .postfix-radius.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }
form .row .postfix-radius.row.collapse .postfix {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 3px;
  -webkit-border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }
form .row .prefix-round.row.collapse input, form .row .prefix-round.row.collapse textarea, form .row .prefix-round.row.collapse select, form .row .prefix-round.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 1000px;
  -webkit-border-top-right-radius: 1000px;
  border-bottom-right-radius: 1000px;
  border-top-right-radius: 1000px; }
form .row .prefix-round.row.collapse .prefix {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 1000px;
  -webkit-border-top-left-radius: 1000px;
  border-bottom-left-radius: 1000px;
  border-top-left-radius: 1000px; }
form .row .postfix-round.row.collapse input, form .row .postfix-round.row.collapse textarea, form .row .postfix-round.row.collapse select, form .row .postfix-round.row.collapse button {
  border-radius: 0;
  -webkit-border-bottom-left-radius: 1000px;
  -webkit-border-top-left-radius: 1000px;
  border-bottom-left-radius: 1000px;
  border-top-left-radius: 1000px; }
form .row .postfix-round.row.collapse .postfix {
  border-radius: 0;
  -webkit-border-bottom-right-radius: 1000px;
  -webkit-border-top-right-radius: 1000px;
  border-bottom-right-radius: 1000px;
  border-top-right-radius: 1000px; }

input[type="submit"] {
  -webkit-appearance: none;
  border-radius: 0; }

/* Respect enforced amount of rows for textarea */
textarea[rows] {
  height: auto; }

/* Not allow resize out of parent */
textarea {
  max-width: 100%; }

/* Add height value for select elements to match text input height */
select {
  -webkit-appearance: none !important;
  border-radius: 0;
  background-color: #FAFAFA;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeD0iMTJweCIgeT0iMHB4IiB3aWR0aD0iMjRweCIgaGVpZ2h0PSIzcHgiIHZpZXdCb3g9IjAgMCA2IDMiIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDYgMyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+PHBvbHlnb24gcG9pbnRzPSI1Ljk5MiwwIDIuOTkyLDMgLTAuMDA4LDAgIi8+PC9zdmc+);
  background-position: 100% center;
  background-repeat: no-repeat;
  border-style: solid;
  border-width: 1px;
  border-color: #cccccc;
  padding: 0.5rem;
  font-size: 0.875rem;
  font-family: arial, sans-serif;
  color: rgba(0, 0, 0, 0.75);
  line-height: normal;
  border-radius: 0;
  height: 2.3125rem; }
  select::-ms-expand {
    display: none; }
  select.radius {
    border-radius: 3px; }
  select:hover {
    background-color: #f3f3f3;
    border-color: #999999; }
  select:disabled {
    background-color: #DDDDDD;
    cursor: default; }
  select[multiple] {
    height: auto; }

/* Adjust margin for form elements below */
input[type="file"], input[type="checkbox"], input[type="radio"], select {
  margin: 0 0 1rem 0; }

input[type="checkbox"] + label, input[type="radio"] + label {
  display: inline-block;
  margin-left: 0.5rem;
  margin-right: 1rem;
  margin-bottom: 0;
  vertical-align: baseline; }

/* Normalize file input width */
input[type="file"] {
  width: 100%; }

/* HTML5 Number spinners settings */
/* We add basic fieldset styling */
fieldset {
  border: 1px solid #DDDDDD;
  padding: 1.25rem;
  margin: 1.125rem 0; }
  fieldset legend {
    font-weight: bold;
    background: #FFFFFF;
    padding: 0 0.1875rem;
    margin: 0;
    margin-left: -0.1875rem; }

/* Error Handling */
[data-abide] .error small.error, [data-abide] .error span.error, [data-abide] span.error, [data-abide] small.error {
  display: block;
  padding: 0.375rem 0.5625rem 0.5625rem;
  margin-top: -1px;
  margin-bottom: 1rem;
  font-size: 0.75rem;
  font-weight: 400;
  font-style: italic;
  background: #f04124;
  color: #FFFFFF; }
[data-abide] span.error, [data-abide] small.error {
  display: none; }

span.error, small.error {
  display: block;
  padding: 0.375rem 0.5625rem 0.5625rem;
  margin-top: -1px;
  margin-bottom: 1rem;
  font-size: 0.75rem;
  font-weight: 400;
  font-style: italic;
  background: #f04124;
  color: #FFFFFF; }

.error input, .error textarea, .error select {
  margin-bottom: 0; }
.error input[type="checkbox"], .error input[type="radio"] {
  margin-bottom: 1rem; }
.error label, .error label.error {
  color: #f04124; }
.error small.error {
  display: block;
  padding: 0.375rem 0.5625rem 0.5625rem;
  margin-top: -1px;
  margin-bottom: 1rem;
  font-size: 0.75rem;
  font-weight: 400;
  font-style: italic;
  background: #f04124;
  color: #FFFFFF; }
.error > label > small {
  color: #676767;
  background: transparent;
  padding: 0;
  text-transform: capitalize;
  font-style: normal;
  font-size: 60%;
  margin: 0;
  display: inline; }
.error span.error-message {
  display: block; }

input.error, textarea.error, select.error {
  margin-bottom: 0; }

label.error {
  color: #f04124; }

.icon-bar {
  width: 100%;
  font-size: 0;
  display: inline-block;
  background: #333333; }
  .icon-bar > * {
    text-align: center;
    font-size: 1rem;
    width: 25%;
    margin: 0 auto;
    display: block;
    padding: 1.25rem;
    float: left; }
    .icon-bar > * i, .icon-bar > * img {
      display: block;
      margin: 0 auto; }
      .icon-bar > * i + label, .icon-bar > * img + label {
        margin-top: .0625rem; }
    .icon-bar > * i {
      font-size: 1.875rem;
      vertical-align: middle; }
    .icon-bar > * img {
      width: 1.875rem;
      height: 1.875rem; }
  .icon-bar.label-right > * i, .icon-bar.label-right > * img {
    margin: 0 .0625rem 0 0;
    display: inline-block; }
    .icon-bar.label-right > * i + label, .icon-bar.label-right > * img + label {
      margin-top: 0; }
  .icon-bar.label-right > * label {
    display: inline-block; }
  .icon-bar.vertical.label-right > * {
    text-align: left; }
  .icon-bar.vertical, .icon-bar.small-vertical {
    height: 100%;
    width: auto; }
    .icon-bar.vertical .item, .icon-bar.small-vertical .item {
      width: auto;
      margin: auto;
      float: none; }
  @media only screen and (min-width:40.063em) {
    .icon-bar.medium-vertical {
      height: 100%;
      width: auto; }
      .icon-bar.medium-vertical .item {
        width: auto;
        margin: auto;
        float: none; } }
  @media only screen and (min-width:64.063em) {
    .icon-bar.large-vertical {
      height: 100%;
      width: auto; }
      .icon-bar.large-vertical .item {
        width: auto;
        margin: auto;
        float: none; } }
  .icon-bar > * {
    font-size: 1rem;
    padding: 1.25rem; }
    .icon-bar > * i + label, .icon-bar > * img + label {
      margin-top: .0625rem; }
    .icon-bar > * i {
      font-size: 1.875rem; }
    .icon-bar > * img {
      width: 1.875rem;
      height: 1.875rem; }
  .icon-bar > * label {
    color: #FFFFFF; }
  .icon-bar > * i {
    color: #FFFFFF; }
  .icon-bar > a:hover {
    background: #1f5c87; }
    .icon-bar > a:hover label {
      color: #FFFFFF; }
    .icon-bar > a:hover i {
      color: #FFFFFF; }
  .icon-bar > a.active {
    background: #1f5c87; }
    .icon-bar > a.active label {
      color: #FFFFFF; }
    .icon-bar > a.active i {
      color: #FFFFFF; }
  .icon-bar .item.disabled {
    opacity: 0.7;
    cursor: false;
    pointer-events: none; }
    .icon-bar .item.disabled > * {
      opacity: 0.7;
      cursor: false; }

.icon-bar.two-up .item {
  width: 50%; }
.icon-bar.two-up.vertical .item, .icon-bar.two-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.two-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.two-up.large-vertical .item {
    width: auto; } }
.icon-bar.three-up .item {
  width: 33.3333%; }
.icon-bar.three-up.vertical .item, .icon-bar.three-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.three-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.three-up.large-vertical .item {
    width: auto; } }
.icon-bar.four-up .item {
  width: 25%; }
.icon-bar.four-up.vertical .item, .icon-bar.four-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.four-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.four-up.large-vertical .item {
    width: auto; } }
.icon-bar.five-up .item {
  width: 20%; }
.icon-bar.five-up.vertical .item, .icon-bar.five-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.five-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.five-up.large-vertical .item {
    width: auto; } }
.icon-bar.six-up .item {
  width: 16.66667%; }
.icon-bar.six-up.vertical .item, .icon-bar.six-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.six-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.six-up.large-vertical .item {
    width: auto; } }
.icon-bar.seven-up .item {
  width: 14.28571%; }
.icon-bar.seven-up.vertical .item, .icon-bar.seven-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.seven-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.seven-up.large-vertical .item {
    width: auto; } }
.icon-bar.eight-up .item {
  width: 12.5%; }
.icon-bar.eight-up.vertical .item, .icon-bar.eight-up.small-vertical .item {
  width: auto; }
@media only screen and (min-width:40.063em) {
  .icon-bar.eight-up.medium-vertical .item {
    width: auto; } }
@media only screen and (min-width:64.063em) {
  .icon-bar.eight-up.large-vertical .item {
    width: auto; } }

.inline-list {
  margin: 0 auto 1.0625rem auto;
  margin-left: -1.375rem;
  margin-right: 0;
  padding: 0;
  list-style: none;
  overflow: hidden; }
  .inline-list > li {
    list-style: none;
    float: left;
    margin-left: 1.375rem;
    display: block; }
    .inline-list > li > * {
      display: block; }

/* Foundation Joyride */
.joyride-list {
  display: none; }

/* Default styles for the container */
.joyride-tip-guide {
  display: none;
  position: absolute;
  background: #333333;
  color: #FFFFFF;
  z-index: 101;
  top: 0;
  left: 2.5%;
  font-family: inherit;
  font-weight: 400;
  width: 95%; }

.lt-ie9 .joyride-tip-guide {
  max-width: 800px;
  left: 50%;
  margin-left: -400px; }

.joyride-content-wrapper {
  width: 100%;
  padding: 1.125rem 1.25rem 1.5rem; }
  .joyride-content-wrapper .button {
    margin-bottom: 0 !important; }
  .joyride-content-wrapper .joyride-prev-tip {
    margin-right: 10px; }

/* Add a little css triangle pip, older browser just miss out on the fanciness of it */
.joyride-tip-guide .joyride-nub {
  display: block;
  position: absolute;
  left: 22px;
  width: 0;
  height: 0;
  border: 10px solid #333333; }
  .joyride-tip-guide .joyride-nub.top {
    border-top-style: solid;
    border-color: #333333;
    border-top-color: transparent !important;
    border-left-color: transparent !important;
    border-right-color: transparent !important;
    top: -20px; }
  .joyride-tip-guide .joyride-nub.bottom {
    border-bottom-style: solid;
    border-color: #333333 !important;
    border-bottom-color: transparent !important;
    border-left-color: transparent !important;
    border-right-color: transparent !important;
    bottom: -20px; }
  .joyride-tip-guide .joyride-nub.right {
    right: -20px; }
  .joyride-tip-guide .joyride-nub.left {
    left: -20px; }

/* Typography */
.joyride-tip-guide h1, .joyride-tip-guide h2, .joyride-tip-guide h3, .joyride-tip-guide h4, .joyride-tip-guide h5, .joyride-tip-guide h6 {
  line-height: 1.25;
  margin: 0;
  font-weight: bold;
  color: #FFFFFF; }

.joyride-tip-guide p {
  margin: 0 0 1.125rem 0;
  font-size: 0.875rem;
  line-height: 1.3; }

.joyride-timer-indicator-wrap {
  width: 50px;
  height: 3px;
  border: solid 1px #555555;
  position: absolute;
  right: 1.0625rem;
  bottom: 1rem; }

.joyride-timer-indicator {
  display: block;
  width: 0;
  height: inherit;
  background: #666666; }

.joyride-close-tip {
  position: absolute;
  right: 12px;
  top: 10px;
  color: #777777 !important;
  text-decoration: none;
  font-size: 24px;
  font-weight: 400;
  line-height: .5 !important; }
  .joyride-close-tip:hover, .joyride-close-tip:focus {
    color: #EEEEEE !important; }

.joyride-modal-bg {
  position: fixed;
  height: 100%;
  width: 100%;
  background: transparent;
  background: rgba(0, 0, 0, 0.5);
  z-index: 100;
  display: none;
  top: 0;
  left: 0;
  cursor: pointer; }

.joyride-expose-wrapper {
  background-color: #FFFFFF;
  position: absolute;
  border-radius: 3px;
  z-index: 102;
  box-shadow: 0 0 15px #FFFFFF; }

.joyride-expose-cover {
  background: transparent;
  border-radius: 3px;
  position: absolute;
  z-index: 9999;
  top: 0;
  left: 0; }

/* Styles for screens that are at least 768px; */
@media only screen and (min-width:40.063em) {
  .joyride-tip-guide {
    width: 300px;
    left: inherit; }
    .joyride-tip-guide .joyride-nub.bottom {
      border-color: #333333 !important;
      border-bottom-color: transparent !important;
      border-left-color: transparent !important;
      border-right-color: transparent !important;
      bottom: -20px; }
    .joyride-tip-guide .joyride-nub.right {
      border-color: #333333 !important;
      border-top-color: transparent !important;
      border-right-color: transparent !important;
      border-bottom-color: transparent !important;
      top: 22px;
      left: auto;
      right: -20px; }
    .joyride-tip-guide .joyride-nub.left {
      border-color: #333333 !important;
      border-top-color: transparent !important;
      border-left-color: transparent !important;
      border-bottom-color: transparent !important;
      top: 22px;
      left: -20px;
      right: auto; } }

.keystroke, kbd {
  background-color: #ededed;
  border-color: #dddddd;
  color: #222222;
  border-style: solid;
  border-width: 1px;
  margin: 0;
  font-family: "Consolas", "Menlo", "Courier", monospace;
  font-size: inherit;
  padding: 0.125rem 0.25rem 0;
  border-radius: 3px; }

.label {
  font-weight: 400;
  font-family: arial, sans-serif;
  text-align: center;
  text-decoration: none;
  line-height: 1;
  white-space: nowrap;
  display: inline-block;
  position: relative;
  margin-bottom: auto;
  padding: 0.25rem 0.5rem 0.25rem;
  font-size: 0.6875rem;
  background-color: #1f5c87;
  color: #FFFFFF; }
  .label.radius {
    border-radius: 3px; }
  .label.round {
    border-radius: 1000px; }
  .label.alert {
    background-color: #f04124;
    color: #FFFFFF; }
  .label.warning {
    background-color: #f08a24;
    color: #FFFFFF; }
  .label.success {
    background-color: #43AC6A;
    color: #FFFFFF; }
  .label.secondary {
    background-color: #E7E7E7;
    color: #333333; }
  .label.info {
    background-color: #a0d3e8;
    color: #333333; }

[data-magellan-expedition], [data-magellan-expedition-clone] {
  background: #FFFFFF;
  z-index: 50;
  min-width: 100%;
  padding: 10px; }
  [data-magellan-expedition] .sub-nav, [data-magellan-expedition-clone] .sub-nav {
    margin-bottom: 0; }
    [data-magellan-expedition] .sub-nav dd, [data-magellan-expedition-clone] .sub-nav dd {
      margin-bottom: 0; }
    [data-magellan-expedition] .sub-nav a, [data-magellan-expedition-clone] .sub-nav a {
      line-height: 1.8em; }

@-webkit-keyframes rotate {
  from {
    -webkit-transform: rotate(0deg); }

  to {
    -webkit-transform: rotate(360deg); } }

@-moz-keyframes rotate {
  from {
    -moz-transform: rotate(0deg); }

  to {
    -moz-transform: rotate(360deg); } }

@-o-keyframes rotate {
  from {
    -o-transform: rotate(0deg); }

  to {
    -o-transform: rotate(360deg); } }

@keyframes rotate {
  from {
    transform: rotate(0deg); }

  to {
    transform: rotate(360deg); } }

/* Orbit Graceful Loading */
.slideshow-wrapper {
  position: relative; }
  .slideshow-wrapper ul {
    list-style-type: none;
    margin: 0; }
    .slideshow-wrapper ul li, .slideshow-wrapper ul li .orbit-caption {
      display: none; }
    .slideshow-wrapper ul li:first-child {
      display: block; }
  .slideshow-wrapper .orbit-container {
    background-color: transparent; }
    .slideshow-wrapper .orbit-container li {
      display: block; }
      .slideshow-wrapper .orbit-container li .orbit-caption {
        display: block; }
    .slideshow-wrapper .orbit-container .orbit-bullets li {
      display: inline-block; }
  .slideshow-wrapper .preloader {
    display: block;
    width: 40px;
    height: 40px;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-top: -20px;
    margin-left: -20px;
    border: solid 3px;
    border-color: #555555 #FFFFFF;
    border-radius: 1000px;
    animation-name: rotate;
    animation-duration: 1.5s;
    animation-iteration-count: infinite;
    animation-timing-function: linear; }

.orbit-container {
  overflow: hidden;
  width: 100%;
  position: relative;
  background: none; }
  .orbit-container .orbit-slides-container {
    list-style: none;
    margin: 0;
    padding: 0;
    position: relative;
    -webkit-transform: translateZ(0); }
    .orbit-container .orbit-slides-container img {
      display: block;
      max-width: 100%; }
    .orbit-container .orbit-slides-container > * {
      position: absolute;
      top: 0;
      width: 100%;
      margin-left: 100%; }
      .orbit-container .orbit-slides-container > *:first-child {
        margin-left: 0; }
      .orbit-container .orbit-slides-container > * .orbit-caption {
        position: absolute;
        bottom: 0;
        background-color: rgba(51, 51, 51, 0.8);
        color: #FFFFFF;
        width: 100%;
        padding: 0.625rem 0.875rem;
        font-size: 0.875rem; }
  .orbit-container .orbit-slide-number {
    position: absolute;
    top: 10px;
    left: 10px;
    font-size: 12px;
    color: #FFFFFF;
    background: transparent;
    z-index: 10; }
    .orbit-container .orbit-slide-number span {
      font-weight: 700;
      padding: 0.3125rem; }
  .orbit-container .orbit-timer {
    position: absolute;
    top: 12px;
    right: 10px;
    height: 6px;
    width: 100px;
    z-index: 10; }
    .orbit-container .orbit-timer .orbit-progress {
      height: 3px;
      background-color: rgba(255, 255, 255, 0.3);
      display: block;
      width: 0;
      position: relative;
      right: 20px;
      top: 5px; }
    .orbit-container .orbit-timer > span {
      display: none;
      position: absolute;
      top: 0;
      right: 0;
      width: 11px;
      height: 14px;
      border: solid 4px #FFFFFF;
      border-top: none;
      border-bottom: none; }
    .orbit-container .orbit-timer.paused > span {
      right: -4px;
      top: 0;
      width: 11px;
      height: 14px;
      border: inset 8px;
      border-left-style: solid;
      border-color: transparent;
      border-left-color: #FFFFFF; }
      .orbit-container .orbit-timer.paused > span.dark {
        border-left-color: #333333; }
  .orbit-container:hover .orbit-timer > span {
    display: block; }
  .orbit-container .orbit-prev, .orbit-container .orbit-next {
    position: absolute;
    top: 45%;
    margin-top: -25px;
    width: 36px;
    height: 60px;
    line-height: 50px;
    color: white;
    background-color: transparent;
    text-indent: -9999px !important;
    z-index: 10; }
    .orbit-container .orbit-prev:hover, .orbit-container .orbit-next:hover {
      background-color: rgba(0, 0, 0, 0.3); }
    .orbit-container .orbit-prev > span, .orbit-container .orbit-next > span {
      position: absolute;
      top: 50%;
      margin-top: -10px;
      display: block;
      width: 0;
      height: 0;
      border: inset 10px; }
  .orbit-container .orbit-prev {
    left: 0; }
    .orbit-container .orbit-prev > span {
      border-right-style: solid;
      border-color: transparent;
      border-right-color: #FFFFFF; }
    .orbit-container .orbit-prev:hover > span {
      border-right-color: #FFFFFF; }
  .orbit-container .orbit-next {
    right: 0; }
    .orbit-container .orbit-next > span {
      border-color: transparent;
      border-left-style: solid;
      border-left-color: #FFFFFF;
      left: 50%;
      margin-left: -4px; }
    .orbit-container .orbit-next:hover > span {
      border-left-color: #FFFFFF; }

.orbit-bullets-container {
  text-align: center; }

.orbit-bullets {
  margin: 0 auto 30px auto;
  overflow: hidden;
  position: relative;
  top: 10px;
  float: none;
  text-align: center;
  display: block; }
  .orbit-bullets li {
    cursor: pointer;
    display: inline-block;
    width: 0.5625rem;
    height: 0.5625rem;
    background: #565656;
    float: none;
    margin-right: 6px;
    border-radius: 1000px; }
    .orbit-bullets li.active {
      background: #999999; }
    .orbit-bullets li:last-child {
      margin-right: 0; }

.touch .orbit-container .orbit-prev, .touch .orbit-container .orbit-next {
  display: none; }
.touch .orbit-bullets {
  display: none; }

@media only screen and (min-width:40.063em) {
  .touch .orbit-container .orbit-prev, .touch .orbit-container .orbit-next {
    display: inherit; }
  .touch .orbit-bullets {
    display: block; } }

@media only screen and (max-width: 40em) {
  .orbit-stack-on-small .orbit-slides-container {
    height: auto !important; }
  .orbit-stack-on-small .orbit-slides-container > * {
    position: relative;
    margin: 0 !important;
    opacity: 1 !important; }
  .orbit-stack-on-small .orbit-slide-number {
    display: none; }
  .orbit-timer {
    display: none; }
  .orbit-next, .orbit-prev {
    display: none; }
  .orbit-bullets {
    display: none; } }

ul.pagination {
  display: block;
  min-height: 1.5rem;
  margin-left: -0.3125rem; }
  ul.pagination li {
    height: 1.5rem;
    color: #222222;
    font-size: 0.875rem;
    margin-left: 0.3125rem; }
    ul.pagination li a, ul.pagination li button {
      display: block;
      padding: 0.0625rem 0.625rem 0.0625rem;
      color: #999999;
      background: none;
      border-radius: 3px;
      font-weight: normal;
      font-size: 1em;
      line-height: inherit;
      transition: background-color 300ms ease-out; }
    ul.pagination li:hover a, ul.pagination li a:focus, ul.pagination li:hover button, ul.pagination li button:focus {
      background: #e6e6e6; }
    ul.pagination li.unavailable a, ul.pagination li.unavailable button {
      cursor: default;
      color: #999999; }
    ul.pagination li.unavailable:hover a, ul.pagination li.unavailable a:focus, ul.pagination li.unavailable:hover button, ul.pagination li.unavailable button:focus {
      background: transparent; }
    ul.pagination li.current a, ul.pagination li.current button {
      background: #1f5c87;
      color: #FFFFFF;
      font-weight: bold;
      cursor: default; }
      ul.pagination li.current a:hover, ul.pagination li.current a:focus, ul.pagination li.current button:hover, ul.pagination li.current button:focus {
        background: #1f5c87; }
  ul.pagination li {
    float: left;
    display: block; }

/* Pagination centred wrapper */
.pagination-centered {
  text-align: center; }
  .pagination-centered ul.pagination li {
    float: none;
    display: inline-block; }

/* Panels */
.panel {
  border-style: solid;
  border-width: 1px;
  border-color: #d8d8d8;
  margin-bottom: 1.25rem;
  padding: 1.25rem;
  background: #f2f2f2;
  color: #333333; }
  .panel > :first-child {
    margin-top: 0; }
  .panel > :last-child {
    margin-bottom: 0; }
  .panel h1, .panel h2, .panel h3, .panel h4, .panel h5, .panel h6, .panel p, .panel li, .panel dl {
    color: #333333; }
  .panel h1, .panel h2, .panel h3, .panel h4, .panel h5, .panel h6 {
    line-height: 1;
    margin-bottom: 0.625rem; }
    .panel h1.subheader, .panel h2.subheader, .panel h3.subheader, .panel h4.subheader, .panel h5.subheader, .panel h6.subheader {
      line-height: 1.4; }
  .panel.callout {
    border-style: solid;
    border-width: 1px;
    border-color: #ffe5b9;
    margin-bottom: 1.25rem;
    padding: 1.25rem;
    background: #fff9f0;
    color: #333333; }
    .panel.callout > :first-child {
      margin-top: 0; }
    .panel.callout > :last-child {
      margin-bottom: 0; }
    .panel.callout h1, .panel.callout h2, .panel.callout h3, .panel.callout h4, .panel.callout h5, .panel.callout h6, .panel.callout p, .panel.callout li, .panel.callout dl {
      color: #333333; }
    .panel.callout h1, .panel.callout h2, .panel.callout h3, .panel.callout h4, .panel.callout h5, .panel.callout h6 {
      line-height: 1;
      margin-bottom: 0.625rem; }
      .panel.callout h1.subheader, .panel.callout h2.subheader, .panel.callout h3.subheader, .panel.callout h4.subheader, .panel.callout h5.subheader, .panel.callout h6.subheader {
        line-height: 1.4; }
    .panel.callout a:not(.button) {
      color: #1f5c87; }
      .panel.callout a:not(.button):hover, .panel.callout a:not(.button):focus {
        color: #db8a00; }
  .panel.radius {
    border-radius: 3px; }

/* Pricing Tables */
.pricing-table {
  border: solid 1px #DDDDDD;
  margin-left: 0;
  margin-bottom: 1.25rem; }
  .pricing-table * {
    list-style: none;
    line-height: 1; }
  .pricing-table .title {
    background-color: #333333;
    padding: 0.9375rem 1.25rem;
    text-align: center;
    color: #EEEEEE;
    font-weight: 400;
    font-size: 1rem;
    font-family: arial, sans-serif; }
  .pricing-table .price {
    background-color: #F6F6F6;
    padding: 0.9375rem 1.25rem;
    text-align: center;
    color: #333333;
    font-weight: 400;
    font-size: 2rem;
    font-family: arial, sans-serif; }
  .pricing-table .description {
    background-color: #FFFFFF;
    padding: 0.9375rem;
    text-align: center;
    color: #777777;
    font-size: 0.75rem;
    font-weight: 400;
    line-height: 1.4;
    border-bottom: dotted 1px #DDDDDD; }
  .pricing-table .bullet-item {
    background-color: #FFFFFF;
    padding: 0.9375rem;
    text-align: center;
    color: #333333;
    font-size: 0.875rem;
    font-weight: 400;
    border-bottom: dotted 1px #DDDDDD; }
  .pricing-table .cta-button {
    background-color: #FFFFFF;
    text-align: center;
    padding: 1.25rem 1.25rem 0; }

/* Progress Bar */
.progress {
  background-color: #F6F6F6;
  height: 1.5625rem;
  border: 1px solid white;
  padding: 0.125rem;
  margin-bottom: 0.625rem; }
  .progress .meter {
    background: #1f5c87;
    height: 100%;
    display: block; }
  .progress.secondary .meter {
    background: #E7E7E7;
    height: 100%;
    display: block; }
  .progress.success .meter {
    background: #43AC6A;
    height: 100%;
    display: block; }
  .progress.alert .meter {
    background: #f04124;
    height: 100%;
    display: block; }
  .progress.radius {
    border-radius: 3px; }
    .progress.radius .meter {
      border-radius: 2px; }
  .progress.round {
    border-radius: 1000px; }
    .progress.round .meter {
      border-radius: 999px; }

.range-slider {
  position: relative;
  border: 1px solid #DDDDDD;
  margin: 1.25rem 0;
  -ms-touch-action: none;
  touch-action: none;
  display: block;
  width: 100%;
  height: 1rem;
  background: #FAFAFA; }
  .range-slider.vertical-range {
    position: relative;
    border: 1px solid #DDDDDD;
    margin: 1.25rem 0;
    -ms-touch-action: none;
    touch-action: none;
    display: inline-block;
    width: 1rem;
    height: 12.5rem; }
    .range-slider.vertical-range .range-slider-handle {
      margin-top: 0;
      margin-left: -0.5rem;
      position: absolute;
      bottom: -10.5rem; }
    .range-slider.vertical-range .range-slider-active-segment {
      width: 0.875rem;
      height: auto;
      bottom: 0; }
  .range-slider.radius {
    background: #FAFAFA;
    border-radius: 3px; }
    .range-slider.radius .range-slider-handle {
      background: #1f5c87;
      border-radius: 3px; }
      .range-slider.radius .range-slider-handle:hover {
        background: #e08e00; }
  .range-slider.round {
    background: #FAFAFA;
    border-radius: 1000px; }
    .range-slider.round .range-slider-handle {
      background: #1f5c87;
      border-radius: 1000px; }
      .range-slider.round .range-slider-handle:hover {
        background: #e08e00; }
  .range-slider.disabled, .range-slider[disabled] {
    background: #FAFAFA;
    cursor: false;
    opacity: 0.7; }
    .range-slider.disabled .range-slider-handle, .range-slider[disabled] .range-slider-handle {
      background: #1f5c87;
      cursor: default;
      opacity: 0.7; }
      .range-slider.disabled .range-slider-handle:hover, .range-slider[disabled] .range-slider-handle:hover {
        background: #e08e00; }

.range-slider-active-segment {
  display: inline-block;
  position: absolute;
  height: 0.875rem;
  background: #e5e5e5; }

.range-slider-handle {
  display: inline-block;
  position: absolute;
  z-index: 1;
  top: -0.3125rem;
  width: 2rem;
  height: 1.375rem;
  border: 1px solid none;
  cursor: pointer;
  -ms-touch-action: manipulation;
  touch-action: manipulation;
  background: #1f5c87; }
  .range-slider-handle:hover {
    background: #e08e00; }

.reveal-modal-bg {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: #000000;
  background: rgba(0, 0, 0, 0.45);
  z-index: 1004;
  display: none;
  left: 0; }

.reveal-modal {
  visibility: hidden;
  display: none;
  position: absolute;
  z-index: 1005;
  width: 100%;
  top: 0;
  border-radius: 3px;
  left: 0;
  background-color: #FFFFFF;
  padding: 1.875rem;
  border: solid 1px #666666;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.4); }
  @media only screen and (max-width: 40em) {
    .reveal-modal {
      min-height: 100vh; } }
  .reveal-modal .column, .reveal-modal .columns {
    min-width: 0; }
  .reveal-modal > :first-child {
    margin-top: 0; }
  .reveal-modal > :last-child {
    margin-bottom: 0; }
  @media only screen and (min-width:40.063em) {
    .reveal-modal {
      width: 80%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal {
      top: 6.25rem; } }
  .reveal-modal.radius {
    border-radius: 3px; }
  .reveal-modal.round {
    border-radius: 1000px; }
  .reveal-modal.collapse {
    padding: 0; }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.tiny {
      width: 30%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.small {
      width: 40%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.medium {
      width: 60%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.large {
      width: 70%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  @media only screen and (min-width:40.063em) {
    .reveal-modal.xlarge {
      width: 95%;
      max-width: 68.75rem;
      left: 0;
      right: 0;
      margin: 0 auto; } }
  .reveal-modal.full {
    top: 0;
    left: 0;
    height: 100%;
    height: 100vh;
    min-height: 100vh;
    max-width: none !important;
    margin-left: 0 !important; }
    @media only screen and (min-width:40.063em) {
      .reveal-modal.full {
        width: 100%;
        max-width: 68.75rem;
        left: 0;
        right: 0;
        margin: 0 auto; } }
  .reveal-modal.toback {
    z-index: 1003; }
  .reveal-modal .close-reveal-modal {
    font-size: 2.5rem;
    line-height: 1;
    position: absolute;
    top: 0.625rem;
    right: 1.375rem;
    color: #AAAAAA;
    font-weight: bold;
    cursor: pointer; }

.side-nav {
  display: block;
  margin: 0;
  padding: 0.875rem 0;
  list-style-type: none;
  list-style-position: outside;
  font-family: arial, sans-serif; }
  .side-nav li {
    margin: 0 0 0.4375rem 0;
    font-size: 0.875rem;
    font-weight: 400; }
    .side-nav li a:not(.button) {
      display: block;
      color: #1f5c87;
      margin: 0;
      padding: 0.4375rem 0.875rem; }
      .side-nav li a:not(.button):hover, .side-nav li a:not(.button):focus {
        background: rgba(0, 0, 0, 0.025);
        color: #ffbd4d; }
    .side-nav li.active > a:first-child:not(.button) {
      color: #ffbd4d;
      font-weight: 400;
      font-family: arial, sans-serif; }
    .side-nav li.divider {
      border-top: 1px solid;
      height: 0;
      padding: 0;
      list-style: none;
      border-top-color: white; }
    .side-nav li.heading {
      color: #1f5c87;
      font-size: 0.875rem;
      font-weight: bold;
      text-transform: uppercase; }

.split.button {
  position: relative;
  padding-right: 5.0625rem; }
  .split.button span {
    display: block;
    height: 100%;
    position: absolute;
    right: 0;
    top: 0;
    border-left: solid 1px; }
    .split.button span:after {
      position: absolute;
      content: "";
      width: 0;
      height: 0;
      display: block;
      border-style: inset;
      top: 50%;
      left: 50%; }
    .split.button span:active {
      background-color: rgba(0, 0, 0, 0.1); }
  .split.button span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button span {
    width: 3.09375rem; }
    .split.button span:after {
      border-top-style: solid;
      border-width: 0.375rem;
      top: 48%;
      margin-left: -0.375rem; }
  .split.button span:after {
    border-color: #FFFFFF transparent transparent transparent; }
  .split.button.secondary span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button.secondary span:after {
    border-color: #FFFFFF transparent transparent transparent; }
  .split.button.alert span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button.success span {
    border-left-color: rgba(255, 255, 255, 0.5); }
  .split.button.tiny {
    padding-right: 3.75rem; }
    .split.button.tiny span {
      width: 2.25rem; }
      .split.button.tiny span:after {
        border-top-style: solid;
        border-width: 0.375rem;
        top: 48%;
        margin-left: -0.375rem; }
  .split.button.small {
    padding-right: 4.375rem; }
    .split.button.small span {
      width: 2.625rem; }
      .split.button.small span:after {
        border-top-style: solid;
        border-width: 0.4375rem;
        top: 48%;
        margin-left: -0.375rem; }
  .split.button.large {
    padding-right: 5.5rem; }
    .split.button.large span {
      width: 3.4375rem; }
      .split.button.large span:after {
        border-top-style: solid;
        border-width: 0.3125rem;
        top: 48%;
        margin-left: -0.375rem; }
  .split.button.expand {
    padding-left: 2rem; }
  .split.button.secondary span:after {
    border-color: #333333 transparent transparent transparent; }
  .split.button.radius span {
    -webkit-border-bottom-right-radius: 3px;
    -webkit-border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
    border-top-right-radius: 3px; }
  .split.button.round span {
    -webkit-border-bottom-right-radius: 1000px;
    -webkit-border-top-right-radius: 1000px;
    border-bottom-right-radius: 1000px;
    border-top-right-radius: 1000px; }
  .split.button.no-pip span:before {
    border-style: none; }
  .split.button.no-pip span:after {
    border-style: none; }
  .split.button.no-pip span > i {
    top: 50%;
    display: block;
    position: absolute;
    left: 50%;
    margin-left: -0.28889em;
    margin-top: -0.48889em; }

.sub-nav {
  display: block;
  width: auto;
  overflow: hidden;
  margin-bottom: -0.25rem 0 1.125rem;
  padding-top: 0.25rem; }
  .sub-nav dt {
    text-transform: uppercase; }
  .sub-nav dt, .sub-nav dd, .sub-nav li {
    float: left;
    margin-left: 1rem;
    margin-bottom: 0;
    font-family: arial, sans-serif;
    font-weight: 400;
    font-size: 0.875rem;
    color: #999999; }
    .sub-nav dt a, .sub-nav dd a, .sub-nav li a {
      text-decoration: none;
      color: #999999;
      padding: 0.1875rem 1rem; }
      .sub-nav dt a:hover, .sub-nav dd a:hover, .sub-nav li a:hover {
        color: #737373; }
    .sub-nav dt.active a, .sub-nav dd.active a, .sub-nav li.active a {
      border-radius: 3px;
      font-weight: 400;
      background: #1f5c87;
      padding: 0.1875rem 1rem;
      cursor: default;
      color: #FFFFFF; }
      .sub-nav dt.active a:hover, .sub-nav dd.active a:hover, .sub-nav li.active a:hover {
        background: #db8a00; }

.switch {
  padding: 0;
  border: none;
  position: relative;
  outline: 0;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none; }
  .switch label {
    display: block;
    margin-bottom: 1rem;
    position: relative;
    color: transparent;
    background: #DDDDDD;
    text-indent: 100%;
    width: 4rem;
    height: 2rem;
    cursor: pointer;
    transition: left 0.15s ease-out; }
  .switch input {
    opacity: 0;
    position: absolute;
    top: 9px;
    left: 10px;
    padding: 0; }
    .switch input + label {
      margin-left: 0;
      margin-right: 0; }
  .switch label:after {
    content: "";
    display: block;
    background: #FFFFFF;
    position: absolute;
    top: .25rem;
    left: .25rem;
    width: 1.5rem;
    height: 1.5rem;
    -webkit-transition: left 0.15s ease-out;
    -moz-transition: left 0.15s ease-out;
    -o-transition: translate3d(0, 0, 0);
    transition: left 0.15s ease-out;
    -webkit-transform: translate3d(0, 0, 0);
    -moz-transform: translate3d(0, 0, 0);
    -o-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0); }
  .switch input:checked + label {
    background: #1f5c87; }
  .switch input:checked + label:after {
    left: 2.25rem; }
  .switch label {
    width: 4rem;
    height: 2rem; }
  .switch label:after {
    width: 1.5rem;
    height: 1.5rem; }
  .switch input:checked + label:after {
    left: 2.25rem; }
  .switch label {
    color: transparent;
    background: #DDDDDD; }
  .switch label:after {
    background: #FFFFFF; }
  .switch input:checked + label {
    background: #1f5c87; }
  .switch.large label {
    width: 5rem;
    height: 2.5rem; }
  .switch.large label:after {
    width: 2rem;
    height: 2rem; }
  .switch.large input:checked + label:after {
    left: 2.75rem; }
  .switch.small label {
    width: 3.5rem;
    height: 1.75rem; }
  .switch.small label:after {
    width: 1.25rem;
    height: 1.25rem; }
  .switch.small input:checked + label:after {
    left: 2rem; }
  .switch.tiny label {
    width: 3rem;
    height: 1.5rem; }
  .switch.tiny label:after {
    width: 1rem;
    height: 1rem; }
  .switch.tiny input:checked + label:after {
    left: 1.75rem; }
  .switch.radius label {
    border-radius: 4px; }
  .switch.radius label:after {
    border-radius: 3px; }
  .switch.round {
    border-radius: 1000px; }
    .switch.round label {
      border-radius: 2rem; }
    .switch.round label:after {
      border-radius: 2rem; }

table {
  background: #FFFFFF;
  margin-bottom: 1.25rem;
  border: solid 1px #DDDDDD;
  table-layout: auto; }
  table caption {
    background: transparent;
    color: #222222;
    font-size: 1rem;
    font-weight: bold; }
  table thead {
    background: #F5F5F5; }
    table thead tr th, table thead tr td {
      padding: 0.5rem 0.625rem 0.625rem;
      font-size: 0.875rem;
      font-weight: bold;
      color: #222222; }
  table tfoot {
    background: #F5F5F5; }
    table tfoot tr th, table tfoot tr td {
      padding: 0.5rem 0.625rem 0.625rem;
      font-size: 0.875rem;
      font-weight: bold;
      color: #222222; }
  table tr th, table tr td {
    padding: 0.5625rem 0.625rem;
    font-size: 0.875rem;
    color: #222222;
    text-align: left; }
  table tr.even, table tr.alt, table tr:nth-of-type(even) {
    background: #F9F9F9; }
  table thead tr th, table tfoot tr th, table tfoot tr td, table tbody tr th, table tbody tr td, table tr td {
    display: table-cell;
    line-height: 1.125rem; }

.tabs {
  margin-bottom: 0 !important;
  margin-left: 0; }
  .tabs:before, .tabs:after {
    content: " ";
    display: table; }
  .tabs:after {
    clear: both; }
  .tabs dd, .tabs .tab-title {
    position: relative;
    margin-bottom: 0 !important;
    list-style: none;
    float: left; }
    .tabs dd > a, .tabs .tab-title > a {
      display: block;
      background-color: #EFEFEF;
      color: #222222;
      padding: 1rem 2rem;
      font-family: arial, sans-serif;
      font-size: 1rem; }
      .tabs dd > a:hover, .tabs .tab-title > a:hover {
        background-color: #e1e1e1; }
      .tabs dd > a:focus, .tabs .tab-title > a:focus {
        outline: none; }
    .tabs dd.active a, .tabs .tab-title.active a {
      background-color: #FFFFFF;
      color: #222222; }
  .tabs.radius dd:first-child a, .tabs.radius .tab:first-child a {
    -webkit-border-bottom-left-radius: 3px;
    -webkit-border-top-left-radius: 3px;
    border-bottom-left-radius: 3px;
    border-top-left-radius: 3px; }
  .tabs.radius dd:last-child a, .tabs.radius .tab:last-child a {
    -webkit-border-bottom-right-radius: 3px;
    -webkit-border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
    border-top-right-radius: 3px; }
  .tabs.vertical dd, .tabs.vertical .tab-title {
    position: inherit;
    float: none;
    display: block;
    top: auto; }

.tabs-content {
  margin-bottom: 1.5rem;
  width: 100%; }
  .tabs-content:before, .tabs-content:after {
    content: " ";
    display: table; }
  .tabs-content:after {
    clear: both; }
  .tabs-content > .content {
    display: none;
    float: left;
    padding: 0.9375rem 0;
    width: 100%; }
    .tabs-content > .content.active {
      display: block;
      float: none; }
    .tabs-content > .content.contained {
      padding: 0.9375rem; }
  .tabs-content.vertical {
    display: block; }
    .tabs-content.vertical > .content {
      padding: 0 0.9375rem; }

@media only screen and (min-width:40.063em) {
  .tabs.vertical {
    width: 20%;
    max-width: 20%;
    float: left;
    margin: 0 0 1.25rem; }
  .tabs-content.vertical {
    width: 80%;
    max-width: 80%;
    float: left;
    margin-left: -1px;
    padding-left: 1rem; } }

.no-js .tabs-content > .content {
  display: block;
  float: none; }

/* Image Thumbnails */
.th {
  line-height: 0;
  display: inline-block;
  border: solid 4px #FFFFFF;
  max-width: 100%;
  box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.2);
  transition: all 200ms ease-out; }
  .th:hover, .th:focus {
    box-shadow: 0 0 6px 1px rgba(255, 161, 0, 0.5); }
  .th.radius {
    border-radius: 3px; }

/* Tooltips */
.has-tip {
  border-bottom: dotted 1px #565656;
  cursor: help;
  font-weight: bold;
  color: #333333; }
  .has-tip:hover, .has-tip:focus {
    border-bottom: dotted 1px #734800;
    color: #1f5c87; }
  .has-tip.tip-left, .has-tip.tip-right {
    float: none !important; }

.tooltip {
  display: none;
  position: absolute;
  z-index: 1006;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.3;
  padding: 0.75rem;
  max-width: 300px;
  left: 50%;
  width: 100%;
  color: #FFFFFF;
  background: #333333; }
  .tooltip > .nub {
    display: block;
    left: 5px;
    position: absolute;
    width: 0;
    height: 0;
    border: solid 5px;
    border-color: transparent transparent #333333 transparent;
    top: -10px;
    pointer-events: none; }
    .tooltip > .nub.rtl {
      left: auto;
      right: 5px; }
  .tooltip.radius {
    border-radius: 3px; }
  .tooltip.round {
    border-radius: 1000px; }
    .tooltip.round > .nub {
      left: 2rem; }
  .tooltip.opened {
    color: #1f5c87 !important;
    border-bottom: dotted 1px #734800 !important; }

.tap-to-close {
  display: block;
  font-size: 0.625rem;
  color: #777777;
  font-weight: 400; }

@media only screen and (min-width:40.063em) {
  .tooltip > .nub {
    border-color: transparent transparent #333333 transparent;
    top: -10px; }
  .tooltip.tip-top > .nub {
    border-color: #333333 transparent transparent transparent;
    top: auto;
    bottom: -10px; }
  .tooltip.tip-left, .tooltip.tip-right {
    float: none !important; }
  .tooltip.tip-left > .nub {
    border-color: transparent transparent transparent #333333;
    right: -10px;
    left: auto;
    top: 50%;
    margin-top: -5px; }
  .tooltip.tip-right > .nub {
    border-color: transparent #333333 transparent transparent;
    right: auto;
    left: -10px;
    top: 50%;
    margin-top: -5px; } }

meta.foundation-mq-topbar {
  font-family: "/only screen and (min-width:40.063em)/";
  width: 40.063em; }

/* Wrapped around .top-bar to contain to grid width */
.contain-to-grid {
  width: 100%;
  background: #333333; }
  .contain-to-grid .top-bar {
    margin-bottom: 0; }

.fixed {
  width: 100%;
  left: 0;
  position: fixed;
  top: 0;
  z-index: 99; }
  .fixed.expanded:not(.top-bar) {
    overflow-y: auto;
    height: auto;
    width: 100%;
    max-height: 100%; }
    .fixed.expanded:not(.top-bar) .title-area {
      position: fixed;
      width: 100%;
      z-index: 99; }
    .fixed.expanded:not(.top-bar) .top-bar-section {
      z-index: 98;
      margin-top: 2.8125rem; }

.top-bar {
  overflow: hidden;
  height: 2.8125rem;
  line-height: 2.8125rem;
  position: relative;
  background: #333333;
  margin-bottom: 0; }
  .top-bar ul {
    margin-bottom: 0;
    list-style: none; }
  .top-bar .row {
    max-width: none; }
  .top-bar form, .top-bar input {
    margin-bottom: 0; }
  .top-bar input {
    height: 1.75rem;
    padding-top: .35rem;
    padding-bottom: .35rem;
    font-size: 0.75rem; }
  .top-bar .button, .top-bar button {
    padding-top: .4125rem;
    padding-bottom: .4125rem;
    margin-bottom: 0;
    font-size: 0.75rem; }
    @media only screen and (max-width: 40em) {
      .top-bar .button, .top-bar button {
        position: relative;
        top: -1px; } }
  .top-bar .title-area {
    position: relative;
    margin: 0; }
  .top-bar .name {
    height: 2.8125rem;
    margin: 0;
    font-size: 16px; }
    .top-bar .name h1, .top-bar .name h2, .top-bar .name h3, .top-bar .name h4, .top-bar .name p, .top-bar .name span {
      line-height: 2.8125rem;
      font-size: 1.0625rem;
      margin: 0; }
      .top-bar .name h1 a, .top-bar .name h2 a, .top-bar .name h3 a, .top-bar .name h4 a, .top-bar .name p a, .top-bar .name span a {
        font-weight: 400;
        color: #FFFFFF;
        width: 75%;
        display: block;
        padding: 0 0.9375rem; }
  .top-bar .toggle-topbar {
    position: absolute;
    right: 0;
    top: 0; }
    .top-bar .toggle-topbar a {
      color: #FFFFFF;
      text-transform: uppercase;
      font-size: 0.8125rem;
      font-weight: bold;
      position: relative;
      display: block;
      padding: 0 0.9375rem;
      height: 2.8125rem;
      line-height: 2.8125rem; }
    .top-bar .toggle-topbar.menu-icon {
      top: 50%;
      margin-top: -16px; }
      .top-bar .toggle-topbar.menu-icon a {
        height: 34px;
        line-height: 33px;
        padding: 0 2.5rem 0 0.9375rem;
        color: #FFFFFF;
        position: relative; }
        .top-bar .toggle-topbar.menu-icon a span::after {
          content: "";
          position: absolute;
          display: block;
          height: 0;
          top: 50%;
          margin-top: -8px;
          right: 0.9375rem;
          box-shadow: 0 0 0 1px #FFFFFF, 0 7px 0 1px #FFFFFF, 0 14px 0 1px #FFFFFF;
          width: 16px; }
        .top-bar .toggle-topbar.menu-icon a span:hover:after {
          box-shadow: 0 0 0 1px "", 0 7px 0 1px "", 0 14px 0 1px ""; }
  .top-bar.expanded {
    height: auto;
    background: transparent; }
    .top-bar.expanded .title-area {
      background: #333333; }
    .top-bar.expanded .toggle-topbar a {
      color: #888888; }
      .top-bar.expanded .toggle-topbar a span::after {
        box-shadow: 0 0 0 1px #888888, 0 7px 0 1px #888888, 0 14px 0 1px #888888; }

.top-bar-section {
  left: 0;
  position: relative;
  width: auto;
  transition: left 300ms ease-out; }
  .top-bar-section ul {
    padding: 0;
    width: 100%;
    height: auto;
    display: block;
    font-size: 16px;
    margin: 0; }
  .top-bar-section .divider, .top-bar-section [role="separator"] {
    border-top: solid 1px #1a1a1a;
    clear: both;
    height: 1px;
    width: 100%; }
  .top-bar-section ul li {
    background: #333333; }
    .top-bar-section ul li > a {
      display: block;
      width: 100%;
      color: #FFFFFF;
      padding: 12px 0 12px 0;
      padding-left: 0.9375rem;
      font-family: arial, sans-serif;
      font-size: 0.8125rem;
      font-weight: 400;
      text-transform: none; }
      .top-bar-section ul li > a.button {
        font-size: 0.8125rem;
        padding-right: 0.9375rem;
        padding-left: 0.9375rem;
        background-color: #1f5c87;
        border-color: #cc8100;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button:hover, .top-bar-section ul li > a.button:focus {
          background-color: #cc8100; }
        .top-bar-section ul li > a.button:hover, .top-bar-section ul li > a.button:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > a.button.secondary {
        background-color: #E7E7E7;
        border-color: #b9b9b9;
        color: #333333; }
        .top-bar-section ul li > a.button.secondary:hover, .top-bar-section ul li > a.button.secondary:focus {
          background-color: #b9b9b9; }
        .top-bar-section ul li > a.button.secondary:hover, .top-bar-section ul li > a.button.secondary:focus {
          color: #333333; }
      .top-bar-section ul li > a.button.success {
        background-color: #43AC6A;
        border-color: #368a55;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button.success:hover, .top-bar-section ul li > a.button.success:focus {
          background-color: #368a55; }
        .top-bar-section ul li > a.button.success:hover, .top-bar-section ul li > a.button.success:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > a.button.alert {
        background-color: #f04124;
        border-color: #cf2a0e;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button.alert:hover, .top-bar-section ul li > a.button.alert:focus {
          background-color: #cf2a0e; }
        .top-bar-section ul li > a.button.alert:hover, .top-bar-section ul li > a.button.alert:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > a.button.warning {
        background-color: #f08a24;
        border-color: #cf6e0e;
        color: #FFFFFF; }
        .top-bar-section ul li > a.button.warning:hover, .top-bar-section ul li > a.button.warning:focus {
          background-color: #cf6e0e; }
        .top-bar-section ul li > a.button.warning:hover, .top-bar-section ul li > a.button.warning:focus {
          color: #FFFFFF; }
    .top-bar-section ul li > button {
      font-size: 0.8125rem;
      padding-right: 0.9375rem;
      padding-left: 0.9375rem;
      background-color: #1f5c87;
      border-color: #cc8100;
      color: #FFFFFF; }
      .top-bar-section ul li > button:hover, .top-bar-section ul li > button:focus {
        background-color: #cc8100; }
      .top-bar-section ul li > button:hover, .top-bar-section ul li > button:focus {
        color: #FFFFFF; }
      .top-bar-section ul li > button.secondary {
        background-color: #E7E7E7;
        border-color: #b9b9b9;
        color: #333333; }
        .top-bar-section ul li > button.secondary:hover, .top-bar-section ul li > button.secondary:focus {
          background-color: #b9b9b9; }
        .top-bar-section ul li > button.secondary:hover, .top-bar-section ul li > button.secondary:focus {
          color: #333333; }
      .top-bar-section ul li > button.success {
        background-color: #43AC6A;
        border-color: #368a55;
        color: #FFFFFF; }
        .top-bar-section ul li > button.success:hover, .top-bar-section ul li > button.success:focus {
          background-color: #368a55; }
        .top-bar-section ul li > button.success:hover, .top-bar-section ul li > button.success:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > button.alert {
        background-color: #f04124;
        border-color: #cf2a0e;
        color: #FFFFFF; }
        .top-bar-section ul li > button.alert:hover, .top-bar-section ul li > button.alert:focus {
          background-color: #cf2a0e; }
        .top-bar-section ul li > button.alert:hover, .top-bar-section ul li > button.alert:focus {
          color: #FFFFFF; }
      .top-bar-section ul li > button.warning {
        background-color: #f08a24;
        border-color: #cf6e0e;
        color: #FFFFFF; }
        .top-bar-section ul li > button.warning:hover, .top-bar-section ul li > button.warning:focus {
          background-color: #cf6e0e; }
        .top-bar-section ul li > button.warning:hover, .top-bar-section ul li > button.warning:focus {
          color: #FFFFFF; }
    .top-bar-section ul li:hover:not(.has-form) > a {
      background-color: #555555;
      background: #333333;
      color: #FFFFFF; }
    .top-bar-section ul li.active > a {
      background: #1f5c87;
      color: #FFFFFF; }
      .top-bar-section ul li.active > a:hover {
        background: #db8a00;
        color: #FFFFFF; }
  .top-bar-section .has-form {
    padding: 0.9375rem; }
  .top-bar-section .has-dropdown {
    position: relative; }
    .top-bar-section .has-dropdown > a:after {
      content: "";
      display: block;
      width: 0;
      height: 0;
      border: inset 5px;
      border-color: transparent transparent transparent rgba(255, 255, 255, 0.4);
      border-left-style: solid;
      margin-right: 0.9375rem;
      margin-top: -4.5px;
      position: absolute;
      top: 50%;
      right: 0; }
    .top-bar-section .has-dropdown.moved {
      position: static; }
      .top-bar-section .has-dropdown.moved > .dropdown {
        display: block;
        position: static !important;
        height: auto;
        width: auto;
        overflow: visible;
        clip: auto;
        position: absolute !important;
        width: 100%; }
      .top-bar-section .has-dropdown.moved > a:after {
        display: none; }
  .top-bar-section .dropdown {
    padding: 0;
    position: absolute;
    left: 100%;
    top: 0;
    z-index: 99;
    display: block;
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
    .top-bar-section .dropdown li {
      width: 100%;
      height: auto; }
      .top-bar-section .dropdown li a {
        font-weight: 400;
        padding: 8px 0.9375rem; }
        .top-bar-section .dropdown li a.parent-link {
          font-weight: 400; }
      .top-bar-section .dropdown li.title h5, .top-bar-section .dropdown li.parent-link {
        margin-bottom: 0;
        margin-top: 0;
        font-size: 1.125rem; }
        .top-bar-section .dropdown li.title h5 a, .top-bar-section .dropdown li.parent-link a {
          color: #FFFFFF;
          display: block; }
          .top-bar-section .dropdown li.title h5 a:hover, .top-bar-section .dropdown li.parent-link a:hover {
            background: none; }
      .top-bar-section .dropdown li.has-form {
        padding: 8px 0.9375rem; }
      .top-bar-section .dropdown li .button, .top-bar-section .dropdown li button {
        top: auto; }
    .top-bar-section .dropdown label {
      padding: 8px 0.9375rem 2px;
      margin-bottom: 0;
      text-transform: uppercase;
      color: #777777;
      font-weight: bold;
      font-size: 0.625rem; }

.js-generated {
  display: block; }

@media only screen and (min-width:40.063em) {
  .top-bar {
    background: #333333;
    overflow: visible; }
    .top-bar:before, .top-bar:after {
      content: " ";
      display: table; }
    .top-bar:after {
      clear: both; }
    .top-bar .toggle-topbar {
      display: none; }
    .top-bar .title-area {
      float: left; }
    .top-bar .name h1 a, .top-bar .name h2 a, .top-bar .name h3 a, .top-bar .name h4 a, .top-bar .name h5 a, .top-bar .name h6 a {
      width: auto; }
    .top-bar input, .top-bar .button, .top-bar button {
      font-size: 0.875rem;
      position: relative;
      height: 1.75rem;
      top: 0.53125rem; }
    .top-bar.expanded {
      background: #333333; }
  .contain-to-grid .top-bar {
    max-width: 68.75rem;
    margin: 0 auto;
    margin-bottom: 0; }
  .top-bar-section {
    transition: none 0 0;
    left: 0 !important; }
    .top-bar-section ul {
      width: auto;
      height: auto !important;
      display: inline; }
      .top-bar-section ul li {
        float: left; }
        .top-bar-section ul li .js-generated {
          display: none; }
    .top-bar-section li.hover > a:not(.button) {
      background-color: #555555;
      background: #333333;
      color: #FFFFFF; }
    .top-bar-section li:not(.has-form) a:not(.button) {
      padding: 0 0.9375rem;
      line-height: 2.8125rem;
      background: #333333; }
      .top-bar-section li:not(.has-form) a:not(.button):hover {
        background-color: #555555;
        background: #333333; }
    .top-bar-section li.active:not(.has-form) a:not(.button) {
      padding: 0 0.9375rem;
      line-height: 2.8125rem;
      color: #FFFFFF;
      background: #1f5c87; }
      .top-bar-section li.active:not(.has-form) a:not(.button):hover {
        background: #db8a00;
        color: #FFFFFF; }
    .top-bar-section .has-dropdown > a {
      padding-right: 2.1875rem !important; }
      .top-bar-section .has-dropdown > a:after {
        content: "";
        display: block;
        width: 0;
        height: 0;
        border: inset 5px;
        border-color: rgba(255, 255, 255, 0.4) transparent transparent transparent;
        border-top-style: solid;
        margin-top: -2.5px;
        top: 1.40625rem; }
    .top-bar-section .has-dropdown.moved {
      position: relative; }
      .top-bar-section .has-dropdown.moved > .dropdown {
        display: block;
        position: absolute !important;
        height: 1px;
        width: 1px;
        overflow: hidden;
        clip: rect(1px, 1px, 1px, 1px); }
    .top-bar-section .has-dropdown.hover > .dropdown, .top-bar-section .has-dropdown.not-click:hover > .dropdown {
      display: block;
      position: static !important;
      height: auto;
      width: auto;
      overflow: visible;
      clip: auto;
      position: absolute !important; }
    .top-bar-section .has-dropdown > a:focus + .dropdown {
      display: block;
      position: static !important;
      height: auto;
      width: auto;
      overflow: visible;
      clip: auto;
      position: absolute !important; }
    .top-bar-section .has-dropdown .dropdown li.has-dropdown > a:after {
      border: none;
      content: "\00bb";
      top: 1rem;
      margin-top: -1px;
      right: 5px;
      line-height: 1.2; }
    .top-bar-section .dropdown {
      left: 0;
      top: auto;
      background: transparent;
      min-width: 100%; }
      .top-bar-section .dropdown li a {
        color: #FFFFFF;
        line-height: 2.8125rem;
        white-space: nowrap;
        padding: 12px 0.9375rem;
        background: #333333; }
      .top-bar-section .dropdown li:not(.has-form):not(.active) > a:not(.button) {
        color: #FFFFFF;
        background: #333333; }
      .top-bar-section .dropdown li:not(.has-form):not(.active):hover > a:not(.button) {
        color: #FFFFFF;
        background-color: #555555;
        background: #333333; }
      .top-bar-section .dropdown li label {
        white-space: nowrap;
        background: #333333; }
      .top-bar-section .dropdown li .dropdown {
        left: 100%;
        top: 0; }
    .top-bar-section > ul > .divider, .top-bar-section > ul > [role="separator"] {
      border-bottom: none;
      border-top: none;
      border-right: solid 1px #4e4e4e;
      clear: none;
      height: 2.8125rem;
      width: 0; }
    .top-bar-section .has-form {
      background: #333333;
      padding: 0 0.9375rem;
      height: 2.8125rem; }
    .top-bar-section .right li .dropdown {
      left: auto;
      right: 0; }
      .top-bar-section .right li .dropdown li .dropdown {
        right: 100%; }
    .top-bar-section .left li .dropdown {
      right: auto;
      left: 0; }
      .top-bar-section .left li .dropdown li .dropdown {
        left: 100%; }
  .no-js .top-bar-section ul li:hover > a {
    background-color: #555555;
    background: #333333;
    color: #FFFFFF; }
  .no-js .top-bar-section ul li:active > a {
    background: #1f5c87;
    color: #FFFFFF; }
  .no-js .top-bar-section .has-dropdown:hover > .dropdown {
    display: block;
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto;
    position: absolute !important; }
  .no-js .top-bar-section .has-dropdown > a:focus + .dropdown {
    display: block;
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto;
    position: absolute !important; } }

.text-left {
  text-align: left !important; }

.text-right {
  text-align: right !important; }

.text-center {
  text-align: center !important; }

.text-justify {
  text-align: justify !important; }

@media only screen and (max-width: 40em) {
  .small-only-text-left {
    text-align: left !important; }
  .small-only-text-right {
    text-align: right !important; }
  .small-only-text-center {
    text-align: center !important; }
  .small-only-text-justify {
    text-align: justify !important; } }

@media only screen {
  .small-text-left {
    text-align: left !important; }
  .small-text-right {
    text-align: right !important; }
  .small-text-center {
    text-align: center !important; }
  .small-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:40.063em) and (max-width:64em) {
  .medium-only-text-left {
    text-align: left !important; }
  .medium-only-text-right {
    text-align: right !important; }
  .medium-only-text-center {
    text-align: center !important; }
  .medium-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:40.063em) {
  .medium-text-left {
    text-align: left !important; }
  .medium-text-right {
    text-align: right !important; }
  .medium-text-center {
    text-align: center !important; }
  .medium-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:64.063em) and (max-width:90em) {
  .large-only-text-left {
    text-align: left !important; }
  .large-only-text-right {
    text-align: right !important; }
  .large-only-text-center {
    text-align: center !important; }
  .large-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:64.063em) {
  .large-text-left {
    text-align: left !important; }
  .large-text-right {
    text-align: right !important; }
  .large-text-center {
    text-align: center !important; }
  .large-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:90.063em) and (max-width:120em) {
  .xlarge-only-text-left {
    text-align: left !important; }
  .xlarge-only-text-right {
    text-align: right !important; }
  .xlarge-only-text-center {
    text-align: center !important; }
  .xlarge-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:90.063em) {
  .xlarge-text-left {
    text-align: left !important; }
  .xlarge-text-right {
    text-align: right !important; }
  .xlarge-text-center {
    text-align: center !important; }
  .xlarge-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:120.063em) and (max-width:99999999em) {
  .xxlarge-only-text-left {
    text-align: left !important; }
  .xxlarge-only-text-right {
    text-align: right !important; }
  .xxlarge-only-text-center {
    text-align: center !important; }
  .xxlarge-only-text-justify {
    text-align: justify !important; } }

@media only screen and (min-width:120.063em) {
  .xxlarge-text-left {
    text-align: left !important; }
  .xxlarge-text-right {
    text-align: right !important; }
  .xxlarge-text-center {
    text-align: center !important; }
  .xxlarge-text-justify {
    text-align: justify !important; } }

/* Typography resets */
div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, p, blockquote, th, td {
  margin: 0;
  padding: 0; }

/* Default Link Styles */
a {
  color: #1f5c87;
  text-decoration: none;
  line-height: inherit; }
  a:hover, a:focus {
    color: #1f5c87; }
  a img {
    border: none; }

/* Default paragraph styles */
p {
  font-family: inherit;
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.6;
  margin-bottom: 1.25rem;
  text-rendering: optimizeLegibility; }
  p.lead {
    font-size: 1.21875rem;
    line-height: 1.6; }
  p aside {
    font-size: 0.875rem;
    line-height: 1.35;
    font-style: italic; }

/* Default header styles */
h1, h2, h3, h4, h5, h6 {
  font-family: arial, sans-serif;
  font-weight: 400;
  font-style: normal;
  color: #222222;
  text-rendering: optimizeLegibility;
  margin-top: 0.2rem;
  margin-bottom: 0.5rem;
  line-height: 1.2; }
  h1 small, h2 small, h3 small, h4 small, h5 small, h6 small {
    font-size: 60%;
    color: #6f6f6f;
    line-height: 0; }

h1 {
  font-size: 2.125rem; }

h2 {
  font-size: 1.6875rem; }

h3 {
  font-size: 1.375rem; }

h4 {
  font-size: 1.125rem; }

h5 {
  font-size: 1.125rem; }

h6 {
  font-size: 1rem; }

.subheader {
  line-height: 1.4;
  color: #6f6f6f;
  font-weight: 400;
  margin-top: 0.2rem;
  margin-bottom: 0.5rem; }

hr {
  border: solid #DDDDDD;
  border-width: 1px 0 0;
  clear: both;
  margin: 1.25rem 0 1.1875rem;
  height: 0; }

/* Helpful Typography Defaults */
em, i {
  font-style: italic;
  line-height: inherit; }

strong, b {
  font-weight: bold;
  line-height: inherit; }

small {
  font-size: 60%;
  line-height: inherit; }

code {
  font-family: Consolas, "Liberation Mono", Courier, monospace;
  font-weight: 400;
  color: #333333;
  background-color: #f8f8f8;
  border-width: 1px;
  border-style: solid;
  border-color: #dfdfdf;
  padding: 0.125rem 0.3125rem 0.0625rem; }

/* Lists */
ul, ol, dl {
  font-size: 1rem;
  line-height: 1.6;
  margin-bottom: 1.25rem;
  list-style-position: outside;
  font-family: inherit; }

ul {
  margin-left: 1.1rem; }
  ul.no-bullet {
    margin-left: 0; }
    ul.no-bullet li ul, ul.no-bullet li ol {
      margin-left: 1.25rem;
      margin-bottom: 0;
      list-style: none; }

/* Unordered Lists */
ul li ul, ul li ol {
  margin-left: 1.25rem;
  margin-bottom: 0; }
ul.square li ul, ul.circle li ul, ul.disc li ul {
  list-style: inherit; }
ul.square {
  list-style-type: square;
  margin-left: 1.1rem; }
ul.circle {
  list-style-type: circle;
  margin-left: 1.1rem; }
ul.disc {
  list-style-type: disc;
  margin-left: 1.1rem; }
ul.no-bullet {
  list-style: none; }

/* Ordered Lists */
ol {
  margin-left: 1.4rem; }
  ol li ul, ol li ol {
    margin-left: 1.25rem;
    margin-bottom: 0; }

/* Definition Lists */
dl dt {
  margin-bottom: 0.3rem;
  font-weight: bold; }
dl dd {
  margin-bottom: 0.75rem; }

/* Abbreviations */
abbr, acronym {
  text-transform: uppercase;
  font-size: 90%;
  color: #565656;
  cursor: help; }

abbr {
  text-transform: none; }
  abbr[title] {
    border-bottom: 1px dotted #DDDDDD; }

/* Blockquotes */
blockquote {
  margin: 0 0 1.25rem;
  padding: 0.5625rem 1.25rem 0 1.1875rem;
  border-left: 1px solid #DDDDDD; }
  blockquote cite {
    display: block;
    font-size: 0.8125rem;
    color: #555555; }
    blockquote cite:before {
      content: "\2014 \0020"; }
    blockquote cite a, blockquote cite a:visited {
      color: #555555; }

blockquote, blockquote p {
  line-height: 1.6;
  color: #6f6f6f; }

/* Microformats */
.vcard {
  display: inline-block;
  margin: 0 0 1.25rem 0;
  border: 1px solid #DDDDDD;
  padding: 0.625rem 0.75rem; }
  .vcard li {
    margin: 0;
    display: block; }
  .vcard .fn {
    font-weight: bold;
    font-size: 0.9375rem; }

.vevent .summary {
  font-weight: bold; }
.vevent abbr {
  cursor: default;
  text-decoration: none;
  font-weight: bold;
  border: none;
  padding: 0 0.0625rem; }

@media only screen and (min-width:40.063em) {
  h1, h2, h3, h4, h5, h6 {
    line-height: 1.2; }
  h1 {
    font-size: 2.75rem; }
  h2 {
    font-size: 2.3125rem; }
  h3 {
    font-size: 1.6875rem; }
  h4 {
    font-size: 1.4375rem; }
  h5 {
    font-size: 1.125rem; }
  h6 {
    font-size: 1rem; } }

.off-canvas-wrap {
  -webkit-backface-visibility: hidden;
  position: relative;
  width: 100%;
  overflow: hidden; }
  .off-canvas-wrap.move-right, .off-canvas-wrap.move-left {
    min-height: 100%;
    -webkit-overflow-scrolling: touch; }

.inner-wrap {
  position: relative;
  width: 100%;
  -webkit-transition: -webkit-transform 500ms ease;
  -moz-transition: -moz-transform 500ms ease;
  -ms-transition: -ms-transform 500ms ease;
  -o-transition: -o-transform 500ms ease;
  transition: transform 500ms ease; }
  .inner-wrap:before, .inner-wrap:after {
    content: " ";
    display: table; }
  .inner-wrap:after {
    clear: both; }

.tab-bar {
  -webkit-backface-visibility: hidden;
  background: #333333;
  color: #FFFFFF;
  height: 2.8125rem;
  line-height: 2.8125rem;
  position: relative; }
  .tab-bar h1, .tab-bar h2, .tab-bar h3, .tab-bar h4, .tab-bar h5, .tab-bar h6 {
    color: #FFFFFF;
    font-weight: bold;
    line-height: 2.8125rem;
    margin: 0; }
  .tab-bar h1, .tab-bar h2, .tab-bar h3, .tab-bar h4 {
    font-size: 1.125rem; }

.left-small {
  width: 2.8125rem;
  height: 2.8125rem;
  position: absolute;
  top: 0;
  border-right: solid 1px #1a1a1a;
  left: 0; }

.right-small {
  width: 2.8125rem;
  height: 2.8125rem;
  position: absolute;
  top: 0;
  border-left: solid 1px #1a1a1a;
  right: 0; }

.tab-bar-section {
  padding: 0 0.625rem;
  position: absolute;
  text-align: center;
  height: 2.8125rem;
  top: 0; }
  @media only screen and (min-width:40.063em) {
    .tab-bar-section.left {
      text-align: left; }
    .tab-bar-section.right {
      text-align: right; } }
  .tab-bar-section.left {
    left: 0;
    right: 2.8125rem; }
  .tab-bar-section.right {
    left: 2.8125rem;
    right: 0; }
  .tab-bar-section.middle {
    left: 2.8125rem;
    right: 2.8125rem; }

.tab-bar .menu-icon {
  text-indent: 2.1875rem;
  width: 2.8125rem;
  height: 2.8125rem;
  display: block;
  padding: 0;
  color: #FFFFFF;
  position: relative;
  transform: translate3d(0, 0, 0); }
  .tab-bar .menu-icon span::after {
    content: "";
    position: absolute;
    display: block;
    height: 0;
    top: 50%;
    margin-top: -0.5rem;
    left: 0.90625rem;
    box-shadow: 0 0 0 1px #FFFFFF, 0 7px 0 1px #FFFFFF, 0 14px 0 1px #FFFFFF;
    width: 1rem; }
  .tab-bar .menu-icon span:hover:after {
    box-shadow: 0 0 0 1px #b3b3b3, 0 7px 0 1px #b3b3b3, 0 14px 0 1px #b3b3b3; }

.left-off-canvas-menu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1001;
  box-sizing: content-box;
  transition: transform 500ms ease 0s;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar;
  -ms-transform: translate(-100%, 0);
  -webkit-transform: translate3d(-100%, 0, 0);
  -moz-transform: translate3d(-100%, 0, 0);
  -ms-transform: translate3d(-100%, 0, 0);
  -o-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
  left: 0; }
  .left-off-canvas-menu * {
    -webkit-backface-visibility: hidden; }

.right-off-canvas-menu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1001;
  box-sizing: content-box;
  transition: transform 500ms ease 0s;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar;
  -ms-transform: translate(100%, 0);
  -webkit-transform: translate3d(100%, 0, 0);
  -moz-transform: translate3d(100%, 0, 0);
  -ms-transform: translate3d(100%, 0, 0);
  -o-transform: translate3d(100%, 0, 0);
  transform: translate3d(100%, 0, 0);
  right: 0; }
  .right-off-canvas-menu * {
    -webkit-backface-visibility: hidden; }

ul.off-canvas-list {
  list-style-type: none;
  padding: 0;
  margin: 0; }
  ul.off-canvas-list li label {
    display: block;
    padding: 0.3rem 0.9375rem;
    color: #999999;
    text-transform: uppercase;
    font-size: 0.75rem;
    font-weight: bold;
    background: #444444;
    border-top: 1px solid #5e5e5e;
    border-bottom: none;
    margin: 0; }
  ul.off-canvas-list li a {
    display: block;
    padding: 0.6666666667rem;
    color: rgba(255, 255, 255, 0.7);
    border-bottom: 1px solid #262626;
    transition: background 300ms ease; }
    ul.off-canvas-list li a:hover {
      background: #242424; }

.move-right > .inner-wrap {
  -ms-transform: translate(15.625rem, 0);
  -webkit-transform: translate3d(15.625rem, 0, 0);
  -moz-transform: translate3d(15.625rem, 0, 0);
  -ms-transform: translate3d(15.625rem, 0, 0);
  -o-transform: translate3d(15.625rem, 0, 0);
  transform: translate3d(15.625rem, 0, 0); }
.move-right .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .move-right .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.move-left > .inner-wrap {
  -ms-transform: translate(-15.625rem, 0);
  -webkit-transform: translate3d(-15.625rem, 0, 0);
  -moz-transform: translate3d(-15.625rem, 0, 0);
  -ms-transform: translate3d(-15.625rem, 0, 0);
  -o-transform: translate3d(-15.625rem, 0, 0);
  transform: translate3d(-15.625rem, 0, 0); }
.move-left .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .move-left .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.offcanvas-overlap .left-off-canvas-menu, .offcanvas-overlap .right-off-canvas-menu {
  -ms-transform: none;
  -webkit-transform: none;
  -moz-transform: none;
  -o-transform: none;
  transform: none;
  z-index: 1003; }
.offcanvas-overlap .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .offcanvas-overlap .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.offcanvas-overlap-left .right-off-canvas-menu {
  -ms-transform: none;
  -webkit-transform: none;
  -moz-transform: none;
  -o-transform: none;
  transform: none;
  z-index: 1003; }
.offcanvas-overlap-left .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .offcanvas-overlap-left .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.offcanvas-overlap-right .left-off-canvas-menu {
  -ms-transform: none;
  -webkit-transform: none;
  -moz-transform: none;
  -o-transform: none;
  transform: none;
  z-index: 1003; }
.offcanvas-overlap-right .exit-off-canvas {
  -webkit-backface-visibility: hidden;
  transition: background 300ms ease;
  cursor: pointer;
  box-shadow: -4px 0 4px rgba(0, 0, 0, 0.5), 4px 0 4px rgba(0, 0, 0, 0.5);
  display: block;
  position: absolute;
  background: rgba(255, 255, 255, 0.2);
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1002;
  -webkit-tap-highlight-color: transparent; }
  @media only screen and (min-width:40.063em) {
    .offcanvas-overlap-right .exit-off-canvas:hover {
      background: rgba(255, 255, 255, 0.05); } }

.no-csstransforms .left-off-canvas-menu {
  left: -15.625rem; }
.no-csstransforms .right-off-canvas-menu {
  right: -15.625rem; }
.no-csstransforms .move-left > .inner-wrap {
  right: 15.625rem; }
.no-csstransforms .move-right > .inner-wrap {
  left: 15.625rem; }

.left-submenu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  margin: 0;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1002;
  box-sizing: content-box;
  -webkit-overflow-scrolling: touch;
  -ms-transform: translate(-100%, 0);
  -webkit-transform: translate3d(-100%, 0, 0);
  -moz-transform: translate3d(-100%, 0, 0);
  -ms-transform: translate3d(-100%, 0, 0);
  -o-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
  left: 0;
  -webkit-transition: -webkit-transform 500ms ease;
  -moz-transition: -moz-transform 500ms ease;
  -ms-transition: -ms-transform 500ms ease;
  -o-transition: -o-transform 500ms ease;
  transition: transform 500ms ease; }
  .left-submenu * {
    -webkit-backface-visibility: hidden; }
  .left-submenu .back > a {
    padding: 0.3rem 0.9375rem;
    color: #999999;
    text-transform: uppercase;
    font-weight: bold;
    background: #444;
    border-top: 1px solid #5e5e5e;
    border-bottom: none;
    margin: 0; }
    .left-submenu .back > a:hover {
      background: #303030;
      border-top: 1px solid #5e5e5e;
      border-bottom: none; }
    .left-submenu .back > a:before {
      content: "\AB";
      margin-right: 0.5rem;
      display: inline; }
  .left-submenu.move-right, .left-submenu.offcanvas-overlap-right, .left-submenu.offcanvas-overlap {
    -ms-transform: translate(0%, 0);
    -webkit-transform: translate3d(0%, 0, 0);
    -moz-transform: translate3d(0%, 0, 0);
    -ms-transform: translate3d(0%, 0, 0);
    -o-transform: translate3d(0%, 0, 0);
    transform: translate3d(0%, 0, 0); }

.right-submenu {
  -webkit-backface-visibility: hidden;
  width: 15.625rem;
  top: 0;
  bottom: 0;
  position: absolute;
  margin: 0;
  overflow-x: hidden;
  overflow-y: auto;
  background: #333333;
  z-index: 1002;
  box-sizing: content-box;
  -webkit-overflow-scrolling: touch;
  -ms-transform: translate(100%, 0);
  -webkit-transform: translate3d(100%, 0, 0);
  -moz-transform: translate3d(100%, 0, 0);
  -ms-transform: translate3d(100%, 0, 0);
  -o-transform: translate3d(100%, 0, 0);
  transform: translate3d(100%, 0, 0);
  right: 0;
  -webkit-transition: -webkit-transform 500ms ease;
  -moz-transition: -moz-transform 500ms ease;
  -ms-transition: -ms-transform 500ms ease;
  -o-transition: -o-transform 500ms ease;
  transition: transform 500ms ease; }
  .right-submenu * {
    -webkit-backface-visibility: hidden; }
  .right-submenu .back > a {
    padding: 0.3rem 0.9375rem;
    color: #999999;
    text-transform: uppercase;
    font-weight: bold;
    background: #444;
    border-top: 1px solid #5e5e5e;
    border-bottom: none;
    margin: 0; }
    .right-submenu .back > a:hover {
      background: #303030;
      border-top: 1px solid #5e5e5e;
      border-bottom: none; }
    .right-submenu .back > a:after {
      content: "\BB";
      margin-left: 0.5rem;
      display: inline; }
  .right-submenu.move-left, .right-submenu.offcanvas-overlap-left, .right-submenu.offcanvas-overlap {
    -ms-transform: translate(0%, 0);
    -webkit-transform: translate3d(0%, 0, 0);
    -moz-transform: translate3d(0%, 0, 0);
    -ms-transform: translate3d(0%, 0, 0);
    -o-transform: translate3d(0%, 0, 0);
    transform: translate3d(0%, 0, 0); }

.left-off-canvas-menu ul.off-canvas-list li.has-submenu > a:after {
  content: "\BB";
  margin-left: 0.5rem;
  display: inline; }

.right-off-canvas-menu ul.off-canvas-list li.has-submenu > a:before {
  content: "\AB";
  margin-right: 0.5rem;
  display: inline; }

/* small displays */
@media only screen {
  .show-for-small-only, .show-for-small-up, .show-for-small, .show-for-small-down, .hide-for-medium-only, .hide-for-medium-up, .hide-for-medium, .show-for-medium-down, .hide-for-large-only, .hide-for-large-up, .hide-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .hide-for-small-only, .hide-for-small-up, .hide-for-small, .hide-for-small-down, .show-for-medium-only, .show-for-medium-up, .show-for-medium, .hide-for-medium-down, .show-for-large-only, .show-for-large-up, .show-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .visible-for-small-only, .visible-for-small-up, .visible-for-small, .visible-for-small-down, .hidden-for-medium-only, .hidden-for-medium-up, .hidden-for-medium, .visible-for-medium-down, .hidden-for-large-only, .hidden-for-large-up, .hidden-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .hidden-for-small-only, .hidden-for-small-up, .hidden-for-small, .hidden-for-small-down, .visible-for-medium-only, .visible-for-medium-up, .visible-for-medium, .hidden-for-medium-down, .visible-for-large-only, .visible-for-large-up, .visible-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.show-for-small-only, table.show-for-small-up, table.show-for-small, table.show-for-small-down, table.hide-for-medium-only, table.hide-for-medium-up, table.hide-for-medium, table.show-for-medium-down, table.hide-for-large-only, table.hide-for-large-up, table.hide-for-large, table.show-for-large-down, table.hide-for-xlarge-only, table.hide-for-xlarge-up, table.hide-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.show-for-small-only, thead.show-for-small-up, thead.show-for-small, thead.show-for-small-down, thead.hide-for-medium-only, thead.hide-for-medium-up, thead.hide-for-medium, thead.show-for-medium-down, thead.hide-for-large-only, thead.hide-for-large-up, thead.hide-for-large, thead.show-for-large-down, thead.hide-for-xlarge-only, thead.hide-for-xlarge-up, thead.hide-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.show-for-small-only, tbody.show-for-small-up, tbody.show-for-small, tbody.show-for-small-down, tbody.hide-for-medium-only, tbody.hide-for-medium-up, tbody.hide-for-medium, tbody.show-for-medium-down, tbody.hide-for-large-only, tbody.hide-for-large-up, tbody.hide-for-large, tbody.show-for-large-down, tbody.hide-for-xlarge-only, tbody.hide-for-xlarge-up, tbody.hide-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.show-for-small-only, tr.show-for-small-up, tr.show-for-small, tr.show-for-small-down, tr.hide-for-medium-only, tr.hide-for-medium-up, tr.hide-for-medium, tr.show-for-medium-down, tr.hide-for-large-only, tr.hide-for-large-up, tr.hide-for-large, tr.show-for-large-down, tr.hide-for-xlarge-only, tr.hide-for-xlarge-up, tr.hide-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.show-for-small-only, td.show-for-small-only, th.show-for-small-up, td.show-for-small-up, th.show-for-small, td.show-for-small, th.show-for-small-down, td.show-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.hide-for-medium-up, td.hide-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.show-for-medium-down, td.show-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.hide-for-large-up, td.hide-for-large-up, th.hide-for-large, td.hide-for-large, th.show-for-large-down, td.show-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.hide-for-xlarge-up, td.hide-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* medium displays */
@media only screen and (min-width:40.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .show-for-medium-only, .show-for-medium-up, .show-for-medium, .show-for-medium-down, .hide-for-large-only, .hide-for-large-up, .hide-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .hide-for-medium-only, .hide-for-medium-up, .hide-for-medium, .hide-for-medium-down, .show-for-large-only, .show-for-large-up, .show-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .visible-for-medium-only, .visible-for-medium-up, .visible-for-medium, .visible-for-medium-down, .hidden-for-large-only, .hidden-for-large-up, .hidden-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .hidden-for-medium-only, .hidden-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .visible-for-large-only, .visible-for-large-up, .visible-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.show-for-medium-only, table.show-for-medium-up, table.show-for-medium, table.show-for-medium-down, table.hide-for-large-only, table.hide-for-large-up, table.hide-for-large, table.show-for-large-down, table.hide-for-xlarge-only, table.hide-for-xlarge-up, table.hide-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.show-for-medium-only, thead.show-for-medium-up, thead.show-for-medium, thead.show-for-medium-down, thead.hide-for-large-only, thead.hide-for-large-up, thead.hide-for-large, thead.show-for-large-down, thead.hide-for-xlarge-only, thead.hide-for-xlarge-up, thead.hide-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.show-for-medium-only, tbody.show-for-medium-up, tbody.show-for-medium, tbody.show-for-medium-down, tbody.hide-for-large-only, tbody.hide-for-large-up, tbody.hide-for-large, tbody.show-for-large-down, tbody.hide-for-xlarge-only, tbody.hide-for-xlarge-up, tbody.hide-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.show-for-medium-only, tr.show-for-medium-up, tr.show-for-medium, tr.show-for-medium-down, tr.hide-for-large-only, tr.hide-for-large-up, tr.hide-for-large, tr.show-for-large-down, tr.hide-for-xlarge-only, tr.hide-for-xlarge-up, tr.hide-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.show-for-medium-only, td.show-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.show-for-medium, td.show-for-medium, th.show-for-medium-down, td.show-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.hide-for-large-up, td.hide-for-large-up, th.hide-for-large, td.hide-for-large, th.show-for-large-down, td.show-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.hide-for-xlarge-up, td.hide-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* large displays */
@media only screen and (min-width:64.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .hide-for-medium-only, .show-for-medium-up, .hide-for-medium, .hide-for-medium-down, .show-for-large-only, .show-for-large-up, .show-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .show-for-medium-only, .hide-for-medium-up, .show-for-medium, .show-for-medium-down, .hide-for-large-only, .hide-for-large-up, .hide-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .hidden-for-medium-only, .visible-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .visible-for-large-only, .visible-for-large-up, .visible-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .visible-for-medium-only, .hidden-for-medium-up, .visible-for-medium, .visible-for-medium-down, .hidden-for-large-only, .hidden-for-large-up, .hidden-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.hide-for-medium-only, table.show-for-medium-up, table.hide-for-medium, table.hide-for-medium-down, table.show-for-large-only, table.show-for-large-up, table.show-for-large, table.show-for-large-down, table.hide-for-xlarge-only, table.hide-for-xlarge-up, table.hide-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.hide-for-medium-only, thead.show-for-medium-up, thead.hide-for-medium, thead.hide-for-medium-down, thead.show-for-large-only, thead.show-for-large-up, thead.show-for-large, thead.show-for-large-down, thead.hide-for-xlarge-only, thead.hide-for-xlarge-up, thead.hide-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.hide-for-medium-only, tbody.show-for-medium-up, tbody.hide-for-medium, tbody.hide-for-medium-down, tbody.show-for-large-only, tbody.show-for-large-up, tbody.show-for-large, tbody.show-for-large-down, tbody.hide-for-xlarge-only, tbody.hide-for-xlarge-up, tbody.hide-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.hide-for-medium-only, tr.show-for-medium-up, tr.hide-for-medium, tr.hide-for-medium-down, tr.show-for-large-only, tr.show-for-large-up, tr.show-for-large, tr.show-for-large-down, tr.hide-for-xlarge-only, tr.hide-for-xlarge-up, tr.hide-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.hide-for-medium-down, td.hide-for-medium-down, th.show-for-large-only, td.show-for-large-only, th.show-for-large-up, td.show-for-large-up, th.show-for-large, td.show-for-large, th.show-for-large-down, td.show-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.hide-for-xlarge-up, td.hide-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* xlarge displays */
@media only screen and (min-width:90.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .hide-for-medium-only, .show-for-medium-up, .hide-for-medium, .hide-for-medium-down, .hide-for-large-only, .show-for-large-up, .hide-for-large, .hide-for-large-down, .show-for-xlarge-only, .show-for-xlarge-up, .show-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .show-for-medium-only, .hide-for-medium-up, .show-for-medium, .show-for-medium-down, .show-for-large-only, .hide-for-large-up, .show-for-large, .show-for-large-down, .hide-for-xlarge-only, .hide-for-xlarge-up, .hide-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .hidden-for-medium-only, .visible-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .hidden-for-large-only, .visible-for-large-up, .hidden-for-large, .hidden-for-large-down, .visible-for-xlarge-only, .visible-for-xlarge-up, .visible-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .visible-for-medium-only, .hidden-for-medium-up, .visible-for-medium, .visible-for-medium-down, .visible-for-large-only, .hidden-for-large-up, .visible-for-large, .visible-for-large-down, .hidden-for-xlarge-only, .hidden-for-xlarge-up, .hidden-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.hide-for-medium-only, table.show-for-medium-up, table.hide-for-medium, table.hide-for-medium-down, table.hide-for-large-only, table.show-for-large-up, table.hide-for-large, table.hide-for-large-down, table.show-for-xlarge-only, table.show-for-xlarge-up, table.show-for-xlarge, table.show-for-xlarge-down, table.hide-for-xxlarge-only, table.hide-for-xxlarge-up, table.hide-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.hide-for-medium-only, thead.show-for-medium-up, thead.hide-for-medium, thead.hide-for-medium-down, thead.hide-for-large-only, thead.show-for-large-up, thead.hide-for-large, thead.hide-for-large-down, thead.show-for-xlarge-only, thead.show-for-xlarge-up, thead.show-for-xlarge, thead.show-for-xlarge-down, thead.hide-for-xxlarge-only, thead.hide-for-xxlarge-up, thead.hide-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.hide-for-medium-only, tbody.show-for-medium-up, tbody.hide-for-medium, tbody.hide-for-medium-down, tbody.hide-for-large-only, tbody.show-for-large-up, tbody.hide-for-large, tbody.hide-for-large-down, tbody.show-for-xlarge-only, tbody.show-for-xlarge-up, tbody.show-for-xlarge, tbody.show-for-xlarge-down, tbody.hide-for-xxlarge-only, tbody.hide-for-xxlarge-up, tbody.hide-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.hide-for-medium-only, tr.show-for-medium-up, tr.hide-for-medium, tr.hide-for-medium-down, tr.hide-for-large-only, tr.show-for-large-up, tr.hide-for-large, tr.hide-for-large-down, tr.show-for-xlarge-only, tr.show-for-xlarge-up, tr.show-for-xlarge, tr.show-for-xlarge-down, tr.hide-for-xxlarge-only, tr.hide-for-xxlarge-up, tr.hide-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.hide-for-medium-down, td.hide-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.show-for-large-up, td.show-for-large-up, th.hide-for-large, td.hide-for-large, th.hide-for-large-down, td.hide-for-large-down, th.show-for-xlarge-only, td.show-for-xlarge-only, th.show-for-xlarge-up, td.show-for-xlarge-up, th.show-for-xlarge, td.show-for-xlarge, th.show-for-xlarge-down, td.show-for-xlarge-down, th.hide-for-xxlarge-only, td.hide-for-xxlarge-only, th.hide-for-xxlarge-up, td.hide-for-xxlarge-up, th.hide-for-xxlarge, td.hide-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* xxlarge displays */
@media only screen and (min-width:120.063em) {
  .hide-for-small-only, .show-for-small-up, .hide-for-small, .hide-for-small-down, .hide-for-medium-only, .show-for-medium-up, .hide-for-medium, .hide-for-medium-down, .hide-for-large-only, .show-for-large-up, .hide-for-large, .hide-for-large-down, .hide-for-xlarge-only, .show-for-xlarge-up, .hide-for-xlarge, .hide-for-xlarge-down, .show-for-xxlarge-only, .show-for-xxlarge-up, .show-for-xxlarge, .show-for-xxlarge-down {
    display: inherit !important; }
  .show-for-small-only, .hide-for-small-up, .show-for-small, .show-for-small-down, .show-for-medium-only, .hide-for-medium-up, .show-for-medium, .show-for-medium-down, .show-for-large-only, .hide-for-large-up, .show-for-large, .show-for-large-down, .show-for-xlarge-only, .hide-for-xlarge-up, .show-for-xlarge, .show-for-xlarge-down, .hide-for-xxlarge-only, .hide-for-xxlarge-up, .hide-for-xxlarge, .hide-for-xxlarge-down {
    display: none !important; }
  .hidden-for-small-only, .visible-for-small-up, .hidden-for-small, .hidden-for-small-down, .hidden-for-medium-only, .visible-for-medium-up, .hidden-for-medium, .hidden-for-medium-down, .hidden-for-large-only, .visible-for-large-up, .hidden-for-large, .hidden-for-large-down, .hidden-for-xlarge-only, .visible-for-xlarge-up, .hidden-for-xlarge, .hidden-for-xlarge-down, .visible-for-xxlarge-only, .visible-for-xxlarge-up, .visible-for-xxlarge, .visible-for-xxlarge-down {
    position: static !important;
    height: auto;
    width: auto;
    overflow: visible;
    clip: auto; }
  .visible-for-small-only, .hidden-for-small-up, .visible-for-small, .visible-for-small-down, .visible-for-medium-only, .hidden-for-medium-up, .visible-for-medium, .visible-for-medium-down, .visible-for-large-only, .hidden-for-large-up, .visible-for-large, .visible-for-large-down, .visible-for-xlarge-only, .hidden-for-xlarge-up, .visible-for-xlarge, .visible-for-xlarge-down, .hidden-for-xxlarge-only, .hidden-for-xxlarge-up, .hidden-for-xxlarge, .hidden-for-xxlarge-down {
    position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px, 1px, 1px, 1px); }
  table.hide-for-small-only, table.show-for-small-up, table.hide-for-small, table.hide-for-small-down, table.hide-for-medium-only, table.show-for-medium-up, table.hide-for-medium, table.hide-for-medium-down, table.hide-for-large-only, table.show-for-large-up, table.hide-for-large, table.hide-for-large-down, table.hide-for-xlarge-only, table.show-for-xlarge-up, table.hide-for-xlarge, table.hide-for-xlarge-down, table.show-for-xxlarge-only, table.show-for-xxlarge-up, table.show-for-xxlarge, table.show-for-xxlarge-down {
    display: table !important; }
  thead.hide-for-small-only, thead.show-for-small-up, thead.hide-for-small, thead.hide-for-small-down, thead.hide-for-medium-only, thead.show-for-medium-up, thead.hide-for-medium, thead.hide-for-medium-down, thead.hide-for-large-only, thead.show-for-large-up, thead.hide-for-large, thead.hide-for-large-down, thead.hide-for-xlarge-only, thead.show-for-xlarge-up, thead.hide-for-xlarge, thead.hide-for-xlarge-down, thead.show-for-xxlarge-only, thead.show-for-xxlarge-up, thead.show-for-xxlarge, thead.show-for-xxlarge-down {
    display: table-header-group !important; }
  tbody.hide-for-small-only, tbody.show-for-small-up, tbody.hide-for-small, tbody.hide-for-small-down, tbody.hide-for-medium-only, tbody.show-for-medium-up, tbody.hide-for-medium, tbody.hide-for-medium-down, tbody.hide-for-large-only, tbody.show-for-large-up, tbody.hide-for-large, tbody.hide-for-large-down, tbody.hide-for-xlarge-only, tbody.show-for-xlarge-up, tbody.hide-for-xlarge, tbody.hide-for-xlarge-down, tbody.show-for-xxlarge-only, tbody.show-for-xxlarge-up, tbody.show-for-xxlarge, tbody.show-for-xxlarge-down {
    display: table-row-group !important; }
  tr.hide-for-small-only, tr.show-for-small-up, tr.hide-for-small, tr.hide-for-small-down, tr.hide-for-medium-only, tr.show-for-medium-up, tr.hide-for-medium, tr.hide-for-medium-down, tr.hide-for-large-only, tr.show-for-large-up, tr.hide-for-large, tr.hide-for-large-down, tr.hide-for-xlarge-only, tr.show-for-xlarge-up, tr.hide-for-xlarge, tr.hide-for-xlarge-down, tr.show-for-xxlarge-only, tr.show-for-xxlarge-up, tr.show-for-xxlarge, tr.show-for-xxlarge-down {
    display: table-row; }
  th.hide-for-small-only, td.hide-for-small-only, th.show-for-small-up, td.show-for-small-up, th.hide-for-small, td.hide-for-small, th.hide-for-small-down, td.hide-for-small-down, th.hide-for-medium-only, td.hide-for-medium-only, th.show-for-medium-up, td.show-for-medium-up, th.hide-for-medium, td.hide-for-medium, th.hide-for-medium-down, td.hide-for-medium-down, th.hide-for-large-only, td.hide-for-large-only, th.show-for-large-up, td.show-for-large-up, th.hide-for-large, td.hide-for-large, th.hide-for-large-down, td.hide-for-large-down, th.hide-for-xlarge-only, td.hide-for-xlarge-only, th.show-for-xlarge-up, td.show-for-xlarge-up, th.hide-for-xlarge, td.hide-for-xlarge, th.hide-for-xlarge-down, td.hide-for-xlarge-down, th.show-for-xxlarge-only, td.show-for-xxlarge-only, th.show-for-xxlarge-up, td.show-for-xxlarge-up, th.show-for-xxlarge, td.show-for-xxlarge, th.show-for-xxlarge-down, td.show-for-xxlarge-down {
    display: table-cell !important; } }

/* Orientation targeting */
.show-for-landscape, .hide-for-portrait {
  display: inherit !important; }

.hide-for-landscape, .show-for-portrait {
  display: none !important; }

/* Specific visibility for tables */
table.hide-for-landscape, table.show-for-portrait {
  display: table !important; }

thead.hide-for-landscape, thead.show-for-portrait {
  display: table-header-group !important; }

tbody.hide-for-landscape, tbody.show-for-portrait {
  display: table-row-group !important; }

tr.hide-for-landscape, tr.show-for-portrait {
  display: table-row !important; }

td.hide-for-landscape, td.show-for-portrait, th.hide-for-landscape, th.show-for-portrait {
  display: table-cell !important; }

@media only screen and (orientation: landscape) {
  .show-for-landscape, .hide-for-portrait {
    display: inherit !important; }
  .hide-for-landscape, .show-for-portrait {
    display: none !important; }
  /* Specific visibility for tables */
  table.show-for-landscape, table.hide-for-portrait {
    display: table !important; }
  thead.show-for-landscape, thead.hide-for-portrait {
    display: table-header-group !important; }
  tbody.show-for-landscape, tbody.hide-for-portrait {
    display: table-row-group !important; }
  tr.show-for-landscape, tr.hide-for-portrait {
    display: table-row !important; }
  td.show-for-landscape, td.hide-for-portrait, th.show-for-landscape, th.hide-for-portrait {
    display: table-cell !important; } }

@media only screen and (orientation: portrait) {
  .show-for-portrait, .hide-for-landscape {
    display: inherit !important; }
  .hide-for-portrait, .show-for-landscape {
    display: none !important; }
  /* Specific visibility for tables */
  table.show-for-portrait, table.hide-for-landscape {
    display: table !important; }
  thead.show-for-portrait, thead.hide-for-landscape {
    display: table-header-group !important; }
  tbody.show-for-portrait, tbody.hide-for-landscape {
    display: table-row-group !important; }
  tr.show-for-portrait, tr.hide-for-landscape {
    display: table-row !important; }
  td.show-for-portrait, td.hide-for-landscape, th.show-for-portrait, th.hide-for-landscape {
    display: table-cell !important; } }

/* Touch-enabled device targeting */
.show-for-touch {
  display: none !important; }

.hide-for-touch {
  display: inherit !important; }

.touch .show-for-touch {
  display: inherit !important; }

.touch .hide-for-touch {
  display: none !important; }

/* Specific visibility for tables */
table.hide-for-touch {
  display: table !important; }

.touch table.show-for-touch {
  display: table !important; }

thead.hide-for-touch {
  display: table-header-group !important; }

.touch thead.show-for-touch {
  display: table-header-group !important; }

tbody.hide-for-touch {
  display: table-row-group !important; }

.touch tbody.show-for-touch {
  display: table-row-group !important; }

tr.hide-for-touch {
  display: table-row !important; }

.touch tr.show-for-touch {
  display: table-row !important; }

td.hide-for-touch {
  display: table-cell !important; }

.touch td.show-for-touch {
  display: table-cell !important; }

th.hide-for-touch {
  display: table-cell !important; }

.touch th.show-for-touch {
  display: table-cell !important; }

/*
       * Print styles.
       *
       * Inlined to avoid required HTTP connection: www.phpied.com/delay-loading-your-print-css/
       * Credit to Paul Irish and HTML5 Boilerplate (html5boilerplate.com)
      */
.print-only {
  display: none !important; }

@media print {
  * {
    background: transparent !important;
    color: #000000 !important;
    /* Black prints faster: h5bp.com/s */
    box-shadow: none !important;
    text-shadow: none !important; }
  .show-for-print {
    display: block; }
  .hide-for-print {
    display: none; }
  table.show-for-print {
    display: table !important; }
  thead.show-for-print {
    display: table-header-group !important; }
  tbody.show-for-print {
    display: table-row-group !important; }
  tr.show-for-print {
    display: table-row !important; }
  td.show-for-print {
    display: table-cell !important; }
  th.show-for-print {
    display: table-cell !important; }
  a, a:visited {
    text-decoration: underline; }
  a[href]:after {
    content: " (" attr(href) ")"; }
  abbr[title]:after {
    content: " (" attr(title) ")"; }
  .ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after {
    content: ""; }
  pre, blockquote {
    border: 1px solid #999999;
    page-break-inside: avoid; }
  thead {
    display: table-header-group;
    /* h5bp.com/t */ }
  tr, img {
    page-break-inside: avoid; }
  img {
    max-width: 100% !important; }
  @page {
    margin: 0.5cm; }

  p, h2, h3 {
    orphans: 3;
    widows: 3; }
  h2, h3 {
    page-break-after: avoid; }
  .hide-on-print {
    display: none !important; }
  .print-only {
    display: block !important; }
  .hide-for-print {
    display: none !important; }
  .show-for-print {
    display: inherit !important; } }

/* Print visibility */
@media print {
  .show-for-print {
    display: block; }
  .hide-for-print {
    display: none; }
  table.show-for-print {
    display: table !important; }
  thead.show-for-print {
    display: table-header-group !important; }
  tbody.show-for-print {
    display: table-row-group !important; }
  tr.show-for-print {
    display: table-row !important; }
  td.show-for-print {
    display: table-cell !important; }
  th.show-for-print {
    display: table-cell !important; } }

/* 
  Font Awesome - (http://fontawesome.io/) :
  Feel free to remove the import statement below if you don't plan to use icon-fonts in your project
*/
/*!
 *  Font Awesome 4.3.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('./assets/fontawesome/fonts/fontawesome-webfont.eot?v=4.3.0');
  src: url('./assets/fontawesome/fonts/fontawesome-webfont.eot?#iefix&v=4.3.0') format('embedded-opentype'), url('./assets/fontawesome/fonts/fontawesome-webfont.woff2?v=4.3.0') format('woff2'), url('./assets/fontawesome/fonts/fontawesome-webfont.woff?v=4.3.0') format('woff'), url('./assets/fontawesome/fonts/fontawesome-webfont.ttf?v=4.3.0') format('truetype'), url('./assets/fontawesome/fonts/fontawesome-webfont.svg?v=4.3.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal; }

.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  transform: translate(0, 0); }

/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.3333333333em;
  line-height: 0.75em;
  vertical-align: -15%; }

.fa-2x {
  font-size: 2em; }

.fa-3x {
  font-size: 3em; }

.fa-4x {
  font-size: 4em; }

.fa-5x {
  font-size: 5em; }

.fa-fw {
  width: 1.2857142857em;
  text-align: center; }

.fa-ul {
  padding-left: 0;
  margin-left: 2.1428571429em;
  list-style-type: none; }
  .fa-ul > li {
    position: relative; }

.fa-li {
  position: absolute;
  left: -2.1428571429em;
  width: 2.1428571429em;
  top: 0.1428571429em;
  text-align: center; }
  .fa-li.fa-lg {
    left: -1.8571428571em; }

.fa-border {
  padding: .2em .25em .15em;
  border: solid .08em #eee;
  border-radius: .1em; }

.pull-right {
  float: right; }

.pull-left {
  float: left; }

.fa.pull-left {
  margin-right: .3em; }
.fa.pull-right {
  margin-left: .3em; }

.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear; }

.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8); }

@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg); }

  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg); } }

@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg); }

  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg); } }

.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg); }

.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg); }

.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg); }

.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1); }

.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1); }

:root .fa-rotate-90, :root .fa-rotate-180, :root .fa-rotate-270, :root .fa-flip-horizontal, :root .fa-flip-vertical {
  filter: none; }

.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle; }

.fa-stack-1x, .fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center; }

.fa-stack-1x {
  line-height: inherit; }

.fa-stack-2x {
  font-size: 2em; }

.fa-inverse {
  color: #fff; }

/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000"; }

.fa-music:before {
  content: "\f001"; }

.fa-search:before {
  content: "\f002"; }

.fa-envelope-o:before {
  content: "\f003"; }

.fa-heart:before {
  content: "\f004"; }

.fa-star:before {
  content: "\f005"; }

.fa-star-o:before {
  content: "\f006"; }

.fa-user:before {
  content: "\f007"; }

.fa-film:before {
  content: "\f008"; }

.fa-th-large:before {
  content: "\f009"; }

.fa-th:before {
  content: "\f00a"; }

.fa-th-list:before {
  content: "\f00b"; }

.fa-check:before {
  content: "\f00c"; }

.fa-remove:before, .fa-close:before, .fa-times:before {
  content: "\f00d"; }

.fa-search-plus:before {
  content: "\f00e"; }

.fa-search-minus:before {
  content: "\f010"; }

.fa-power-off:before {
  content: "\f011"; }

.fa-signal:before {
  content: "\f012"; }

.fa-gear:before, .fa-cog:before {
  content: "\f013"; }

.fa-trash-o:before {
  content: "\f014"; }

.fa-home:before {
  content: "\f015"; }

.fa-file-o:before {
  content: "\f016"; }

.fa-clock-o:before {
  content: "\f017"; }

.fa-road:before {
  content: "\f018"; }

.fa-download:before {
  content: "\f019"; }

.fa-arrow-circle-o-down:before {
  content: "\f01a"; }

.fa-arrow-circle-o-up:before {
  content: "\f01b"; }

.fa-inbox:before {
  content: "\f01c"; }

.fa-play-circle-o:before {
  content: "\f01d"; }

.fa-rotate-right:before, .fa-repeat:before {
  content: "\f01e"; }

.fa-refresh:before {
  content: "\f021"; }

.fa-list-alt:before {
  content: "\f022"; }

.fa-lock:before {
  content: "\f023"; }

.fa-flag:before {
  content: "\f024"; }

.fa-headphones:before {
  content: "\f025"; }

.fa-volume-off:before {
  content: "\f026"; }

.fa-volume-down:before {
  content: "\f027"; }

.fa-volume-up:before {
  content: "\f028"; }

.fa-qrcode:before {
  content: "\f029"; }

.fa-barcode:before {
  content: "\f02a"; }

.fa-tag:before {
  content: "\f02b"; }

.fa-tags:before {
  content: "\f02c"; }

.fa-book:before {
  content: "\f02d"; }

.fa-bookmark:before {
  content: "\f02e"; }

.fa-print:before {
  content: "\f02f"; }

.fa-camera:before {
  content: "\f030"; }

.fa-font:before {
  content: "\f031"; }

.fa-bold:before {
  content: "\f032"; }

.fa-italic:before {
  content: "\f033"; }

.fa-text-height:before {
  content: "\f034"; }

.fa-text-width:before {
  content: "\f035"; }

.fa-align-left:before {
  content: "\f036"; }

.fa-align-center:before {
  content: "\f037"; }

.fa-align-right:before {
  content: "\f038"; }

.fa-align-justify:before {
  content: "\f039"; }

.fa-list:before {
  content: "\f03a"; }

.fa-dedent:before, .fa-outdent:before {
  content: "\f03b"; }

.fa-indent:before {
  content: "\f03c"; }

.fa-video-camera:before {
  content: "\f03d"; }

.fa-photo:before, .fa-image:before, .fa-picture-o:before {
  content: "\f03e"; }

.fa-pencil:before {
  content: "\f040"; }

.fa-map-marker:before {
  content: "\f041"; }

.fa-adjust:before {
  content: "\f042"; }

.fa-tint:before {
  content: "\f043"; }

.fa-edit:before, .fa-pencil-square-o:before {
  content: "\f044"; }

.fa-share-square-o:before {
  content: "\f045"; }

.fa-check-square-o:before {
  content: "\f046"; }

.fa-arrows:before {
  content: "\f047"; }

.fa-step-backward:before {
  content: "\f048"; }

.fa-fast-backward:before {
  content: "\f049"; }

.fa-backward:before {
  content: "\f04a"; }

.fa-play:before {
  content: "\f04b"; }

.fa-pause:before {
  content: "\f04c"; }

.fa-stop:before {
  content: "\f04d"; }

.fa-forward:before {
  content: "\f04e"; }

.fa-fast-forward:before {
  content: "\f050"; }

.fa-step-forward:before {
  content: "\f051"; }

.fa-eject:before {
  content: "\f052"; }

.fa-chevron-left:before {
  content: "\f053"; }

.fa-chevron-right:before {
  content: "\f054"; }

.fa-plus-circle:before {
  content: "\f055"; }

.fa-minus-circle:before {
  content: "\f056"; }

.fa-times-circle:before {
  content: "\f057"; }

.fa-check-circle:before {
  content: "\f058"; }

.fa-question-circle:before {
  content: "\f059"; }

.fa-info-circle:before {
  content: "\f05a"; }

.fa-crosshairs:before {
  content: "\f05b"; }

.fa-times-circle-o:before {
  content: "\f05c"; }

.fa-check-circle-o:before {
  content: "\f05d"; }

.fa-ban:before {
  content: "\f05e"; }

.fa-arrow-left:before {
  content: "\f060"; }

.fa-arrow-right:before {
  content: "\f061"; }

.fa-arrow-up:before {
  content: "\f062"; }

.fa-arrow-down:before {
  content: "\f063"; }

.fa-mail-forward:before, .fa-share:before {
  content: "\f064"; }

.fa-expand:before {
  content: "\f065"; }

.fa-compress:before {
  content: "\f066"; }

.fa-plus:before {
  content: "\f067"; }

.fa-minus:before {
  content: "\f068"; }

.fa-asterisk:before {
  content: "\f069"; }

.fa-exclamation-circle:before {
  content: "\f06a"; }

.fa-gift:before {
  content: "\f06b"; }

.fa-leaf:before {
  content: "\f06c"; }

.fa-fire:before {
  content: "\f06d"; }

.fa-eye:before {
  content: "\f06e"; }

.fa-eye-slash:before {
  content: "\f070"; }

.fa-warning:before, .fa-exclamation-triangle:before {
  content: "\f071"; }

.fa-plane:before {
  content: "\f072"; }

.fa-calendar:before {
  content: "\f073"; }

.fa-random:before {
  content: "\f074"; }

.fa-comment:before {
  content: "\f075"; }

.fa-magnet:before {
  content: "\f076"; }

.fa-chevron-up:before {
  content: "\f077"; }

.fa-chevron-down:before {
  content: "\f078"; }

.fa-retweet:before {
  content: "\f079"; }

.fa-shopping-cart:before {
  content: "\f07a"; }

.fa-folder:before {
  content: "\f07b"; }

.fa-folder-open:before {
  content: "\f07c"; }

.fa-arrows-v:before {
  content: "\f07d"; }

.fa-arrows-h:before {
  content: "\f07e"; }

.fa-bar-chart-o:before, .fa-bar-chart:before {
  content: "\f080"; }

.fa-twitter-square:before {
  content: "\f081"; }

.fa-facebook-square:before {
  content: "\f082"; }

.fa-camera-retro:before {
  content: "\f083"; }

.fa-key:before {
  content: "\f084"; }

.fa-gears:before, .fa-cogs:before {
  content: "\f085"; }

.fa-comments:before {
  content: "\f086"; }

.fa-thumbs-o-up:before {
  content: "\f087"; }

.fa-thumbs-o-down:before {
  content: "\f088"; }

.fa-star-half:before {
  content: "\f089"; }

.fa-heart-o:before {
  content: "\f08a"; }

.fa-sign-out:before {
  content: "\f08b"; }

.fa-linkedin-square:before {
  content: "\f08c"; }

.fa-thumb-tack:before {
  content: "\f08d"; }

.fa-external-link:before {
  content: "\f08e"; }

.fa-sign-in:before {
  content: "\f090"; }

.fa-trophy:before {
  content: "\f091"; }

.fa-github-square:before {
  content: "\f092"; }

.fa-upload:before {
  content: "\f093"; }

.fa-lemon-o:before {
  content: "\f094"; }

.fa-phone:before {
  content: "\f095"; }

.fa-square-o:before {
  content: "\f096"; }

.fa-bookmark-o:before {
  content: "\f097"; }

.fa-phone-square:before {
  content: "\f098"; }

.fa-twitter:before {
  content: "\f099"; }

.fa-facebook-f:before, .fa-facebook:before {
  content: "\f09a"; }

.fa-github:before {
  content: "\f09b"; }

.fa-unlock:before {
  content: "\f09c"; }

.fa-credit-card:before {
  content: "\f09d"; }

.fa-rss:before {
  content: "\f09e"; }

.fa-hdd-o:before {
  content: "\f0a0"; }

.fa-bullhorn:before {
  content: "\f0a1"; }

.fa-bell:before {
  content: "\f0f3"; }

.fa-certificate:before {
  content: "\f0a3"; }

.fa-hand-o-right:before {
  content: "\f0a4"; }

.fa-hand-o-left:before {
  content: "\f0a5"; }

.fa-hand-o-up:before {
  content: "\f0a6"; }

.fa-hand-o-down:before {
  content: "\f0a7"; }

.fa-arrow-circle-left:before {
  content: "\f0a8"; }

.fa-arrow-circle-right:before {
  content: "\f0a9"; }

.fa-arrow-circle-up:before {
  content: "\f0aa"; }

.fa-arrow-circle-down:before {
  content: "\f0ab"; }

.fa-globe:before {
  content: "\f0ac"; }

.fa-wrench:before {
  content: "\f0ad"; }

.fa-tasks:before {
  content: "\f0ae"; }

.fa-filter:before {
  content: "\f0b0"; }

.fa-briefcase:before {
  content: "\f0b1"; }

.fa-arrows-alt:before {
  content: "\f0b2"; }

.fa-group:before, .fa-users:before {
  content: "\f0c0"; }

.fa-chain:before, .fa-link:before {
  content: "\f0c1"; }

.fa-cloud:before {
  content: "\f0c2"; }

.fa-flask:before {
  content: "\f0c3"; }

.fa-cut:before, .fa-scissors:before {
  content: "\f0c4"; }

.fa-copy:before, .fa-files-o:before {
  content: "\f0c5"; }

.fa-paperclip:before {
  content: "\f0c6"; }

.fa-save:before, .fa-floppy-o:before {
  content: "\f0c7"; }

.fa-square:before {
  content: "\f0c8"; }

.fa-navicon:before, .fa-reorder:before, .fa-bars:before {
  content: "\f0c9"; }

.fa-list-ul:before {
  content: "\f0ca"; }

.fa-list-ol:before {
  content: "\f0cb"; }

.fa-strikethrough:before {
  content: "\f0cc"; }

.fa-underline:before {
  content: "\f0cd"; }

.fa-table:before {
  content: "\f0ce"; }

.fa-magic:before {
  content: "\f0d0"; }

.fa-truck:before {
  content: "\f0d1"; }

.fa-pinterest:before {
  content: "\f0d2"; }

.fa-pinterest-square:before {
  content: "\f0d3"; }

.fa-google-plus-square:before {
  content: "\f0d4"; }

.fa-google-plus:before {
  content: "\f0d5"; }

.fa-money:before {
  content: "\f0d6"; }

.fa-caret-down:before {
  content: "\f0d7"; }

.fa-caret-up:before {
  content: "\f0d8"; }

.fa-caret-left:before {
  content: "\f0d9"; }

.fa-caret-right:before {
  content: "\f0da"; }

.fa-columns:before {
  content: "\f0db"; }

.fa-unsorted:before, .fa-sort:before {
  content: "\f0dc"; }

.fa-sort-down:before, .fa-sort-desc:before {
  content: "\f0dd"; }

.fa-sort-up:before, .fa-sort-asc:before {
  content: "\f0de"; }

.fa-envelope:before {
  content: "\f0e0"; }

.fa-linkedin:before {
  content: "\f0e1"; }

.fa-rotate-left:before, .fa-undo:before {
  content: "\f0e2"; }

.fa-legal:before, .fa-gavel:before {
  content: "\f0e3"; }

.fa-dashboard:before, .fa-tachometer:before {
  content: "\f0e4"; }

.fa-comment-o:before {
  content: "\f0e5"; }

.fa-comments-o:before {
  content: "\f0e6"; }

.fa-flash:before, .fa-bolt:before {
  content: "\f0e7"; }

.fa-sitemap:before {
  content: "\f0e8"; }

.fa-umbrella:before {
  content: "\f0e9"; }

.fa-paste:before, .fa-clipboard:before {
  content: "\f0ea"; }

.fa-lightbulb-o:before {
  content: "\f0eb"; }

.fa-exchange:before {
  content: "\f0ec"; }

.fa-cloud-download:before {
  content: "\f0ed"; }

.fa-cloud-upload:before {
  content: "\f0ee"; }

.fa-user-md:before {
  content: "\f0f0"; }

.fa-stethoscope:before {
  content: "\f0f1"; }

.fa-suitcase:before {
  content: "\f0f2"; }

.fa-bell-o:before {
  content: "\f0a2"; }

.fa-coffee:before {
  content: "\f0f4"; }

.fa-cutlery:before {
  content: "\f0f5"; }

.fa-file-text-o:before {
  content: "\f0f6"; }

.fa-building-o:before {
  content: "\f0f7"; }

.fa-hospital-o:before {
  content: "\f0f8"; }

.fa-ambulance:before {
  content: "\f0f9"; }

.fa-medkit:before {
  content: "\f0fa"; }

.fa-fighter-jet:before {
  content: "\f0fb"; }

.fa-beer:before {
  content: "\f0fc"; }

.fa-h-square:before {
  content: "\f0fd"; }

.fa-plus-square:before {
  content: "\f0fe"; }

.fa-angle-double-left:before {
  content: "\f100"; }

.fa-angle-double-right:before {
  content: "\f101"; }

.fa-angle-double-up:before {
  content: "\f102"; }

.fa-angle-double-down:before {
  content: "\f103"; }

.fa-angle-left:before {
  content: "\f104"; }

.fa-angle-right:before {
  content: "\f105"; }

.fa-angle-up:before {
  content: "\f106"; }

.fa-angle-down:before {
  content: "\f107"; }

.fa-desktop:before {
  content: "\f108"; }

.fa-laptop:before {
  content: "\f109"; }

.fa-tablet:before {
  content: "\f10a"; }

.fa-mobile-phone:before, .fa-mobile:before {
  content: "\f10b"; }

.fa-circle-o:before {
  content: "\f10c"; }

.fa-quote-left:before {
  content: "\f10d"; }

.fa-quote-right:before {
  content: "\f10e"; }

.fa-spinner:before {
  content: "\f110"; }

.fa-circle:before {
  content: "\f111"; }

.fa-mail-reply:before, .fa-reply:before {
  content: "\f112"; }

.fa-github-alt:before {
  content: "\f113"; }

.fa-folder-o:before {
  content: "\f114"; }

.fa-folder-open-o:before {
  content: "\f115"; }

.fa-smile-o:before {
  content: "\f118"; }

.fa-frown-o:before {
  content: "\f119"; }

.fa-meh-o:before {
  content: "\f11a"; }

.fa-gamepad:before {
  content: "\f11b"; }

.fa-keyboard-o:before {
  content: "\f11c"; }

.fa-flag-o:before {
  content: "\f11d"; }

.fa-flag-checkered:before {
  content: "\f11e"; }

.fa-terminal:before {
  content: "\f120"; }

.fa-code:before {
  content: "\f121"; }

.fa-mail-reply-all:before, .fa-reply-all:before {
  content: "\f122"; }

.fa-star-half-empty:before, .fa-star-half-full:before, .fa-star-half-o:before {
  content: "\f123"; }

.fa-location-arrow:before {
  content: "\f124"; }

.fa-crop:before {
  content: "\f125"; }

.fa-code-fork:before {
  content: "\f126"; }

.fa-unlink:before, .fa-chain-broken:before {
  content: "\f127"; }

.fa-question:before {
  content: "\f128"; }

.fa-info:before {
  content: "\f129"; }

.fa-exclamation:before {
  content: "\f12a"; }

.fa-superscript:before {
  content: "\f12b"; }

.fa-subscript:before {
  content: "\f12c"; }

.fa-eraser:before {
  content: "\f12d"; }

.fa-puzzle-piece:before {
  content: "\f12e"; }

.fa-microphone:before {
  content: "\f130"; }

.fa-microphone-slash:before {
  content: "\f131"; }

.fa-shield:before {
  content: "\f132"; }

.fa-calendar-o:before {
  content: "\f133"; }

.fa-fire-extinguisher:before {
  content: "\f134"; }

.fa-rocket:before {
  content: "\f135"; }

.fa-maxcdn:before {
  content: "\f136"; }

.fa-chevron-circle-left:before {
  content: "\f137"; }

.fa-chevron-circle-right:before {
  content: "\f138"; }

.fa-chevron-circle-up:before {
  content: "\f139"; }

.fa-chevron-circle-down:before {
  content: "\f13a"; }

.fa-html5:before {
  content: "\f13b"; }

.fa-css3:before {
  content: "\f13c"; }

.fa-anchor:before {
  content: "\f13d"; }

.fa-unlock-alt:before {
  content: "\f13e"; }

.fa-bullseye:before {
  content: "\f140"; }

.fa-ellipsis-h:before {
  content: "\f141"; }

.fa-ellipsis-v:before {
  content: "\f142"; }

.fa-rss-square:before {
  content: "\f143"; }

.fa-play-circle:before {
  content: "\f144"; }

.fa-ticket:before {
  content: "\f145"; }

.fa-minus-square:before {
  content: "\f146"; }

.fa-minus-square-o:before {
  content: "\f147"; }

.fa-level-up:before {
  content: "\f148"; }

.fa-level-down:before {
  content: "\f149"; }

.fa-check-square:before {
  content: "\f14a"; }

.fa-pencil-square:before {
  content: "\f14b"; }

.fa-external-link-square:before {
  content: "\f14c"; }

.fa-share-square:before {
  content: "\f14d"; }

.fa-compass:before {
  content: "\f14e"; }

.fa-toggle-down:before, .fa-caret-square-o-down:before {
  content: "\f150"; }

.fa-toggle-up:before, .fa-caret-square-o-up:before {
  content: "\f151"; }

.fa-toggle-right:before, .fa-caret-square-o-right:before {
  content: "\f152"; }

.fa-euro:before, .fa-eur:before {
  content: "\f153"; }

.fa-gbp:before {
  content: "\f154"; }

.fa-dollar:before, .fa-usd:before {
  content: "\f155"; }

.fa-rupee:before, .fa-inr:before {
  content: "\f156"; }

.fa-cny:before, .fa-rmb:before, .fa-yen:before, .fa-jpy:before {
  content: "\f157"; }

.fa-ruble:before, .fa-rouble:before, .fa-rub:before {
  content: "\f158"; }

.fa-won:before, .fa-krw:before {
  content: "\f159"; }

.fa-bitcoin:before, .fa-btc:before {
  content: "\f15a"; }

.fa-file:before {
  content: "\f15b"; }

.fa-file-text:before {
  content: "\f15c"; }

.fa-sort-alpha-asc:before {
  content: "\f15d"; }

.fa-sort-alpha-desc:before {
  content: "\f15e"; }

.fa-sort-amount-asc:before {
  content: "\f160"; }

.fa-sort-amount-desc:before {
  content: "\f161"; }

.fa-sort-numeric-asc:before {
  content: "\f162"; }

.fa-sort-numeric-desc:before {
  content: "\f163"; }

.fa-thumbs-up:before {
  content: "\f164"; }

.fa-thumbs-down:before {
  content: "\f165"; }

.fa-youtube-square:before {
  content: "\f166"; }

.fa-youtube:before {
  content: "\f167"; }

.fa-xing:before {
  content: "\f168"; }

.fa-xing-square:before {
  content: "\f169"; }

.fa-youtube-play:before {
  content: "\f16a"; }

.fa-dropbox:before {
  content: "\f16b"; }

.fa-stack-overflow:before {
  content: "\f16c"; }

.fa-instagram:before {
  content: "\f16d"; }

.fa-flickr:before {
  content: "\f16e"; }

.fa-adn:before {
  content: "\f170"; }

.fa-bitbucket:before {
  content: "\f171"; }

.fa-bitbucket-square:before {
  content: "\f172"; }

.fa-tumblr:before {
  content: "\f173"; }

.fa-tumblr-square:before {
  content: "\f174"; }

.fa-long-arrow-down:before {
  content: "\f175"; }

.fa-long-arrow-up:before {
  content: "\f176"; }

.fa-long-arrow-left:before {
  content: "\f177"; }

.fa-long-arrow-right:before {
  content: "\f178"; }

.fa-apple:before {
  content: "\f179"; }

.fa-windows:before {
  content: "\f17a"; }

.fa-android:before {
  content: "\f17b"; }

.fa-linux:before {
  content: "\f17c"; }

.fa-dribbble:before {
  content: "\f17d"; }

.fa-skype:before {
  content: "\f17e"; }

.fa-foursquare:before {
  content: "\f180"; }

.fa-trello:before {
  content: "\f181"; }

.fa-female:before {
  content: "\f182"; }

.fa-male:before {
  content: "\f183"; }

.fa-gittip:before, .fa-gratipay:before {
  content: "\f184"; }

.fa-sun-o:before {
  content: "\f185"; }

.fa-moon-o:before {
  content: "\f186"; }

.fa-archive:before {
  content: "\f187"; }

.fa-bug:before {
  content: "\f188"; }

.fa-vk:before {
  content: "\f189"; }

.fa-weibo:before {
  content: "\f18a"; }

.fa-renren:before {
  content: "\f18b"; }

.fa-pagelines:before {
  content: "\f18c"; }

.fa-stack-exchange:before {
  content: "\f18d"; }

.fa-arrow-circle-o-right:before {
  content: "\f18e"; }

.fa-arrow-circle-o-left:before {
  content: "\f190"; }

.fa-toggle-left:before, .fa-caret-square-o-left:before {
  content: "\f191"; }

.fa-dot-circle-o:before {
  content: "\f192"; }

.fa-wheelchair:before {
  content: "\f193"; }

.fa-vimeo-square:before {
  content: "\f194"; }

.fa-turkish-lira:before, .fa-try:before {
  content: "\f195"; }

.fa-plus-square-o:before {
  content: "\f196"; }

.fa-space-shuttle:before {
  content: "\f197"; }

.fa-slack:before {
  content: "\f198"; }

.fa-envelope-square:before {
  content: "\f199"; }

.fa-wordpress:before {
  content: "\f19a"; }

.fa-openid:before {
  content: "\f19b"; }

.fa-institution:before, .fa-bank:before, .fa-university:before {
  content: "\f19c"; }

.fa-mortar-board:before, .fa-graduation-cap:before {
  content: "\f19d"; }

.fa-yahoo:before {
  content: "\f19e"; }

.fa-google:before {
  content: "\f1a0"; }

.fa-reddit:before {
  content: "\f1a1"; }

.fa-reddit-square:before {
  content: "\f1a2"; }

.fa-stumbleupon-circle:before {
  content: "\f1a3"; }

.fa-stumbleupon:before {
  content: "\f1a4"; }

.fa-delicious:before {
  content: "\f1a5"; }

.fa-digg:before {
  content: "\f1a6"; }

.fa-pied-piper:before {
  content: "\f1a7"; }

.fa-pied-piper-alt:before {
  content: "\f1a8"; }

.fa-drupal:before {
  content: "\f1a9"; }

.fa-joomla:before {
  content: "\f1aa"; }

.fa-language:before {
  content: "\f1ab"; }

.fa-fax:before {
  content: "\f1ac"; }

.fa-building:before {
  content: "\f1ad"; }

.fa-child:before {
  content: "\f1ae"; }

.fa-paw:before {
  content: "\f1b0"; }

.fa-spoon:before {
  content: "\f1b1"; }

.fa-cube:before {
  content: "\f1b2"; }

.fa-cubes:before {
  content: "\f1b3"; }

.fa-behance:before {
  content: "\f1b4"; }

.fa-behance-square:before {
  content: "\f1b5"; }

.fa-steam:before {
  content: "\f1b6"; }

.fa-steam-square:before {
  content: "\f1b7"; }

.fa-recycle:before {
  content: "\f1b8"; }

.fa-automobile:before, .fa-car:before {
  content: "\f1b9"; }

.fa-cab:before, .fa-taxi:before {
  content: "\f1ba"; }

.fa-tree:before {
  content: "\f1bb"; }

.fa-spotify:before {
  content: "\f1bc"; }

.fa-deviantart:before {
  content: "\f1bd"; }

.fa-soundcloud:before {
  content: "\f1be"; }

.fa-database:before {
  content: "\f1c0"; }

.fa-file-pdf-o:before {
  content: "\f1c1"; }

.fa-file-word-o:before {
  content: "\f1c2"; }

.fa-file-excel-o:before {
  content: "\f1c3"; }

.fa-file-powerpoint-o:before {
  content: "\f1c4"; }

.fa-file-photo-o:before, .fa-file-picture-o:before, .fa-file-image-o:before {
  content: "\f1c5"; }

.fa-file-zip-o:before, .fa-file-archive-o:before {
  content: "\f1c6"; }

.fa-file-sound-o:before, .fa-file-audio-o:before {
  content: "\f1c7"; }

.fa-file-movie-o:before, .fa-file-video-o:before {
  content: "\f1c8"; }

.fa-file-code-o:before {
  content: "\f1c9"; }

.fa-vine:before {
  content: "\f1ca"; }

.fa-codepen:before {
  content: "\f1cb"; }

.fa-jsfiddle:before {
  content: "\f1cc"; }

.fa-life-bouy:before, .fa-life-buoy:before, .fa-life-saver:before, .fa-support:before, .fa-life-ring:before {
  content: "\f1cd"; }

.fa-circle-o-notch:before {
  content: "\f1ce"; }

.fa-ra:before, .fa-rebel:before {
  content: "\f1d0"; }

.fa-ge:before, .fa-empire:before {
  content: "\f1d1"; }

.fa-git-square:before {
  content: "\f1d2"; }

.fa-git:before {
  content: "\f1d3"; }

.fa-hacker-news:before {
  content: "\f1d4"; }

.fa-tencent-weibo:before {
  content: "\f1d5"; }

.fa-qq:before {
  content: "\f1d6"; }

.fa-wechat:before, .fa-weixin:before {
  content: "\f1d7"; }

.fa-send:before, .fa-paper-plane:before {
  content: "\f1d8"; }

.fa-send-o:before, .fa-paper-plane-o:before {
  content: "\f1d9"; }

.fa-history:before {
  content: "\f1da"; }

.fa-genderless:before, .fa-circle-thin:before {
  content: "\f1db"; }

.fa-header:before {
  content: "\f1dc"; }

.fa-paragraph:before {
  content: "\f1dd"; }

.fa-sliders:before {
  content: "\f1de"; }

.fa-share-alt:before {
  content: "\f1e0"; }

.fa-share-alt-square:before {
  content: "\f1e1"; }

.fa-bomb:before {
  content: "\f1e2"; }

.fa-soccer-ball-o:before, .fa-futbol-o:before {
  content: "\f1e3"; }

.fa-tty:before {
  content: "\f1e4"; }

.fa-binoculars:before {
  content: "\f1e5"; }

.fa-plug:before {
  content: "\f1e6"; }

.fa-slideshare:before {
  content: "\f1e7"; }

.fa-twitch:before {
  content: "\f1e8"; }

.fa-yelp:before {
  content: "\f1e9"; }

.fa-newspaper-o:before {
  content: "\f1ea"; }

.fa-wifi:before {
  content: "\f1eb"; }

.fa-calculator:before {
  content: "\f1ec"; }

.fa-paypal:before {
  content: "\f1ed"; }

.fa-google-wallet:before {
  content: "\f1ee"; }

.fa-cc-visa:before {
  content: "\f1f0"; }

.fa-cc-mastercard:before {
  content: "\f1f1"; }

.fa-cc-discover:before {
  content: "\f1f2"; }

.fa-cc-amex:before {
  content: "\f1f3"; }

.fa-cc-paypal:before {
  content: "\f1f4"; }

.fa-cc-stripe:before {
  content: "\f1f5"; }

.fa-bell-slash:before {
  content: "\f1f6"; }

.fa-bell-slash-o:before {
  content: "\f1f7"; }

.fa-trash:before {
  content: "\f1f8"; }

.fa-copyright:before {
  content: "\f1f9"; }

.fa-at:before {
  content: "\f1fa"; }

.fa-eyedropper:before {
  content: "\f1fb"; }

.fa-paint-brush:before {
  content: "\f1fc"; }

.fa-birthday-cake:before {
  content: "\f1fd"; }

.fa-area-chart:before {
  content: "\f1fe"; }

.fa-pie-chart:before {
  content: "\f200"; }

.fa-line-chart:before {
  content: "\f201"; }

.fa-lastfm:before {
  content: "\f202"; }

.fa-lastfm-square:before {
  content: "\f203"; }

.fa-toggle-off:before {
  content: "\f204"; }

.fa-toggle-on:before {
  content: "\f205"; }

.fa-bicycle:before {
  content: "\f206"; }

.fa-bus:before {
  content: "\f207"; }

.fa-ioxhost:before {
  content: "\f208"; }

.fa-angellist:before {
  content: "\f209"; }

.fa-cc:before {
  content: "\f20a"; }

.fa-shekel:before, .fa-sheqel:before, .fa-ils:before {
  content: "\f20b"; }

.fa-meanpath:before {
  content: "\f20c"; }

.fa-buysellads:before {
  content: "\f20d"; }

.fa-connectdevelop:before {
  content: "\f20e"; }

.fa-dashcube:before {
  content: "\f210"; }

.fa-forumbee:before {
  content: "\f211"; }

.fa-leanpub:before {
  content: "\f212"; }

.fa-sellsy:before {
  content: "\f213"; }

.fa-shirtsinbulk:before {
  content: "\f214"; }

.fa-simplybuilt:before {
  content: "\f215"; }

.fa-skyatlas:before {
  content: "\f216"; }

.fa-cart-plus:before {
  content: "\f217"; }

.fa-cart-arrow-down:before {
  content: "\f218"; }

.fa-diamond:before {
  content: "\f219"; }

.fa-ship:before {
  content: "\f21a"; }

.fa-user-secret:before {
  content: "\f21b"; }

.fa-motorcycle:before {
  content: "\f21c"; }

.fa-street-view:before {
  content: "\f21d"; }

.fa-heartbeat:before {
  content: "\f21e"; }

.fa-venus:before {
  content: "\f221"; }

.fa-mars:before {
  content: "\f222"; }

.fa-mercury:before {
  content: "\f223"; }

.fa-transgender:before {
  content: "\f224"; }

.fa-transgender-alt:before {
  content: "\f225"; }

.fa-venus-double:before {
  content: "\f226"; }

.fa-mars-double:before {
  content: "\f227"; }

.fa-venus-mars:before {
  content: "\f228"; }

.fa-mars-stroke:before {
  content: "\f229"; }

.fa-mars-stroke-v:before {
  content: "\f22a"; }

.fa-mars-stroke-h:before {
  content: "\f22b"; }

.fa-neuter:before {
  content: "\f22c"; }

.fa-facebook-official:before {
  content: "\f230"; }

.fa-pinterest-p:before {
  content: "\f231"; }

.fa-whatsapp:before {
  content: "\f232"; }

.fa-server:before {
  content: "\f233"; }

.fa-user-plus:before {
  content: "\f234"; }

.fa-user-times:before {
  content: "\f235"; }

.fa-hotel:before, .fa-bed:before {
  content: "\f236"; }

.fa-viacoin:before {
  content: "\f237"; }

.fa-train:before {
  content: "\f238"; }

.fa-subway:before {
  content: "\f239"; }

.fa-medium:before {
  content: "\f23a"; }

/* 
  My custom styles:
  Add your own folders and scss files for your project and import them below
*/
body {
  color: #6C6C6C;
  font-family: arial, sans-serif; }
  body h1, body h2, body h3, body h4, body h5, body h6 {
    color: #6C6C6C; }
  body a {
    color: #1f5c87; }
  body .author {
    text-transform: uppercase; }
  body input[type=submit] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    font-size: 1.25em;
    background-color: transparent;
    padding: .25em .25em .25em 0;
    border: none;
    margin-top: 3px; }

body .Masthead {
  padding-top: 15px; }
  body .Masthead div.MastheadLogo {
    padding-bottom: 15px; }
  body .Masthead .social {
    text-align: right; }
    body .Masthead .social .social-links {
      font-size: 1.5em;
      text-align: right; }
      body .Masthead .social .social-links a {
        color: #989898; }
        body .Masthead .social .social-links a:hover {
          color: #1f5c87; }
  body .Masthead form.search div div div:last-child {
    padding-left: 0;
    margin-left: 0; }
  body .Masthead form.search div div div input[type=submit] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    font-size: 1.25em;
    background-color: transparent;
    padding: .25em .25em .25em 0;
    border: none;
    margin-top: 3px; }
  body .Masthead nav.navigation ul {
    list-style: none;
    margin-bottom: .25rem; }
    body .Masthead nav.navigation ul li {
      font-size: 1em;
      display: inline-block;
      vertical-align: top;
      padding: 5px 10px; }
      body .Masthead nav.navigation ul li a {
        color: #1f5c87; }
      body .Masthead nav.navigation ul li a:hover {
        color: #000000; }
      body .Masthead nav.navigation ul li ul li {
        display: block; }
  body .Masthead .mobile-nav {
    font-size: 2em;
    text-align: right;
    padding-right: 5px; }
  body .Masthead .right-off-canvas-menu {
    background: #000000; }
    body .Masthead .right-off-canvas-menu ul {
      list-style: none; }
      body .Masthead .right-off-canvas-menu ul li {
        font-size: 1.5em;
        border: none;
        padding: 15px 0; }
        body .Masthead .right-off-canvas-menu ul li a {
          color: #FFFFFF; }
body .title {
  background-color: #000;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  display: table;
  height: 400px;
  width: 100%;
  margin-bottom: 35px; }
  body .title .row {
    display: table-cell;
    vertical-align: middle; }
    body .title .row header {
      display: block;
      max-width: 68.75rem;
      margin: 0 auto; }
      body .title .row header h1, body .title .row header h5, body .title .row header a {
        color: #FFFFFF; }
      body .title .row header h1 {
        font-size: 2.75em;
        line-height: 1;
        margin-bottom: 0; }
      body .title .row header h5 {
        color: #FFFFFF;
        font-family: Arial, san-serif;
        display: inline-block; }
        body .title .row header h5:first-child:after {
          content: '|';
          margin: 0 5px; }
body .content {
  margin-bottom: 100px; }
  body .content main header h3 {
    color: #BABABA;
    font-family: Arial, san-serif;
    font-size: 2em;
    text-transform: uppercase;
    margin-bottom: 10px; }
  body .content main ul {
    margin-left: 0; }
  body .content main article header h4 {
    font-size: 2em; }
  body .content main article header .author h5 {
    font-family: Arial, san-serif;
    font-size: 1em;
    line-height: 1;
    display: inline-block;
    padding-bottom: 0; }
    body .content main article header .author h5:first-child:after {
      content: '|';
      margin: 0 5px; }
  body .content main article section {
    margin-top: 5px; }
  body .content main .alm-btn-wrap {
    text-align: center; }
    body .content main .alm-btn-wrap #load-more {
      color: #6C6C6C;
      font-size: 1.25em;
      background-color: #E7E7E7; }
  body .content aside#sidebar h3 {
    color: #BABABA;
    font-family: Arial, san-serif;
    font-size: 1.5em;
    text-transform: uppercase;
    margin-bottom: 10px; }
  body .content aside#sidebar ul {
    list-style-type: none;
    padding: 0;
    margin: 0; }
    body .content aside#sidebar ul li {
      margin-bottom: 35px; }
      body .content aside#sidebar ul li:last-child {
        margin-bottom: 0; }
      body .content aside#sidebar ul li h4 {
        font-size: 1.25em; }
      body .content aside#sidebar ul li h5 {
        font-family: Arial, san-serif;
        font-size: 1em;
        line-height: 1;
        padding-bottom: 0; }
  body .content aside#sidebar .feature-block {
    margin: 45px 0; }
    body .content aside#sidebar .feature-block img {
      display: block;
      height: auto;
      max-height: 250px;
      width: 100%;
      max-width: 300px;
      margin: 0 auto; }
body #footer {
  padding-top: 35px;
  background-color: #E7E7E7;
  max-width: 100%; }
  body #footer nav ul, body #footer .menu-footer-nav-container ul {
    list-style: none;
    padding: 0;
    margin: 0; }
    body #footer nav ul li, body #footer .menu-footer-nav-container ul li {
      display: inline-block;
      vertical-align: top;
      padding: 5px 30px 5px 0; }
  body #footer .social-links {
    font-size: 1.5em;
    float: right; }

@media only screen and (min-width: 48rem) {
  body .Masthead .mobile-nav {
    display: none; } }

@media only screen and (max-width: 48rem) {
  body .social {
    display: none; }
  body .Masthead div, body .Masthead nav {
    height: 100%; }
    body .Masthead div div.search, body .Masthead nav div.search {
      display: none; }
    body .Masthead div nav.navigation, body .Masthead nav nav.navigation {
      display: none; }
    body .Masthead div .social, body .Masthead nav .social {
      text-align: center; }
  body #footer .navigation li {
    display: block;
    padding: 15px 0; }
  body #footer .social-links {
    display: none; } }

body.archive .title > div {
  background-color: rgba(0, 0, 0, 0.5); }
body.archive main header h1 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  text-transform: uppercase; }

body.home .content main h2 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  font-size: 2.5em;
  text-transform: uppercase;
  margin-bottom: 20px; }

body.page .title {
  height: auto;
  padding-top: 35px;
  padding-bottom: 35px; }
body.page article h2 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  font-size: 1.5em;
  text-transform: uppercase; }

body.search .title, body.error404 .title {
  height: auto;
  padding-top: 35px;
  padding-bottom: 35px; }

body.single .title > div {
  background-color: rgba(0, 0, 0, 0.5); }
body.single article h2 {
  color: #BABABA;
  font-family: Arial, sans-serif;
  font-size: 1.5em;
  text-transform: uppercase; }
body.single article .addthis-toolbox {
  margin: 15px 0; }

body .featured-boxes {
  margin-top: 35px;
  margin-bottom: 35px; }
  body .featured-boxes .featured-box {
    height: 300px;
    padding: 10px; }
    body .featured-boxes .featured-box:hover > .wrapper {
      // background-image: none !important;
      // background-color: #1f5c87; }
    body .featured-boxes .featured-box .wrapper {
      background-color: #E7E7E7;
      background-color: #000;
      background-repeat: no-repeat;
      background-position: center center;
      background-size: cover;
      height: 100%;
      width: 100%; }
      body .featured-boxes .featured-box .wrapper article {
        color: #FFFFFF;
        background-color: rgba(0,0,0,.5);
        padding: 15px;
        height: 100%;
        width: 100%; }
        body .featured-boxes .featured-box .wrapper article a {
          display: table;
          height: 100%;
          width: 100%; }
        body .featured-boxes .featured-box .wrapper article h4, body .featured-boxes .featured-box .wrapper article h5, body .featured-boxes .featured-box .wrapper article a {
          font-size: 1.125rem;
          color: #FFFFFF;
          line-height: 1rem; }
        body .featured-boxes .featured-box .wrapper article .article-title {
          display: table-cell;
          vertical-align: bottom; }
          body .featured-boxes .featured-box .wrapper article .article-title h4 {
            font-family: arial, sans-serif; }
          body .featured-boxes .featured-box .wrapper article .article-title h4:hover {
            text-decoration: underline; }  
          body .featured-boxes .featured-box .wrapper article .article-title .author h5, body .featured-boxes .featured-box .wrapper article .article-title .author a {
            line-height: 1rem;
            margin-bottom: 0;
            font-size: 1rem;
            font-family: Arial, sans-serif;
            text-transform: none; }

body .featured-slideshow {
  max-width: 100%; }
  body .featured-slideshow .orbit-container {
    background-color: #FFF;
    height: 400px;
    width: 100%; }
    body .featured-slideshow .orbit-container ul {
      height: inherit;
      background-color: #1f5c87; }
      body .featured-slideshow .orbit-container ul li {
        height: inherit;
        background-color: #000;
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover; }
        body .featured-slideshow .orbit-container ul li a {
          color: #FFFFFF;
          background-color: rgba(0, 0, 0, 0.5);
          height: inherit;
          display: table;
          width: 100%; }
          body .featured-slideshow .orbit-container ul li a:hover h1 {
            text-decoration: underline; }
          body .featured-slideshow .orbit-container ul li a section {
          	text-align: center;
            display: table-cell;
            vertical-align: middle; }
            body .featured-slideshow .orbit-container ul li a section h1 {
              color: #FFFFFF;
              display: block;
              max-width: 68.75rem;
              padding: 0 30px;
              margin: 0 auto; }
            body .featured-slideshow .orbit-container ul li a section span {
              display: block;
              max-width: 68.75rem;
              padding: 0 30px;
              margin: 0 auto; }
            body .featured-slideshow .orbit-container ul li a section h4 {
              color: #FFFFFF; }
            body .featured-slideshow .orbit-container ul li a section h5 {
              color: #FFFFFF;
              display: inline-block;
              font-family: Arial, sans-serif; }
              body .featured-slideshow .orbit-container ul li a section h5:first-child:after {
                content: '|';
                margin: 0 5px; }
  body .featured-slideshow .slide-controls {
    background-color: #000000; }
    body .featured-slideshow .slide-controls .disc {
      max-width: 68.75rem;
      margin-left: auto;
      margin-right: auto; }
      body .featured-slideshow .slide-controls .disc .slide-control {
        background-color: transparent;
        height: 1px;
        padding-top: 0;
        padding-bottom: 0; }
        body .featured-slideshow .slide-controls .disc .slide-control.active {
          background-color: #1f5c87; }
  body .featured-slideshow .slide-titles {
    background-color: #000000; }
    body .featured-slideshow .slide-titles .disc {
      list-style: none;
      height: 100%;
      max-width: 68.75rem;
      margin-right: auto;
      margin-left: auto; }
      body .featured-slideshow .slide-titles .disc .slide-title {
      	text-align: center;
        padding: 35px; }
        body .featured-slideshow .slide-titles .disc .slide-title a {
          position: relative; }
          body .featured-slideshow .slide-titles .disc .slide-title a h5 {
            color: #FFFFFF;
            font-family: Arial, sans-serif;
            font-size: 1em; }
          body .featured-slideshow .slide-titles .disc .slide-title a .author h5 {
            color: #FFFFFF;
            font-family: arial, sans-serif;
            font-size: .9em;
            line-height: 1.25;
            text-transform: none;
            margin: 0; }

@media screen and (max-width: 48rem) {
  body .featured-slideshow .slide-control {
    display: none; } }

/*# sourceMappingURL=style.css.map */
