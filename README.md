# Unexpected Type Coercion in JavaScript

This repository demonstrates a common JavaScript bug caused by loose typing and unexpected type coercion.

## The Bug

The `foo` function is intended to add two numbers. However, due to JavaScript's loose typing, when one of the arguments is a string, the `+` operator performs string concatenation instead of numerical addition.

## Solution

The solution involves explicitly converting the arguments to numbers using `parseInt()` or `Number()` before performing the addition.

## How to reproduce the bug:
1. Clone this repository
2. Run `node bug.js`