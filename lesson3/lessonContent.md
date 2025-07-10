# Functions in C++

## Overview

This lesson covers the concept of functions in C++, which is one of the main building blocks of a program.

## Learning Objectives

- Understand what a function is
- Write user defined functions
- Use built-in functions
- Understand recursion

## Topics Covered

- functions
- recursion

## Status

complete

## Assignment

Implement Functions in C++

### Objective

Apply your knowledge of functions to implement and use them in a simple C++ program.

### Expected Capabilities

- Define and call functions
- Use parameters and return values
- Write a functional C++ program utilizing functions

### Instructions

#### Part 1

**Define a function**

Write a function in C++ that computes the sum of two integers and returns the result.

```
int add(int a, int b) { return a + b; }
```

**Call the function**

Use the previously defined function in a C++ program to compute the sum of two numbers provided by the user.

```
int main() { int result = add(5, 7); cout << "Sum: " << result; return 0; }
```

### Tasks

#### Task 1: Write a program using functions

Create a C++ program that defines and uses at least two functions.

```
N/A
```

### Submission Instructions

Submit the .cpp file containing your program and a screenshot of the program output.

### Checklist

- [ ] Function defined and used
- [ ] Void and non-void functions implemented
- [ ] Program compiles and runs
- [ ] Output verified

### Check for Understanding

**What does a function return type signify?**

- Type of parameters it accepts
- Type of value it returns to the caller
- Type of arguments it processes

**Answer:** Type of value it returns to the caller

**Can a void function use return statements?**

- Yes, to return specific values
- No, it cannot contain return statements
- Yes, but only to exit the function early

**Answer:** Yes, but only to exit the function early

**How do you call a function in C++?**

- Define it again
- Use its name followed by parentheses
- Invoke run() method

**Answer:** Use its name followed by parentheses

## Subsections

### Introduction to Functions in C++

Functions are fundamental building blocks in C++. They allow you to break down complex problems into smaller, manageable tasks. Each function performs a specific task, enhancing code clarity and reusability.

**Video URL:** http://video.com/introToFunctions

**Code Examples:**

```
void myFunction() { // Code to execute }
```

**External Links:**

- [https://www.learncpp.com/cpp-tutorial/introduction-to-functions/](https://www.learncpp.com/cpp-tutorial/introduction-to-functions/)

**Quizzes:**

**What is the primary purpose of using functions in programming?**

- Enhance code performance
- Break down tasks for clarity and reusability
- Conditionally execute blocks of code

**Answer:** Break down tasks for clarity and reusability

### Defining and Calling Functions

Learn how to define a function in C++ using the correct syntax and call it within your programs. A function definition includes the function return type, name, and parameters, if any.

**Video URL:** http://video.com/definingFunctions

**Code Examples:**

```
int add(int a, int b) { return a + b; }
```

**External Links:**

- [https://www.tutorialspoint.com/cplusplus/cpp_functions.htm](https://www.tutorialspoint.com/cplusplus/cpp_functions.htm)

**Quizzes:**

**What is needed to define a function in C++?**

- Return type, function name, body
- Function name and body only
- Return type and body only

**Answer:** Return type, function name, body

### Function Parameters and Arguments

Parameters are placeholders in a function definition that accept inputs called arguments during function calls. Understand the difference between pass-by-value and pass-by-reference.

**Video URL:** http://video.com/functionParameters

**Code Examples:**

```
void printSum(int a, int b) { cout << a + b; }
```

**External Links:**

- [https://www.geeksforgeeks.org/functions-in-c/](https://www.geeksforgeeks.org/functions-in-c/)

**Quizzes:**

**What is the difference between pass-by-value and pass-by-reference?**

- Pass-by-value copies the argument, pass-by-reference uses the same memory address
- Both use the same memory address
- Pass-by-reference copies the argument, pass-by-value uses the same memory address

**Answer:** Pass-by-value copies the argument, pass-by-reference uses the same memory address

### Return Values and Void Functions

Discover how functions can return values to the caller using the return statement. Also, explore void functions, which perform tasks but do not return a value.

**Video URL:** http://video.com/returnAndVoidFunctions

**Code Examples:**

```
int square(int num) { return num * num; } // Function with return value
```

```
void printMessage() { cout << "Hello!"; } // Void function
```

**External Links:**

- [https://www.javatpoint.com/cpp-functions](https://www.javatpoint.com/cpp-functions)

**Quizzes:**

**What does a void function do?**

- Returns a value
- Does nothing
- Performs a task without returning a value

**Answer:** Performs a task without returning a value

## Supplemental Videos

- [http://video.com/advancedCppFunctions](http://video.com/advancedCppFunctions)

## References

- [https://www.learncpp.com/cpp-tutorial/introduction-to-functions/](https://www.learncpp.com/cpp-tutorial/introduction-to-functions/)

## Podcast URL

No podcast available