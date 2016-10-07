Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


Documentation
=============

Part 1
------
- `dracula.html` and `vatsyayana.html` has inline styling, so I had to move my `<link>` to below it to allow it to overwrite theirs.

- Changed the background to #f1f1d4, a colour that more resembles parchment paper
- Changed the font-family of the entire page to a more rounded, larger font (Palatino)
- Increased the line-height of paragraphs to 1.5x for easier readability
- Added `mix-blend-mode: multiply` to images to remove white backgrounds
- Removed background color from `a` tags because why were they even there??
- Changed the color of links to brown so they don't stand out so distractingly
- Made the `p` font size a bit bigger
- Italicized `pre`
- Added a margin to `body` and `pre` to homogenize the three pages
- Added some styles to make the Pride and Prejudice Contents table look nicer including adding media queries to have an appropriate number of columns at different screen widths
- I don't think I can do anything to improve the look of the Dracula Contents table without modifying the html

Part 2
------
- Got help creating js-less tabs from https://css-tricks.com/functional-css-tabs-revisited/
- Ideas from image in inspiration/
