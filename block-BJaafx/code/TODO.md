1. Using loops take 10 inputs from user and find the average of all the numbers.

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
hi
hi
hi
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum(max){
   for(var i=0;i<=max;i++){ 
   if(i%2==0){ 
   sum+=i;
   }
}


4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

function getEvenSum(max){
   for(var i=0;i<=max;i++){ 
   if(i%2 !==0){ 
   sum+=i;
   }
}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

function getProductOfDigits(num){
    if(num < 0) {
    return `not a valid input`;
    } else {
      return num.toString().split('').map(Number).filter(i => i).reduce((a, b) => a + b, 1);
    }
}

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

check(10); // bigger than 5
check(1); // smaller than 5
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya';
getOutput('John'); // 'You are john'
getOutput(); // 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.  JavaScript doesn't support functions that return multiple values. However, you can wrap multiple values into an array or an object and return the array or the object.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.   // one has 3 inputs, the other one needs one condition.
