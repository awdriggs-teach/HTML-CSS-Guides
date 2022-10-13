# Box Model
In HTML, everything is a box!

## Stacking
HTML Elements will either want to stack on top of each other or side by side. This is based on the `display` property in CSS.

### Display Block
When an element is display block, it will automatically take up the entire width of the screen.

These elements are display block by default:
- headlines `<h1>`
- paragraphs `<p>`
- divs and other section tags, `<div>` `<header>` `<footer>` `<main>`

You can make make any HTML element be display block by adding this CSS.
```CSS
selector {
display: block;
}
```

### Display inline
When elements are display inline, they will only take up the space they need and site side by side with other elements.

These elements are display inline by default:
- images `<img>`
- span tags `<span>`
- links `<a>`

You can make any HTML element to be display inline by adding this CSS.
```CSS
selector {
display: inline;
}
```

### Inline Block
Elements can be display inline block. This means they will be in line with other elements, but will be like a block and take up a certain amount of space.

You can make any element inline block by adding this CSS.
```CSS
selector {
display: inline-block;
}
```

## [Try it now!](https://www.w3schools.com/css/tryit.asp?filename=trycss_inline-block_span1)

# References
- [W3 Schools Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [MDN Inline elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)
