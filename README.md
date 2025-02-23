# Uncommon CSS `calc()` Errors

This repository demonstrates two uncommon errors related to the CSS `calc()` function and provides solutions.

## Bug 1: Parent Width Issues
The `calc()` function calculates a value based on the parent element's width. If the parent element's width is not explicitly set or is determined automatically, `calc()` can produce unexpected results.  This is because the `100%` used within `calc()` might be interpreted before the parent element's width is actually determined.

## Bug 2: Spacing Errors
Forgetting to add spaces around the operators in `calc()` can lead to parsing errors in some browsers. Always make sure to properly space your operators (+, -, *, /) within the `calc()` expression.

## Solutions
The `bugSolution.css` file provides solutions for these issues.