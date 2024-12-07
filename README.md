# Type Error in TypeScript: Passing Array to String Function

This repository demonstrates a common type error in TypeScript that occurs when passing an array to a function that expects a string argument. The example shows how to identify and fix the issue. 

## Bug Description
The function `greeter` expects a string argument but is given an array. This results in a type error. The solution involves checking the type of the input and handling arrays accordingly.

## Solution
The solution checks if the input is a string or an array. If it's an array, it joins the elements into a single string before passing it to the function. This fixes the type error and allows the code to run correctly.