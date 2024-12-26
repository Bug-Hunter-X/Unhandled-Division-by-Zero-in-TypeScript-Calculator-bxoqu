# Unhandled Division by Zero in TypeScript Calculator

This repository demonstrates a common error in TypeScript: unhandled division by zero. The `bug.ts` file contains a simple calculator with a `divide` function that throws an error if the divisor is zero.  The `bugSolution.ts` file shows how to handle this potential error gracefully.

## Bug Description

The `divide` function lacks error handling. If the user attempts to divide by zero, the function throws an error, potentially crashing the application.  This is undesirable behavior.

## Solution

The solution involves adding error handling to gracefully deal with division by zero.  This can involve returning a specific value (e.g., `NaN`, `Infinity`, or 0) or handling the exception using a `try-catch` block. The preferred solution depends on the specific requirements of the application.
