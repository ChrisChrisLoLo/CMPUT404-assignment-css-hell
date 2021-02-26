Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

Christian's Notes
=================
I removed any `<style>` tags in the gutenberg html files, and added 

```html
<link rel="stylesheet" href="style.css">
```
to each file to insert my own styling.

For Pride and Predujice (3.html), I had to remove the "width" css property on the `<img>` element and the `<div class="fig">` element.
This was so I could use flexbox to properly center the image.

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

style.css, bad.css, good.css, bad.html, good.html is copyright Christian Lo (C) 2020 under the CC-BY-SA 4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2020 Christian Lo visibile in the text.

Files above licensed under the Apache 2.0 license.