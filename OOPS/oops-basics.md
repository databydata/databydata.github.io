---
layout: page
title: OOPS Basics
---

## Programming Paradigms:
Ways to style or structure your code is called as programming paradigm.  

There are different ways:  
1. [Imperative Programming]()
2. [Declarative Programming]()
3. [Procedural Programming]()
4. [Functional Programming]()
5. [Object-Oriented Programming]()

### Imperative Programming
Imperative programming focuses on the 'HOW' part of programming, which means how the code will be processed by the computer.  

So if we say we have five items in an array and we have to double each item, the code will look something like this:
```
    function double(array)
    {
        const result = [];
        for(let i=0; i<array.length; i++)
        {
            array.push(2*array[i]);
        }
        return result;
    }
```
Here we are actually looping and generating result array. In simple terms, we are programming and thinking about how computers will do this operation.

### Declarative Programming 
In the declarative approach, we focus on the 'WHAT' aspect.  

In other words, we try to hide the complex logic and use imperative APIs to make the code simpler.  

Like in the above code, we actually looped over each element, but the declarative approach hides complex logic.  

```
    const squareRoot = numbers.map(num => 2*num);
```
Here we are using the map method to loop at every element.  

This is a declarative approach that internally uses imperative code but abstracts the complex logic. 
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
