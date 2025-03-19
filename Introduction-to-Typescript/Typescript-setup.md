# TypeScript Setup

To install Typescript we need npm (Node Package Manager). which comes bundled with Node Js.

You can verify whether you have nodejs installed by runnning the following command.

```js
node --version
```
if a version number is returned then you have node jhs.  You can also verify that npm is aavailable by running the following command.

```js
 npm --version
 ```
  if the command returns a version number then you have npm installed.

  If the npm is installe theen ypu can proceed and install tyescript globally

  ```ts
  npm install -g typescript
```

Verify that Typescript is installed by  by checking its version
```js
tsc -v
```

If the command returns aversion number, it means typescript is installed

To initialize Typescript in your project , navigate to your project directory and run

```js
tsc --init
```
or 
```ts
npx tsc --init
```

## Your first Typescript Code
with the above setup complete lets begin.

Inside your project directory create a file hello.ts with the following code:

```ts
let age:number=55;
console.log(age);
```
To execute the code above we need to convert it to javascript code first and then execute the generated javascript code.

Navigate to where file hello.ts lives and run the command below

```js
tsc hello.ts
```
This will generate hello.js with the following code

```js
var age=55;
console.log(age);
```
wde can the execute this javascript with node or view its output in the browser.
