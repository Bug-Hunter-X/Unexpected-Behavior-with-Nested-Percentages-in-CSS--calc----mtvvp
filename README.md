# Unexpected Behavior with Nested Percentages in CSS `calc()`

This repository demonstrates an uncommon issue encountered when using the `calc()` function in CSS, specifically involving nested percentage calculations. The problem arises from the order of operations within `calc()` and how percentages are resolved relative to the parent container's dimensions.

The `bug.css` file contains code that exhibits this unexpected behavior. The `bugSolution.css` file offers a corrected approach.

## Issue Description:

When percentages are used in nested `calc()` functions, the final calculated value may differ from the expected outcome due to the way the browser interprets and evaluates the expression. This is primarily because the percentage values are resolved relative to the parent element's size after the `calc()` function completes its computation.

## Solution:

The solution involves restructuring the `calc()` function to ensure correct order of operations or using alternative methods to achieve the desired layout.

## How to reproduce:

1. Open `bug.html` in a web browser.
2. Observe the unexpected layout of the elements.
3. Open `bugSolution.html` to see the corrected layout.
