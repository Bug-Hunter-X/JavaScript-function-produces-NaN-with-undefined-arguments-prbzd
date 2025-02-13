# JavaScript Function with Unexpected NaN Result

This repository demonstrates a common JavaScript issue where using `undefined` values in functions with conditional logic leads to unexpected `NaN` results. The `foo` function behaves erratically when it receives undefined as input. The solution addresses this issue by handling undefined inputs gracefully.

## Bug Report

The `foo` function should return predictable results even when undefined values are passed as arguments. However, it currently returns `NaN` in these cases.

## Solution

The solution utilizes a conditional check for undefined values and employs appropriate fallback mechanisms to prevent the generation of `NaN`.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` to observe the unexpected behavior.
3. Run `bugSolution.js` to see the fixed implementation.
