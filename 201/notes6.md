# Read-06 notes

## Chapter 3 notes from JS

#### An object is a group of variables and functions to create a modle of something you would recognize from the real world.

If a variable is part of an object, it is called a property

If a function is part of an object, it is called a method

It is possible to ammend information into a object by calling `objectName.newItem = newValue`

`this` is a keyword which refers the the current object you are in, this is useful if you need to call a previous value in a latter value

## Chapter 5 notes from JS

#### DOM is short for Document Object Model

This refers to the association of HTML and CSS within javaScript

You can essentially use JS code to insert elements on an HTML document, in turn using JavaScript to add content

You can view the DOM on a webpage through the dev tools, or download a DOM inspector tool

With the DOM you can write in elements through JS onto your HTML file

EX: `const targetedIdName = document.getElementById("targetedIdName");`
<!-- The newElementName can be `article` for example -->
then, `const newElementName = document.createElement('newElementName');`
<!-- This example only works if read as a group or alltogether, if you will -->
and finally, `targetedIdName.appendChild(newElementName);`

There are other methods available for use such as:
- getAttribute()
  - Gets the value of an attribute
- hasAttribute()
  - Checks if element node has a specified attribute
- setAttribute()
  - Sets the value of an attribute
- removeAttribute()
  - Removes an attribute from an element node
  
And plenty more, google is your friend.


[<-- Back](ToC.md)