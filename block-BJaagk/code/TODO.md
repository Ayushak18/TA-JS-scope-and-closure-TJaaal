1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function(marks,total){
  return (marks*100)/total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
function decalration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

function expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

function expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;

function expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

function definition is an expression in JS because function is a special kind of object and object is value thats why.

Example of function expression - 

let newfunction = function (a){
  return a;
}

4. Why is a function call an expression in JavaScript?

We know that expression is something that evaluate to a value and when we call a function it it also evaluated to a value that why we call function call an expression.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

// Valid - valid function defination

let five = add(2, 3); // Answer - Valid - we can store a function call into a variable 
five = add; // Answer Valid - we can store a function defination to a variable
five = five(10, 11); // Answer Valid we can store a function return value to variable
five = function () {
  return 'Hello';
}; // Answer Valid - it a valid function expression.
```

6. What is the difference between function definition and function call? Explain with an example.

When we define a function i.e. tell a what how function work it it called function defination
and when we call that function i.e execute the function it it called function call.

7. What is the similarities between function definition and function call?

both function and function call are expressions.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid - Valid - we are initializing a variable in a function with value Sam;
```

9. What is higher order function explain with an example.

<!-- Higher order functions are those functions which either accepts or returns a function. -->

10. Explain what is callback function. Why you can pass a function inside a function?

<!-- A call back function is that function whose function defination is passed an argument in a function 
function only accepts a value and function is an object which is basically a value so we can pass a fucntion as an argument
-->
