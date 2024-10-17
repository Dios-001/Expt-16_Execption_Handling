# EXP-16: Exception Handling in C++
# Algorithms

## Division Error Handling

### Algorithm

1. **Start.**  
2. **Declare Variables:**  
   - Declare three variables: `n1`, `n2`, and `ans` (float type).  
3. **Input Values:**  
   - Prompt the user to enter values for `n1` and `n2`.  
   - Read the input values of `n1` and `n2`.  
4. **Try Block:**  
   - Check if `n2` is equal to 0.  
     - If `n2 == 0`, throw the value of `n2` (0).  
     - Otherwise, calculate `ans = n1 / n2`.  
     - Display the result: "Answer = `ans`".  
5. **Catch Block:**  
   - If an exception occurs, catch the thrown value `num`.  
   - Display the error message: "ERROR: Division by `num`".  
6. **End.**

---

## Voter Age Error Handling

### Algorithm

1. **Start.**  
2. **Declare Variable:**  
   - Declare an integer variable: `age`.  
3. **Input Age:**  
   - Prompt the user to enter their age.  
   - Read the input value of `age`.  
4. **Try Block:**  
   - Check if `age` is less than 18.  
     - If `age < 18`, throw the value of `age`.  
     - Otherwise, print "You are eligible to vote".  
5. **Catch Block:**  
   - If an exception occurs, catch the thrown value `num`.  
   - Display the error message: "ERROR: required age: 18, your age: `num`".  
6. **End.**


## Overview

This project demonstrates how **exception handling** works in C++ through a simple division program. It prompts the user to enter two numbers and safely handles the case of division by zero using `try-catch` blocks.

## Features

- **Input Handling:** Takes two floating-point numbers from the user.
- **Exception Handling:** Throws an exception if the second number (denominator) is zero.
- **Friendly Error Messages:** Displays a specific error message when a division by zero occurs.

## Code

The core logic of the program is implemented in [`division.cpp`]
