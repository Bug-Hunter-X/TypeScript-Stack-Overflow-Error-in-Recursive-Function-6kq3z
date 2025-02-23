# TypeScript Stack Overflow Error in Recursive Function

This repository demonstrates a common error in TypeScript: stack overflow errors in recursive functions.  The provided code includes a recursive function that lacks an appropriate base case and can lead to stack overflow errors for large inputs. The solution demonstrates how to add a sufficient base case to prevent this error.

## How to reproduce

1. Clone the repository.
2. Run `tsc bug.ts` to compile the code.
3. Run `node bug.js`.  You'll likely see a stack overflow error for the `printNumbers2` function.
4. Run `tsc bugSolution.ts` and `node bugSolution.js` to see the corrected version.

## Additional Notes

Stack overflow errors are a common problem when working with recursion.  Ensure your recursive functions always have a well-defined base case to prevent this type of error.