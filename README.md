# JavaScript Practice – Variables & Basic Operations

This repository contains my basic JavaScript practice code.  
The main focus of these exercises is to understand:

- Variables
- Basic mathematical operations
- Average calculation
- Remainder calculation using modulo operator (`%`)

---

## 📘 Problem 1: Calculate Remaining Balance

**Task:**  
You have some money in your wallet. After buying apples and oranges, calculate how much money will remain.

**Code Snippet:**
```js
var myBalance = 1000;
var applePrice = 300;
var orangePrice = 400;

var totalPrice = applePrice + orangePrice;
console.log(myBalance - totalPrice);


## 📘 Problem 2: Calculate Average Marks

**Task:**
Add the marks of 5 subjects and calculate the average.
Then format the result using toFixed(2).

**Code Snippet:**
```
var math = 75.25;
var biology = 65;
var chemistry = 80;
var physics = 35.45;
var bangla = 99.5;

var totalMarks = math + biology + chemistry + physics + bangla;
var averageMarks = totalMarks / 5;
var averageMarksFixed = parseFloat(averageMarks.toFixed(2));
console.log(averageMarksFixed);


## 📘 Problem 3: Find Remainder

**Task:**
Divide a number by 5 and print the remainder.

**Code Snippet:**
```
var num = 119;
var remainder = num % 5;
console.log(remainder);

## 🛠 Technologies Used

JavaScript

Console output (Node.js or Browser Console)

### 📚 What I Learned

- How to store values using variables

- How to add, subtract and divide numbers

- How to calculate average values

- How to handle decimal formatting

- How to calculate remainder using % operator
