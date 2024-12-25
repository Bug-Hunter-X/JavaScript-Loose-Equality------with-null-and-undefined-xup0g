# JavaScript Loose Equality with null and undefined

This repository demonstrates a common JavaScript bug related to the loose equality operator (==) when comparing null and undefined values.

## The Problem

JavaScript's loose equality (==) performs type coercion before comparison, leading to unexpected results when dealing with null and undefined. In the provided code, while both null and undefined are falsy, they don't behave identically with loose equality and arithmetic operations.

## The Solution

To avoid this issue, it's best practice to use the strict equality operator (===) for comparisons when dealing with null and undefined. This ensures that no type coercion happens and that the comparison is more predictable and less error-prone.