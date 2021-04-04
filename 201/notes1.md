# Pre-day 1 class notes

#### Ways JS can make a website more interactive:
1. The ability to access content.
    * You can use JS to access text from an HTML page.
    * EX: You can select all h1 text.
    * EX: You can select any elements that have a *class* attribute with a value of *note*.
1. The ability to modify content.
    * You can use JS to add elements, attributes, and ntext to a page, or remove them.
1. The ability to program rules.
    * You can specify a set of steps for the browser to follow which can make changes to a webpage.
1. React to events
    * You can specify that a script should run when a specific event is achieved.

Things you can do with JS in the browser:
* Slideshows
* Forms
* Reload parts of a page
* Filtering data

### A script is a series of instructions
#### To write a script, you must first state your goal then write a list of tasks that need to be achieved to accomplish it.

1. Define the goal
1. Design the script
1. Code each step

When a script is ran, it might only use a subset of the rules specified.

## Expressions & Operators

#### An expression is something that results in a single value.

The two types of expressions are:
* Expressions that assign a value to a variable
* Expressions that use two or more values to return a single value.

Operators allow programmers to create a single value from one or more values.
* EX: `=`, `+`, `-`, `>`, `<`, etc.

Arithmetic operators:
* ++ -> Adds one number to the current value.
* -- -> Subtracts one number from the current value.
* % -> The *modulus* divides two values and returns the remainder.
* There is also `+`, `-`, `/`, and `*`

**Concatenation** is when you add two or more strings together to create a new string.

## Functions

#### Functions are lines of code you can save to one location and run throughout a program by *calling* it. They usually have the intention of returning a value to the line where the function was originally called, once complete.

By **calling** a function, you are asking the program to run a specific line or lines of code.

**Parameters** are pieces of information sent to a function.

The **return value** is the information sent back to the line which originally called the function, by the function called.

To declare a function:
`function functionNameHere(parameters, here) {
    document.write('Hello');
}`

To call a function:
`functionNameHere(arguments, here);`

To save information returned from a function, set the function equal to a new variable. The variable's value will be the return value of the function.

[<-- Back](ToC.md)