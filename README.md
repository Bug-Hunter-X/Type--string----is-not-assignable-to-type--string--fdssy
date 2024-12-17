# Type 'string[]' is not assignable to type 'string'
This TypeScript code demonstrates a common type error: assigning an array of strings to a parameter expecting a single string.  The function `greeter` expects a single string, but the code attempts to pass an array of strings.  The solution shows how to correctly handle this scenario, either by passing individual elements of the array or modifying the function signature to accept an array.