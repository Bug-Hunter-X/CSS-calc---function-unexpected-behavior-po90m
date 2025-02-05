# CSS calc() Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function when the parent element's width is not explicitly defined.  The `bug.css` file contains the problematic CSS code, while `bugSolution.css` offers a solution to prevent unexpected behavior.

## Problem
The `calc()` function calculates values based on other values, but if the parent element's width is dynamic (like percentage-based) or not set, unexpected results may occur, as the calculations depend on the parent's size.  The width might be smaller than anticipated.

## Solution
Explicitly setting the parent's width ensures the `calc()` function has a reliable reference point for its calculations. The solution provided in `bugSolution.css` demonstrates this approach.