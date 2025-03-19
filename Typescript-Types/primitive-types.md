# Primitive Types
Primitive types in Typescript are the most basic types that represent simple values and are immutable.

They include boolean , number , string, undefined, and null.

## Numbers
Numeric values; could be positive numbers, negative numbers,0,infinity,-infinity and floating point numbers.

Use the number keyword to define the number data types in Typescript:

```js
const myInteger: number = 5;
const negative: number = -48;
const myFloat: number = 56.835;
const zero: number = 0;
const infinity: number = Infinity;
const negativeInfinity: number = -Infinity;
```

## Strings
A string is  a collection of characters enclosed with double , single quotes or backticks.

Use string Keyword to define a string data type in Typescript.

```ts
const firstName: string = "John";
const lastName: string = "doe";
const emailAddress: string = `johdoe@gmail.com`;
const fullName: string = `${firstName} ${lastName}`;
```

# Booleans
Booleans can either be true or false

Use boolean keyword to define a boolean datatype in TS

```ts
const isMale: boolean = true;
const isFemale: boolean = false;
```
# null
Null is used when we want to explicitly define something that is empty or non existent.

null variables automatically get any data type, which means they can hold values of any data type.

```ts
let result = null;
result = true;
result = "john";
result = 25;
```
A simple fix for this would be to use the null data type as shown, and the variable will never accept any other data type:
```ts
let result:null = null;
```

## Undefined

Undefined is used as a placeholder to mean that a variable has been declared but has not yet been assigned a value but will have a value soon.
 
 Undefined has also its own keyword which is undefined;