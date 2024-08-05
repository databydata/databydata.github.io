---
layout: page
title: Structure Of Class
---

Here we will discuss the basic structure a class which will setup the initial pace of our discussion.  

Classes in abap are created into two parts.  
First we provide a definition and then we provide an implementation.

```
    CLASS NAME DEFINITION.
        PUBLIC SECTION.
        PROTECTED SECTION.
        PRIVATE SECTION.
    ENDCLASS.

    CLASS NAME IMPLEMENTATION.

    ENDCLASS.
```

A class is consist of attributes and methods.  

Let's stick to our example of 'Class Car'. A car consists of certain qualities such as it's color, brand, model etc and it can perform certain actions like it can start, drive, play music etc.

So, here all the qualities are its attributes and each action is its methods. It looks like this

```
    CLASS car DEFINITION.

        PUBLIC SECTION.

            DATA: color TYPE string,
                  brand TYPE string,
                  model TYPE string.

            METHODS: start,
                     drive,
                     playMusic.
    ENDCLASS.

    CLASS car IMPLEMENTATION.

        METHOD start.
            "Logic to start car
        ENDMETHOD.

        METHOD drive.
            "Logic to drive car
        ENDMETHOD.

        METHOD playMusic.
            "Logic to play music
        ENDMETHOD.

    ENDCLASS.
```

Here we have created a basic class, but there are certain principles that must be followed to create a class. In the following sections, we will break down each part and discuss it in detail.

> [Next Section >](oops-principles.md)
