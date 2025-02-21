# Tailwind CSS Button Misalignment Bug

This repository demonstrates a bug encountered when using Tailwind CSS to center a button within a flex container. Despite using the `justify-center` and `items-center` classes, the button appears misaligned due to unexpected padding or margin.

## Bug Description
The bug is caused by conflicting or excessive padding or margin styles applied to the button element, overriding the effects of the flexbox alignment classes.  This results in the button not being centered as intended. The solution involves identifying and adjusting these conflicting styles.

## Reproduction Steps
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe the misaligned button.

## Solution
The solution is provided in `solution.html`, demonstrating how to correct the misalignment by adjusting padding or margin as needed to achieve correct centering within the flex container.