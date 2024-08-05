---
layout: page
title: Programming Paradigm
---

Programming paradigms are ways to style or structure your code.  

There are different ways:  
1. [Imperative Programming](#imperative-programming)
2. [Declarative Programming](#declarative-programming)
3. [Procedural Programming](#procedural-programming)
4. [Functional Programming](#funational-programming)
5. [Object-Oriented Programming]()

### Imperative Programming
Imperative programming focuses on the 'HOW' part of programming, which means how the code will be processed by the computer.  

So if we say we have five items in an array and we have to double each item, the code will look something like this:
```
    #pseudo-code: 

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
    const square = numbers.map(num => 2*num);
```
Here we are using the map method to loop at every element.  

This is a declarative approach that internally uses imperative code but abstracts the complex logic. 

### Procedural programming  
In procedural programming, we still follow the imperative approach but use functions or methods to modularize the code.  

Procedural programming is widely used in programming languages like C and Fortran.  

Procedural programming is based on a top-down approach to programming in which a bigger problem is broken down into smaller pieces and further divided into smaller problems.  

For example, you have a car showroom, and you want to display the properties of each car based on its color and brand.  

One is imperative way
```
    #pseudo-code: 
    
    //Car 1
    Print ('Car is white')
    Print ('Brand Tyota')

    //Car 2
    Print ('Car is balck')
    Print ('Brand Volkswagen')

    //Car 3
    Print ('Car is white')
    Print ('Brand Kia')

    ...so on

```
Instead of this we create functions and pass values to print the data.

```
    #pseudo-code: 
    
    function printColor(color)
    {
        Print ('Car is ', color)
    }

    function printBrand(brand)
    {
        print ('Brand', brand)
    }

    //Car 1
    printColor(white)
    printBrand(Tyota)

    //Car 2
    printColor(Balck)
    printBrand(Volkswagen)
```

Here we have eleminated repetative code and created functions.  

### Funational Programming
Functional programming is based on a declarative approach where we try to create functions that are pure and follow strict control flow.  

Pure functions are functions that produce no side effects.  

A side effect is when we mutate values outside the scope, meaning if the functional is causing any effect other than reading its arguments and returning values, it is said to have side effects.  

For example, we are fetching color and brand of car via API based on key
```
    #pseudo-code: 
    
    function printColor(key)
    {
        var color = APIForColor('LINK',Key)
        Print ('Car is ', color)
    }

    function printBrand(key)
    {
        var brand = APIForColor('LINK',Key)
        Print ('Car is ', brand)
    }

    //Car 1
    printColor(car1)
    printBrand(car1)

    //Car 2
    printColor(car2)
    printBrand(car2)
```

Here functions are not as pure because they are causing some side effects.  

Side effects are not bad but, unexpected side effects should be avoided as they may lead to unwanted bugs.

Unexpected side effects mean, lets say you make an HTTP request in sum of two numbers function, so this should be avoided.  

### Object-Oriented Programming
Taking the example of a car showroom again, now you have a larger number of cars, and you also want to display all the features of cars instead of just color and brand.  

Going with the procedural way and calling methods again and aging will become hard to manage so we need to seperate code for each car somehow.  

Here OOPS comes into picture.  

With OOPS, we can create a blueprint of methods and attributes that will help us manage all cars.  

In OOPS terms, we call this blueprint 'Class,' and for every class we create objects.  

Objects are noting but instances of a class, so in our example we have a blueprint called 'Class Car' and each car will be an object.

```
    Class Car()
    {

        function printColor(color)
        {
            Print ('Car is ', color)
        }

        function printBrand(brand)
        {
            print ('Brand', brand)
        }

        function printEngine(engine)
        {
            print ('Engine', engine)
        }

        function printTyreBrand(tyre)
        {
            print ('Tyre', tyre)
        }
    }

    car1 = new Car();
    car1.printColor('White');
    car1.printBrand('Tyota');
    car1.printEngine('Petrol');
    car1.printTyreBrand('MRF');
```

Here we have depicted a very basic class which looks like procedural code above but in further sections we will present more features of oops which will clarify the reason of its most widely used programming paradigm.

In further sections we will discuss on further concepts of oops and how memory block is allocated for each object.  

> [Next Section >](oops-basics.md)
