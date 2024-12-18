# Unexpected CSS Float Behavior

This repository demonstrates an uncommon CSS bug related to the behavior of `float` when the parent element's width is not explicitly defined.  The `bug.css` file contains the problematic code.  The solution, shown in `bugSolution.css`, provides a fix.

The bug involves the unexpected collapsing or misbehavior of floating elements when their parent lacks a specified width. This can lead to unexpected layout and positioning, especially in older or less-compliant browsers.  The solution addresses this by explicitly setting the parent's width or using alternative layout techniques.

## How to reproduce

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Observe the layout differences between the buggy and fixed versions.

## Solution

The solution avoids the reliance on implicit width calculation by explicitly setting the width of the parent container or by using a more modern layout technique such as flexbox or grid.