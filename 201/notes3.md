# Read-03 notes

## Chapter 3 notes from HTML

#### There are three kinds of lists in HTML
- Ordered lists
  - These lists are usually numbered to list off something based off of a tier system.
  - The tag for this is `<ol>`
- Unordered lists
  - These lists usually list off items that are all tied to significant group.
  - Tends to start with a bullet point.
  - The tag for this is `<ul>`
- Definition list
  - These consist of terms followed by a definition for each term (such as this list).
  - These consist of the tags `<d1>`, `<dt>`, and `<dd>`.
    - `<d1>` This usually houses a series of terms and definitions.
    - `<dt>` This is housed inside of a `<d1>` and houses the *term* being defined.
    - `<dd>` This is housed inside of a `<d1>` and houses the *definition*.

Lists can be nested within eachother.

## Chapter 13 notes from HTML

#### Each element 'box' can be changed in CSS to fit different proportions.

These tags with examples include:
- `height: 500px;`
- `width: 500px;`
- `border: 1em;`
- `padding: 2em;`

You can limit this size on responsive pages with:
- `min-width: 200px;`
- `max-width: 200px;`

Same concept as above can be applied with `height` instead of `width`.

If some content pours outside of the size of a box, you can decide to hide the overflow with:
- `overflow: hidden;`
Or, if you want to add a scoll bar to the box to view the content:
- `overflow: scroll;`

Each box has a **border**, then a **margin** and finally **padding** on the outtermost part. These sections can all be changed in CSS to have as much space as desired.

*inline* elements are elements that will only fill as much as they need, whereas *block* level elements attempt to fill up as much space on a page they can.

## Chapter 2 review from JS

#### javaScript is a programming language meant for front end web development which adds **functionality** to a webpage.

The functionality within javaSript includes, but is not limited to:
- Statements
  - Ability to do math and use user input to evaluate equations or problems
- Comments
  - Ability to write comments to describe *why* code is written a certain way
- Variables
  - Ability to store information which can be easily accessed anywhere in code
- Datatypes
  - Ability to store different *kinds* of information

Variables are created using *let* and *const*
- *let* allows an initiated variable to be latter changed in code
- *const* allows an initiated variable to stay the same throughout the program

Arrays are variables which store more than one value at a time. This is done using:
- `const arrayTest = ['1', '2', '3'];`

Arrays start at 0. This means that when you want to grab a piece of information from an array you have to count starting from 0. EX:
- `let itemOne = arrayTest[0];`
This would set the variable `itemOne` to the value of `1`.

## Chapter 4 review from JS

#### If else statements allow logical comparisons to be made and if the boolean `true` is equated, a code block is run, or if the boolean `false` is equated, the code block is skipped.

Switch statements can be used in place of if/else statements if they exceed 3 different else statements. Switch statements evaluate a variable and, depending on what value is stored in the variable, will output a specific answer which relates to the value. Switch statements always contain a `default` path at the end in case every condition is *not* met with the value in the variable.

falsey values are treated as *if* they are false, falsey values in JS include:
- false
- 0
- ' ' (an empty string)
- NaN (Not a Number)
- a variable with no value assigned to it

truthy values are the opposite, and they will be treated as *if* they were true, these include:
- true
- 1
- 'words' (strings with content)
- 5/10 (number calculations)
- 'true' (true written as a string)
- '0' (zero written as a string)
- 'false' (false written as a string)

Loops such as `for`, `while`, and `do while` are all functions of JS.

JS comparison operators include:
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

[<-- Back](ToC.md)