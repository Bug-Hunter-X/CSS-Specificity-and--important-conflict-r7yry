# CSS Specificity and !important Conflict

This repository demonstrates an uncommon CSS issue related to specificity and the `!important` declaration. The bug showcases a scenario where `!important` overrides expected specificity rules. The solution provides a more maintainable approach that avoids the use of `!important`.

## Bug Description

The provided CSS demonstrates unexpected behavior due to the use of `!important` in relation to class specificity.  The solution explains a more effective method to manage styles without relying on `!important` which can cause issues with maintainability and unexpected behavior as CSS rules become more complex.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and examine the CSS code.
3. Open `bugSolution.css` to see the solution which avoids `!important`. 
4. Examine how the changes in `bugSolution.css` provide the same results but in a more manageable way.

## Solution

The solution presented eliminates the reliance on `!important` by utilizing more effective CSS structuring and specificity rules.  This ensures a cleaner and more maintainable codebase.
