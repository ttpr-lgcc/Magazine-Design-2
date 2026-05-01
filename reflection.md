### What is ```position: absolute``` and why is it useful for a layout like this magazine cover? What would happen if you removed it?
```position: absolute``` lets you take the content you have on your page and place it where ever you want using top, bottom, left, right. If you remove it the content would return back to its normal position with everything stacked vertically.

### What does the ::before pseudo-element do, and why is it useful to add decorative elements this way instead of adding extra HTML tags?
The ```::before``` pseudo-element lets you add decorative elements before the html content. This is better then adding extra html tags because it keeps the HTML clean. 

### What challenges did you face when trying to position elements on the cover? How did you use the browser's DevTools to help?
The challenges I faced was that at first all the contributor names were placed ontop of each other in one single line. I used dev tools to try out different styling methods until I realized I needed to use ```line-height``` so they were stacked verically one after the other. 
