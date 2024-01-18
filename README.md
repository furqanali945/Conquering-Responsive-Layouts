# Conquering-Responsive-Layouts

It's all about making responsive layouts.

## Challenge 1

- Limit the total width of the .intro-conent to about half of it's parent
- Stop the text from overflowing out the bottom at small screen widths

## Solution 1

- I have set the width to 50% for the .intro-content also with percentage it will be responsive on all screens.
- In the problem since we were using height for the container that is why the content was overflowing from the bottom so I have removed it.

## Challenge 2

- Keep the text inside .intro-content in the same place, but have the background extend from one side of the viewport to the other, no matter how wide or narrow the browser is.
- Limit the maximum width of the text in the bottom area.

## Solution 2

- I have added an extra div for the background so that it can be full-width. Also, set the container max-width to be 750px to lock it.
- On the bottom text I have wrap it in div and set max-width to be 750px so it is locked as per the top div.
- Also, added padding to both the divs so that they don't stick to the screen on small devices.
