---
layout: page
title: OOPS Basics
---

## Procedural programming  
Before object-oriented programming, procedural programming was widely used in programming languages like C and Fortran.  

Procedural programming is based on a top-down approach to programming in which a bigger problem is broken down into smaller pieces and further divided into smaller problems.  

An example of a top-down approach:  
Let's say we have to create a calculator, and the calculator will have some basic functions like addition, subtraction, multiplication, and division.  

So, according to procedural programming, we create a calculator first as an overview and then redefine every method one by one.  

Algorith:
```
Step1. Create first method as overview:
        createCalculator(number1, number2, operator)
            {
                if operator == SUM 
                    add(number1, number2)

                if operator == MUL
                    mul(number1, number2)
            }

Step2. Defining Methods:
        add(number1, number2)
        {
            return (number1 + number2)
        }

Step3. Create further methods:...
```
Here, we created an overview method and created sub methods and so on. This is procedural programming.
