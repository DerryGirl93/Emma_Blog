---
title: JavaScript Functions and Control Flow
description: Write up of Functions and Control Flow lesson and tasks
date: 2021-06-15
tags:
  - Coders Guild
layout: layouts/post.njk
---

<h3>About the Lesson</h3>

<h4>Declaring Functions</h4>
<p>
In this lesson we learned how to declare a function. A function is a piece of code that we can reuse elsewhere in our code by calling it.

We declare a function with the following syntax:

Function animalFacts(){
console.log('Spiders have eight legs')
}

To call the function in your code you would use the following syntax:
animalFacts();

</p>
<h4>Arguments & Returning Values</h4>
<p>
We can add arguments into functions as per the example below. This enables us to pass different values into the function so we can change the output of the function.

function callKitten(kittenName){
console.log('Come here, ' + kittenName + '!');
}
callKitten('Fluffy'); // outputs 'Come here, Fluffy!'
function addNumbers(a, b){
console.log(a + b);
}
addNumbers(5, 7); // outputs 12
addNumbers(9, 12); // outputs 21

We can also return a value using a function so we can use it later in our code. Example below:

function square(num) {
return num \* num;
}
console.log(square(4)); // outputs '16'
var squareOfFive = square(5); // squareOfFive equals
'25'

</p>

<h4>Control Flow - IF Statements</h4>
<p>
We use IF statements so we can run some code depending on what conditions are met. The syntax we use is:

if (condition) {
// statements
}

In IF statements we use comparison operators. See list below:

</p>
<table style="width: 50%;" border="1" cellpadding="5">
<tbody>
<tr>
<td>e.g</td>
<td>Name</td>
<td>Result</td>
</tr>
<tr>
<td>a == b</td>
<td>Equal</td>
<td>TRUE if a is equal to b (can be different types).</td>
</tr>
<tr>
<td>a === b</td>
<td>Identical</td>
<td>TRUE if a is equal to b, and the same type.</td>
</tr>
<tr>
<td>a != b</td>
<td>Not equal</td>
<td>TRUE if a is not equal to b (can be different types).</td>
</tr>
<tr>
<td>a !== b</td>
<td>Not identical</td>
<td>TRUE if a is not equal to b, or they are not the same type.</td>
</tr>
<tr>
<td>a < b</td>
<td>Less than</td>
<td>TRUE if a is strictly less than b.</td>
</tr>
<tr>
<td>a > b</td>
<td>Greater than</td>
<td>TRUE if a is strictly greater than b.</td>
</tr>
<tr>
<td>a <= b</td>
<td>Less than or equal to</td>
<td>TRUE if a is less than or equal to b</td>
</tr>
<tr>
<td>a >= b</td>
<td>Greater than or equal to</td>
<td>TRUE if a is greater than or equal to b.</td>
</tr>
</tbody>
</table>

<p>
We can use an ELSE statement at the end of our IF statement. This will tell the browser what to run if none of the conditions set out in the IF statement are met.

We can also use Logical Operators in our IF statements as per the below:

</p>
<table style="width: 50%;" border="1" cellpadding="5">
<tbody>
<tr>
<td>e.g</td>
<td>Name</td>
<td>Result</td>
</tr>
<tr>
<td>a && b </td>
<td>And</td>
<td>TRUE if both a and b are TRUE.</td>
</tr>
<tr>
<td>a || b</td>
<td>Or</td>
<td>TRUE if either a or b is TRUE.</td>
</tr>
<tr>
<td>!a</td>
<td>Not</td>
<td>TRUE if a is not TRUE.</td>
</tr>
</tbody>
</table>

<h3>Tasks</h3>
<h4>Task 1 </h4>
<p>
<em>This logs "Hello World" to the console</em>

function helloWorld(){
console.log("Hello World!")
}

helloWorld();

</p>

<h4>Task 2 </h4>
<p>
<em>This will log "Emma O'Deorain" to the console </em>

function printFullName(firstName, lastName){
console.log(firstName + " " + lastName)
}
printFullName("Emma", "ODeorain");

</p>

<h4>Task 3</h4>
<p>
<em>This will log a students full name to the console</em>

function printStudentName(firstName, lastName){
return firstName + lastName;
}
console.log(printStudentName("John ", "Doe"));

const nameOfStudent = printStudentName("Saoirse ", "Walker")

console.log(nameOfStudent);

<h4>Task 4</h4>
<p>
<em>This will log a statement to the console depending on what value is given in the temp variable</em>

const temp = 27;

if (temp <= 50 && temp > 30 ){
console.log("Wear a coat")
} else if (temp <= 30 && temp > 0){
console.log("Wear a coat & hat")
} else if (temp <= 0){
console.log("Stay inside")
} else {
console.log("just pants and vest is fine" )
}

</p>
