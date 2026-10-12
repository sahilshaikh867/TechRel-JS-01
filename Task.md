
# JavaScript Practical Task
## Topic: Variables & Operators

**Level:** Beginner  
**Duration:** 60–90 minutes  
**Language:** JavaScript  
**Prerequisites:** Basic JavaScript syntax and `console.log()`

### 🎯 Learning Objectives

By completing these tasks, students should be able to:

- Create variables using `let`, `const`, and `var`
- Store different types of values
- Perform arithmetic calculations
- Use assignment operators
- Compare values using comparison operators
- Use logical operators
- Combine variables and operators to solve simple problems

---

## 🟢 Part 1 — Variables Basics

### Task 1: Student Information

Create variables to store:

```javascript
studentName
age
course
college
```

Print the information using `console.log()`.

**Expected Output:**

```text
Name: Sahil
Age: 21
Course: Computer Engineering
College: ABC College
```

---

### Task 2: Change Student Age

Create a variable:

```javascript
let age = 20;
```

Increase the age by `1` and print the result.

**Expected Output:**

```text
Current Age: 21
```

**Hint:**

```javascript
age = age + 1;
```

---

### Task 3: Constants

Create a constant:

```javascript
const pi = 3.14;
```

Try to change its value.

```javascript
pi = 3.14159;
```

### Question

What happens?

**Think:** Why can't we change the value of a `const` variable?

---

# 🟢 Part 2 — Arithmetic Operators

Use:

```text
+
-
*
/
%
**
```

### Task 4: Basic Calculator

Create two variables:

```javascript
let num1 = 20;
let num2 = 5;
```

Perform:

1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Remainder
6. Power

**Expected Output:**

```text
Addition: 25
Subtraction: 15
Multiplication: 100
Division: 4
Remainder: 0
Power: 3200000
```

> Students should calculate the power using `num1 ** num2`.

---

# 🟡 Part 3 — Real-Life Calculations

### Task 5: Shopping Bill 🛒

You purchased:

```javascript
let shirt = 799;
let jeans = 1299;
let shoes = 1999;
```

Calculate:

- Total price
- 10% discount
- Final amount after discount

**Expected Output:**

```text
Total: ₹4097
Discount: ₹409.70
Final Amount: ₹3687.30
```

### Challenge

Add a variable:

```javascript
let gst = 18;
```

Calculate the final amount including GST.

---

## Task 6: Student Marks Calculator 🎓

Create variables:

```javascript
let math = 85;
let physics = 78;
let chemistry = 92;
```

Calculate:

1. Total marks
2. Average marks
3. Percentage

Assume each subject is out of 100.

**Expected Output:**

```text
Total Marks: 255
Average: 85
Percentage: 85%
```

---

# 🟡 Part 4 — Assignment Operators

Use:

```text
=
+=
-=
*=
/=
%=
```

### Task 7: Bank Account

Create:

```javascript
let balance = 10000;
```

Perform the following transactions:

```text
Deposit ₹5000
Withdraw ₹2000
Deposit ₹1500
```

Use assignment operators instead of writing:

```javascript
balance = balance + 5000;
```

Try:

```javascript
balance += 5000;
```

Finally print:

```text
Final Balance: ₹14500
```

---

# 🟡 Part 5 — Increment & Decrement

### Task 8: Counter

Create:

```javascript
let count = 0;
```

Perform:

```text
Increase count 5 times
Decrease count 2 times
```

Use:

```javascript
++
--
```

Print the final value.

**Expected Output:**

```text
Final Count: 3
```

---

# 🟠 Part 6 — Comparison Operators

Use:

```text
>
<
>=
<=
==
===
!=
!==
```

### Task 9: Age Verification

Create:

```javascript
let age = 20;
```

Check:

```text
Is age greater than 18?
Is age equal to 18?
Is age less than 18?
Is age greater than or equal to 18?
```

Print the results.

Example:

```text
Age > 18: true
Age == 18: false
Age < 18: false
Age >= 18: true
```

---

# 🟠 Part 7 — `==` vs `===`

### Task 10: Guess the Output 🤔

Ask students to predict the output **before running the code**.

```javascript
console.log(10 == "10");

console.log(10 === "10");

console.log(5 != "5");

console.log(5 !== "5");
```

### Questions

1. Which ones return `true`?
2. Which ones return `false`?
3. What is the difference between `==` and `===`?

---

# 🔴 Part 8 — Logical Operators

Use:

```text
&&
||
!
```

### Task 11: Driving Eligibility 🚗

Create:

```javascript
let age = 22;
let hasLicense = true;
```

Check whether the person can drive.

Condition:

```text
age >= 18 AND hasLicense must be true
```

Expected:

```text
Can Drive: true
```

Try changing:

```javascript
let age = 16;
```

What happens?

---

### Task 12: Login System 🔐

Create:

```javascript
let username = "admin";
let password = "12345";
```

Create another pair:

```javascript
let enteredUsername = "admin";
let enteredPassword = "12345";
```

Check whether login is successful.

Use:

```javascript
&&
===
```

Expected:

```text
Login Successful: true
```

Try changing the password.

---

# 🔥 Final Practical Challenge

## Task 13: Mini Student Result System

Create variables:

```javascript
let studentName = "Rahul";

let math = 78;
let physics = 82;
let chemistry = 75;
```

Your program should calculate:

### Step 1 — Total

```text
Total Marks
```

### Step 2 — Average

```text
Average Marks
```

### Step 3 — Percentage

```text
Percentage
```

### Step 4 — Result

Student passes if:

```text
Percentage >= 40
```

### Step 5 — Scholarship

Student gets a scholarship if:

```text
Percentage >= 85
```

### Expected Output

```text
========================
   STUDENT RESULT
========================

Name: Rahul

Math: 78
Physics: 82
Chemistry: 75

Total Marks: 235
Average: 78.33
Percentage: 78.33%

Pass: true
Scholarship: false
```

---

# ⭐ Bonus Challenge

Create a **Simple Calculator** using variables and operators.

```javascript
let num1 = 50;
let num2 = 10;
let operator = "+";
```

Your program should support:

```text
+
-
*
/
%
```

For example:

```text
50 + 10 = 60
```

Then change:

```javascript
operator = "*";
```

Output:

```text
50 * 10 = 500
```

**Bonus:** Try solving this without using `if-else` first; then later you'll improve it using conditional statements.

---

## 📝 Student Submission

Students should submit a `.js` file containing:

```text
Task 1
Task 2
Task 3
...
Task 13
Bonus Challenge
```

