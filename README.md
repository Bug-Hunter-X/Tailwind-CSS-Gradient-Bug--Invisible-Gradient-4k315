# Tailwind CSS Gradient Bug

This repository demonstrates a subtle bug in Tailwind CSS where a gradient background may appear invisible if the `from` and `to` colors are too similar.

## Bug Description
The `bg-gradient-to-r` utility is used to create a linear gradient from one color to another.  However, if these colors are almost identical, the transition is imperceptible, and the resulting element appears to have a solid color background instead of a gradient.

## Solution
Choose colors with sufficient contrast to ensure the gradient is clearly visible.

## Code Samples
See `bug.js` and `solution.js` for code demonstrating the problem and its solution.