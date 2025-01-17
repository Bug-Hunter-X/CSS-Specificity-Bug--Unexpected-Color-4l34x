# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity that can lead to unexpected visual outcomes.  The bug arises from a misunderstanding of how CSS selectors' specificity is resolved, which is not always intuitive.

## Bug Description

A CSS rule targeting a nested element may not be applied as expected due to a more general rule having higher specificity.  This occurs even when the more general rule is placed earlier or later in the stylesheet.

## How to Reproduce

1. Clone the repository.
2. Open `index.html` in your web browser.
3. Observe the text color; it will be red, not green as one might initially expect.

## Solution

The solution involves understanding and applying CSS specificity rules correctly, potentially using more specific selectors to ensure the desired style is applied.

The solution is provided in `bugSolution.css`