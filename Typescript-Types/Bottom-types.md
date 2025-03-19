# Bottom Types
In TypeScript, a bottom type is a type that represents a value that never exists.

The only bottom type in TypeScript is never, which is a type that represents values that never occur.

The never type is used in situations where a value can never be observed.

This usually happens in:

1. Functions that never return (e.g., infinite loops and errors)

2. Exhaustive switch-case handling

3. Unreachable code.