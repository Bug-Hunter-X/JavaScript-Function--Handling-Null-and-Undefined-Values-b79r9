# JavaScript Function: Handling Null and Undefined Values

This repository demonstrates a common JavaScript error related to handling null and undefined values in function parameters. The original code only explicitly checks for null values, resulting in incorrect behavior when undefined values are passed as arguments.

## Bug Description

The `foo` function attempts to add two numbers.  It correctly handles null values. However, if either parameter is undefined, the function will throw a TypeError because it attempts to perform arithmetic operation on undefined value.

## Solution

The solution improves the code by explicitly checking for both null and undefined values before attempting addition. This ensures the function behaves correctly regardless of whether the parameters are null, undefined, or numbers.