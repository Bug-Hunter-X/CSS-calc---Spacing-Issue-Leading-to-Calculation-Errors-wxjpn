# CSS `calc()` Spacing Issue

This repository demonstrates a common, yet easily overlooked, error when using the `calc()` function in CSS. Incorrect spacing around the mathematical operators within the `calc()` function can lead to unexpected and incorrect calculations.

## The Bug

The issue arises when extra spaces are included before or after the plus (+), minus (-), multiply (*), or divide (/) operators within the `calc()` function.

## The Solution

The solution is simple: remove any unnecessary spaces immediately adjacent to the operators to ensure correct calculation.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`. Observe the difference and the resulting rendered widths of the `.element` class.

## Further Notes

Always be mindful of spacing when working with CSS `calc()`.  Proper spacing is crucial for the correct functioning of this powerful feature.