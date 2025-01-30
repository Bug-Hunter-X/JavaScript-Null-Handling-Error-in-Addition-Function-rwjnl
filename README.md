# JavaScript Null Handling Bug

This repository demonstrates a common error in JavaScript related to null or undefined values in function arguments. The `foo` function attempts to add two numbers but doesn't handle the case where either input is `null`. This can lead to unexpected behavior in applications. The solution demonstrates how to handle this situation effectively.

## Bug Description:

The provided `foo` function returns `null` if either of its input arguments is `null`. This is often undesirable.  A more robust solution would handle the `null` values explicitly, perhaps by treating them as 0 or throwing an error.

## Solution:

The solution file (`bugSolution.js`) provides an improved version of `foo` that handles null values correctly by replacing them with 0 before performing the addition.