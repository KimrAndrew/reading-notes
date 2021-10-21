So far I've come across three main ways to create a function in JavaScript
  1. Function Declarations
  2. Function Expressions
  3. Arrow Functions
  
To create a function using a function declaration we use the `function` keyword followed by the function's name, parameters, then the code block containing the statements to be run
```js
//prints the sum of two numbers
function printSum(num1,num2) {
  console.log(num1 + num2);
}
```
A notable feature of function declarations is that functions created in this manner make use of function hoisting - allowing functions to be invoked before being declared in your code.

using the function from earlier as an example:
```js
printSum(1,3); //prints 4

//prints the sum of two numbers
function printSum(num1,num2) {
  console.log(num1 + num2);
}
```
Since the function is created using a function declaration, it is able to be called before it is declared in the code.
