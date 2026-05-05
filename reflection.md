# Reflection

## 1. What is `position: absolute` and why is it useful for a layout like this magazine cover? What would happen if you removed it?

`position: absolute` removes an element from the normal document flow and positions it relative to its nearest positioned ancestor. It's useful for the magazine cover because it allows precise placement of headings and text over the background image, creating a layered design effect. If removed, the elements would stack vertically in the normal flow, overlapping the background and losing the intended layout.

## 2. What does the `::before` pseudo-element do, and why is it useful to add decorative elements this way instead of adding extra HTML tags?

The `::before` pseudo-element inserts content before the content of an element using CSS, without adding extra HTML. It's useful for decorative elements like the black bars behind the headings because it keeps the HTML semantic and clean, separating presentation from structure, and allows for easy styling changes.

## 3. What challenges did you face when trying to position elements on the cover? How did you use the browser's DevTools to help?

Positioning elements precisely on the cover was challenging due to the need for exact pixel values and overlapping layers. I used Chrome DevTools to inspect elements, toggle styles, and experiment with `top`, `left`, and `right` values in real-time, allowing me to see changes instantly and fine-tune positions without repeatedly editing the CSS file.