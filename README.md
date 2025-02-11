# Unexpected Null Return in Addition Function

This repository demonstrates a common JavaScript bug involving unexpected null returns in a simple addition function. The function `foo` is designed to add two numbers but incorrectly returns null if either input is null.  The solution corrects this behavior.

## Bug Description

The `foo` function returns null if *either* of its arguments is null.  The intended behavior is for it to return null *only if both* arguments are null.

## Solution

The solution modifies the conditional statement to explicitly check if *both* `a` and `b` are null before returning null.