 # Why We Need TypeScript
  Every programming language has its own problems Javascript has many of these, which can become problematic, especially in large-scale applications.

  Examples
  ### Javascript allows acessing properties which arent present in an object

  ```js
  const rectangle={width:300,height:400};
  const area=rectangle.width*rectangle.something;
  console.log(area);
  ```

  Most programming will not allow access of properties that does not exist in an Object.

  The code below will also work in Js
  ```js
  console.log(4/[]);
  ```

  ## Type Safety(Fewer Runtime Errors)

  Javascript is dynamically typed meaning type-related errors often appear at runtime. Typescript catches these errors at compile time, reducing bugs.

  The function below expects aa number but nothing prevents from passing a string.

  ```js
  function add (a,b){
    return a + b;
  }
  console.log(ad(5,"10")) //output 510 which is  a bug.
```
  ## Better Code Maintainability
  In large code bases Javascript dynamic nature makes it hard to understand what a function expects or returns.

  For example, In Js below its not clear whether the function is adding numbers or strings or even arrays; we just assume that it is adding two numbers

  ```js
  function add(){
    return a + b;
  }
  ```
   ## Enhanced IDE Support and AUtoCompletion
   with TypeScript , editors like vs code provide:

   -Autocompletion and intelliSense

   - Error Checking as you type

   - Quick refactoring and navigation. This Boosts developer productivity compared to Javascript.

   # Scalability for Large Applications
   Javascript works well for small projects, but as application grow, it become harder to manage.

   -No type enforcement
   
   - Developer struggle to understand Data Structures. Typescript enforces in the code, making collaboration and scaling easier.

## Easier Refactoring and Debugging

Renaming variables, moving functions and restructuring code is safer in Typescript because compiler ensures consistency.

-In Javascript, renaming a function might break parts of your code.

In typescript, the compiler warns you about all affected places.

## Popularity and Industry Adoption
Major companies (Google, Microsoft, Airbnb etc) use Typescript for large projects.

- used in frameworks like Angular NestJS, Next.JS etc

- Adopted in backend (NodeJS) & frontend (React, Vue, Angular).







