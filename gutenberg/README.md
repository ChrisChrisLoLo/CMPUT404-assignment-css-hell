I removed any `<style>` tags in the gutenberg html files, and added 

```html
<link rel="stylesheet" href="style.css">
```
to each file to insert my own styling.

For Pride and Predujice (3.html), I had to remove the "width" css property on the `<img>` element and the `<div class="fig">` element.
This was so I could use flexbox to properly center the image.