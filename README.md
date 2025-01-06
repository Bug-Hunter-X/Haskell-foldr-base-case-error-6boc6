# Haskell foldr Base Case Error

This repository demonstrates a common error encountered when using the `foldr` function in Haskell: an incorrect base case that leads to unexpected behavior, particularly when dealing with empty lists.

The `bug.hs` file contains the erroneous code, which uses `foldr` to compute the sum of a list. The `bugSolution.hs` file provides a corrected version.

This example highlights the importance of carefully considering the base case in recursive functions. A seemingly minor mistake can lead to significant issues in program correctness.