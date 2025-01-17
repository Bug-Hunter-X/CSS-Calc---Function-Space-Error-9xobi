# CSS Calc() Function Space Error
This repository demonstrates a common error when using the `calc()` function in CSS: forgetting spaces around the operators.  The incorrect usage leads to unexpected results and layout issues. The solution showcases the correct syntax and the importance of including spaces for proper calculation.

## Bug Description
In CSS, when using the `calc()` function to dynamically calculate values, spaces around the operators (+, -, *, /) are essential.  Omitting them prevents the function from parsing correctly.

## Solution
The solution corrects the syntax by adding spaces around the operators within the `calc()` function. This ensures accurate calculations and proper rendering of CSS styles.

## How to Reproduce the Bug
1. Open `bug.css`.
2. Observe the incorrect usage of `calc()` in the `width` property.
3. See how the intended width is not achieved.

## How to Fix the Bug
1. Open `bugSolution.css`
2. See how the addition of spaces resolves the issue.