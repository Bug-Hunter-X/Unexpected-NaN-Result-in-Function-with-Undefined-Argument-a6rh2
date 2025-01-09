# Unexpected NaN Result in JavaScript Function

This repository demonstrates a subtle bug in a JavaScript function that results in an unexpected `NaN` value when an undefined argument is passed.

## Bug Description
The `foo` function is intended to handle null values gracefully by returning 0. However, when an `undefined` argument is passed, it returns `NaN` instead of a more meaningful value or raising an error.  This inconsistency can lead to unexpected behavior in applications.

## Reproduction
1. Clone this repository.
2. Run `bug.js` using a JavaScript interpreter (like Node.js): `node bug.js`

## Solution
The `bugSolution.js` file provides a corrected version of the `foo` function that explicitly handles undefined values, resulting in more predictable behavior.  The solution checks for both null and undefined using strict equality. 

## Contributing
Contributions to improve this example or add more complex scenarios are welcome!