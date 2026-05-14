# Reflection

## 1. What is position: absolute and why is it useful for a layout like this magazine cover? What would happen if you removed it?

Position: absolute allows elements to be placed exactly where you want them on the page using top, left, right, and bottom values. It is useful for a magazine cover because the text needs to appear in very specific spots on top of the image. If position: absolute was removed, all the headings and paragraphs would stack normally and the cover layout would look messy and unorganized.

## 2. What does the ::before pseudo-element do, and why is it useful to add decorative elements this way instead of adding extra HTML tags?

The ::before pseudo-element adds content before an element without needing extra HTML code. It is useful for decorative shapes and effects like the black rectangles behind the text on the magazine cover. This keeps the HTML cleaner and makes the design easier to manage with CSS only.

## 3. What challenges did you face when trying to position elements on the cover? How did you use the browser's DevTools to help?

One challenge was making the text line up correctly with the background image because small changes in pixel values moved the text a lot. Another challenge was making sure the headings did not overlap each other. I used the browser DevTools to test different top and left values quickly and see the changes in real time before saving them in the CSS file.