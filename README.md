# CSS Specificity Issue: Unexpected Behavior with Combined ID and Class Selectors

This repository demonstrates a subtle but important issue related to CSS specificity.  The problem arises when combining ID and class selectors, which can lead to unexpected results if the specificity rules aren't fully understood.

## Problem

The `bug.css` file contains CSS rules that illustrate the unexpected behavior.  An element with both an ID and a class may not behave as anticipated due to CSS specificity calculations. 

## Solution

The `bugSolution.css` file provides a solution.  This solution might involve restructuring the CSS selectors or adjusting the order to obtain the desired styling behavior.  Understanding how CSS specificity works is crucial for avoiding these types of problems.

## How to reproduce

1. Clone this repository.
2. Open `index.html` in your web browser (you might need to create a simple HTML to test this).
3. Observe the unexpected styling behavior.
4. View `bugSolution.css` to see how the problem can be addressed.