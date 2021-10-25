1. Using loops take 10 inputs from user and find the average of all the numbers.

```js
let sum = 0 
for(let i=1 ; i <=10 ; i = i+1){
sum = +prompt("Enter a number") + sum;
}
let average = sum / 10
console.log(average)
```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
//'hi'
//'hi'
//'hi'
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getEvenSum (max=10){
  let sum = 0
  for(let i=1 ; i<=max ; i++){
    if(i % 2 == 0 ){
      sum = sum + i 
    }
  }
 return sum ;
  };
getEvenSum();
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
function getEvenSum (max=10){
  let sum = 0
  for(let i=1 ; i<=max ; i++){
    if(i % 2 !== 0 ){
      sum = sum + i 
    }
  }
 return sum ;
  };
getEvenSum();
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
```js
let num = 123;
let mul = 1
let last = num%  10;
num = Math.round(num / 10);
mul = mul * last
```

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // 'Bigger than 5'
check(1); // 'Smaller than 5'
check(5); // '5'
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'
getOutput('John'); // 'You are arya'
getOutput(); // 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // console output- 'You are arya' and return output- 'Who are you'
getOutput('John'); // console output- 'You are john' and return output- 'Who are you'
getOutput(); // 'Who are you'
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

```js
 yes,function have multiple return statements.but return only one outputfromthe function .if we have two return statement then we get output from one return only.
 example-
 function sum (a,b){
   return a+b;
   return a-b;
   return a*b;
 }
 sum(1,3)// 4 output is only from first return 
```

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
```js
'for'loop take 3 statement.first statement is used for initialization,second statement is condition in loop,and third statement expalin what to do after every itration.
example- for(let i=1 ; i<=10 ; i++)
console.log(i)

'while'loop take a condition and when condition is true it execute the body,when the condition is false the loop breaks.
example-
let i = 0
while(i<= 10){
  console.log(i)
}
```
