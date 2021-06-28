---
title: Introduction to JavaScript
description:
date: 2021-06-04
tags:
  - Coders Guild
layout: layouts/post.njk
---

<h3> About the Lesson</h3>

<p>Today we learned basic JavaScript programming concepts and how we can use it to make our web pages dynamic. We learned how to write basic JavaScript statements, log JavaScript to the console, and how to write a comment in JavaScript. We also learned how to declare a variable. We can use var, const or let to declare a variable. We also covered data types in JavaScript. These are string, number, boolean, undefined & null. When using the number data type we can use Arithmetic Operators. These are Subtract - , Add + , Multiply * , Divide / and Modulus % </p>

<h3>Task</h3>
<p>The task was to workout what the total bill would be based on adding a tip percentage to the final food bill. Below is my solution coded using JavaScript. This would print out a sentance on the web page saying "The final bill is £60.50 which includes a tip of £5.50".</p>

<p>
let preTipTotal = 55;

let percentage = 10;

let tipAmount = (percentage / 100) \* preTipTotal;

let finalBill= preTipTotal + tipAmount;

let finalBillToDecimals = finalBill.toFixed(2);

let tipAmountToDecimals = tipAmount.toFixed(2);

document.write(`The final bill is £${finalBillToDecimals} which includes a tip of £${tipAmountInDecimals}`); </p>
