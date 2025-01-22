# Unhandled Exception in TypeScript: Division by Zero

This repository demonstrates a common error in TypeScript: failing to handle potential runtime exceptions. The `bug.ts` file contains a function that divides two numbers, but it doesn't handle the case where the divisor is zero.  The `bugSolution.ts` file shows how to properly handle the error using a `try...catch` block.  This example highlights the importance of robust error handling in preventing unexpected program crashes.

## How to Run

1. Clone the repository.
2. Compile and run the files using a TypeScript compiler (tsc) and Node.js.

## Key Concepts

* **Error Handling:**  The importance of anticipating and handling potential errors (such as division by zero).
* **Try...Catch Blocks:** Using `try...catch` blocks in TypeScript to gracefully handle exceptions and prevent program termination.
* **Robust Code:** Writing code that anticipates and manages potential problems, enhancing its reliability and stability.