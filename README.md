# CSS Float Layout Issue: Unexpected Behavior with 50% Width

This repository demonstrates an uncommon issue with CSS float layout. The bug involves using `float: left` to achieve a 50% width layout for multiple divs. Under certain circumstances, this can lead to unexpected behavior and layout inconsistencies across different browsers.

## Bug Description
The provided CSS code snippet intends to make two divs occupy half of the screen width each. However, this might not always work as expected due to several factors:

1. **Parent Container Width:** If the parent container doesn't have a specified width, the divs might not occupy exactly 50% of the viewport width.
2. **Margins and Padding:** If the total width of the two divs, plus their margins and padding, exceeds the parent container's width, the layout can break and the divs may overflow or wrap to the next line.

## Solution
The solution involves using flexbox or grid layout to avoid the issues associated with the float layout. This ensures a more reliable and consistent layout across different browsers and viewport sizes.