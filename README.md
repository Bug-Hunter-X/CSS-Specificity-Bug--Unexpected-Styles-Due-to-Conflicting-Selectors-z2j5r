# CSS Specificity Bug

This repository demonstrates a common issue in CSS: unexpected styling due to conflicting selectors and specificity.  The `bug.css` file contains CSS code that exhibits this issue.  The `bugSolution.css` file provides a solution to resolve the conflicting styles by clarifying the specificity and/or adjusting the CSS rules.

## Bug Description
When multiple styles affect the same element, the browser needs a mechanism to determine which style to apply.  CSS specificity determines this, but understanding its nuances can be challenging. Incorrect specificity can cause unexpected visual results.  The example in `bug.css` demonstrates a situation where specificity leads to undesired styling, and the fix in `bugSolution.css` offers a way to address it.