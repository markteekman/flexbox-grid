# Flexbox Grid
**Powerful, simple, responsive.**

Flexbox Grid is a simple yet powerful responsive front-end grid based on the Flexbox CSS property. It helps you to quickly build advanced layouts for prototyping and real-life projects. Either choose the minified CSS version or the SCSS version to get started. The SCSS version includes a responsive breakpoint mixin as a **bonus** 😉

**Browser support**: All major browsers including Firefox, Safari, Chrome, Opera and Edgde. Includes fallbacks for Internet Explorer 11+.

[DEMO WITH EXAMPLES AND OPTIONS](#) (coming soon..)

## Minified CSS
The quickest way to get started is to include the minified CSS version into your project:

```html
<head>
  <link rel="stylesheet" href="/css/flexbox-grid-min.css">
</head>
```

**Note**: Be sure to include a reset like [Normalize](https://necolas.github.io/normalize.css/) or your own version for setting the default box-sizing, margins and paddings. The minified version sets the box-sizing to default. This minimizes deviations between browsers.

Basic usage (see the demo for all examples and options):

```html
<div class="container">
  <div class="grid">
    <div class="cell small-12 medium-4">
      <!-- your html -->
    </div>
    <div class="cell small-12 medium-8">
      <!-- your html -->
    </div>
  </div>
</div>
```

## SCSS
To use the SCSS version just include the partial files into your project. You can find the variables of the responsive breakpoints and your grid in the `app.scss` file. As a bonus you can use the breakpoint mixin with the the pre-defined breakpoint variables (small, medium, large and huge). For example:

```scss
@include breakpoint(medium) {
  // your styles for the medium and larger breakpoint
}
```

Or use the custom breakpoint:

```scss
@include breakpoint(840) {
  // your styles for the 840px and larger breakpoint
}
```

**Tip**: To minimize deviations between browsers use vendor prefixing and CSS resets when compiling your SCSS.

## License
MIT license. Use it however you like 😄

## Inspiration
Inspired by some awesome people and organizations on the web: Zell Liew, ZURB's Foundation, CSS Tricks and Solved by Flexbox to name a few.

## Something not working right?
Let me know by submitting an issue. I'll see what I can do!
