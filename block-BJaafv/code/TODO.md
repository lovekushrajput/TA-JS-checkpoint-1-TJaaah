1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
// We use return keyword to get the output from the function

// second
function sum(a, b) {
  console.log(a + b);
}
// console.log is used to  display any type of message in the browser.
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.?
// value of `first` is 17.
// value of `second` is 16.


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
// output- 36
because we use only two argument and we passing two value so the two valau is add .

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
// yes . because in `sum` function there is return statement if any function have return statement .we call the function folowed by () and then we cam store it any any variable .


5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js
function sayHello(name){
  return name;
}
sayHello("Hello Arya")
```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
// output- "Hello John"
reason-  username is taken from outer variable because  variable defined outside can be accessed inside but variable define inside cannot be accessed outside.


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // "John"

showMessage(); // "Hello John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
when there is no name to function is known as Anonymous function.
 // example-1
 let addNUmber = function(num1 , num2){
   return num1 + num2
 }
 // example-2
let subNUmber = function(num1 , num2){
   return num1 - num2
 }
 // example-3
 let multipleNumber = function(num1 , num2){
   return num1 * num2
 }

9. Can function declaration be a Anonymous Function? Explain
yes.  function declaration be Anonymous Function because in declaration function is starting with keyword function.
 // example-
let subNUmber = function(num1 , num2){
   return num1 - num2
 }

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
function convertToNumber(){}
function getNumber(){}
function calAge(){}
function findName(){}
function calSalary(){}
