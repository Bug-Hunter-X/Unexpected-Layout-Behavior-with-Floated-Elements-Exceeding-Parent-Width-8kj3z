# Unexpected Layout Behavior with Floated Elements Exceeding Parent Width

This repository demonstrates an uncommon bug related to using the `float` property in CSS.  The bug manifests when the total width of floated elements exceeds the width of their parent container.  This can lead to unpredictable layout behavior across different browsers.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file provides a solution to mitigate the issue.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` (you'll need to create a simple HTML file to test this) in your browser.
3. Observe the layout behavior. Note any inconsistencies between different browsers or unexpected scrolling.

## Solution

The solution involves using techniques like `overflow: hidden;` or `clear: both;` on the parent container to control the behavior of floated elements when they extend beyond the parent's boundaries.