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

#### Comparison operators include:
* `==` -> Equal to (will not check typeOf)
* `!=` -> Not equal to
* `===` -> Strict equal to (WILL check typeOf)
* `!==` -> Strict not equal to
* `>` -> Greater than
* `>=` -> Greater than or equal to
* `<` -> Less than
* `<=` -> Less than or equal to

Logical Operators include:
* `&&` -> Logical and
* `||` -> Logical or
* `!` -> Logical not

## Loops and loop counters

#### Loops allow blocks of code to be ran a certain number of times. Loops check a condition, if the condition returns true, the code block will run until the condition returns false.

The three types of loops are **for**, **while**, and **do while**.

- For loops

If you need to run code a specific number of times, use a `for` loop

EX: `for (let i = 0; i <10; i++) {
    code block here
}`

The first parameter in a for loop Initializes a variable

The second parameter in a for loop sets the condition

The third parameter in a for loop updates the variable if the condition returns true.

- While loops

If it is uncertain how many times the code will run you should use the while loop.

EX: `while (i<10) {
    msg +=i + ' x 5 = ' + (i * 5) + '<br />';
    i++;
}`

- Do while loops

This is similar to the while loop, but should be noted that this will always run at least once, even if the condition is met with false.

EX: `do {
    code block;
    i++;
} while (i<1);`

[<-- Back](ToC.md)