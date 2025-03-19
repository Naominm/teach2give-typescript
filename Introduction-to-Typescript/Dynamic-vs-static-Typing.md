# Dynamic VS. Static Typing
All major programming languages are either dynamically typed or statically typed.

Dynamically typed means that the type of variable can change at runtime.

In Dynamically typed languages the data types are determined  at runtime, meaning you do not need to explicitly declare variable types.

Examples of dynamically typed languages include Js, Python,Php etc.

Example in Javascript

```js
let x=5; //x is a number
x='Hello'; //x is now a string
console.log(x); // output: Hello. no errors
```

statically typed means that the type of variables cannot change once declared.

In Statically typed languages, data types are checked at compile time, meaning you must explicitly declare or infer variable types

Examples of such languages include TypeScript. Java C# swift etc.

Example in Typescript

```Ts
let x: number=5 //x is explicitly declared as a number
x="Hello" // Error: Tpe "Steing is not assignable to type number.
```
