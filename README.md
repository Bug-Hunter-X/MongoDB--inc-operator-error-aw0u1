# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numeric field by a specified value. However, if the field is not a number, or if the increment value is not a number, the operation will fail.

## Bug
The `bug.js` file contains code that incorrectly uses the `$inc` operator. The increment value is provided as a string, which results in an error.

## Solution
The `bugSolution.js` file provides the correct usage of the `$inc` operator. The increment value is given as a number, resolving the issue.

## How to reproduce
1. Clone this repository.
2. Run `bug.js` to see the error.
3. Run `bugSolution.js` to see the correct usage.
