# Read-10 notes

## Chapter 10 from JS

#### If you are receiving errors in your JS code, or its not working properly:
1. Check the dev tools console
  - If you use `'use strict';` at the beginning of your JS document, it is much easier to see where errors occur and on which line JS is running into an issue
1. Google is your friend
  - If there is a section you know you aren't writing correctly, you can always look it up on Google, chances are - someone had the same issue sometime in the past and it was resolved
1. It is important to keep in mind the flow of the program
  - JS runs top down, and wont go back in code unless you loop or call a function written on a previous line, this can lead to errors if you are calling a variable/function that hasnt been declared yet
1. If you get stuck, `console.log()`
  - Writing `console.log()` with different arguments for different sections of your JS program you can see exactly where something may not be running as intended

The stack:

This refers to the layers of functions that may be called. If you call a function within another function, the new function is ***pushed*** on the stack, and when it finishes, it is ***popped*** off the stack. The stack will pause the function underneath the one on the top of the stack, until the top is ***popped*** off the stack, then the *new* top function will resume.

Understand:
[X] Scope
[X] Error objects
[X] Browser dev tools
[X] JS console
[X] Logging data to console

All in all, I feel pretty comfortable **finding** the errors in my code, it just takes a bit longer **solving** them.

[<-- Back](ToC.md)