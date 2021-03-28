# Loops / Comparison & logical operators

## Day 4 Class 2 notes

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

[<-- Back](README.md)