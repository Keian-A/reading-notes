# Read-09 notes

## Chapter 7 notes from HTML

#### HTML forms are used as a way to collect data from users of a page

Forms allow users to search through data, as well as perform other functions online

The different types of form controls:
- Text input
- Password input
- Text area
- Radio buttons
- Checkboxes
- Drop down boxes
- Submit buttons
- Image buttons
- File upload

All of these are used to collect data in different ways. For example the password input will star out the information inserted, and text area is like a short answer response box.

A form works by sending the name of each form control to a server, then the server processes the information using a specific language (this info can then be stored in the DB), and finally the server generates a new page based on the user input and sends the new page back to the user.

Form elements:
- `<form>`
  - Form controls live inside a `<form>` element. This element should always carry the `action=""` attribute and will usually have a `method=""` and `id=""` attribute
- `action=""`
  - This holds the URL for the location of the page on the server that the information will be sent
- `method=""`
  - Forms are sent with one of two methods, `get` or `post`. When you use the `get` method, the values from the form are added to the end of the URL specified in the `<action>` attribute, this can be useful with short forms (such as a search) or when you are just collecting data from a server, not sending information to be stored or deleted from a DB. The `post` method should be used when you are uploading a file, is very long, contains sensitive data (such as passwords) or adding information to or deleting from a DB.

## Chapter 14 notes from HTML

#### Lists, tables, and forms are all HTML properties that can work with specially created CSS properties such as:
1. `list-style-type`
  - This allows you to control the shape or style of a bullet point (AKA a marker)
1. `list-style-image`
  - This allows you to make an image act with a bullet point
1. `list-style-position`
  - This allows you to change whether the bullet points appear inside or outside the main box with the list item

And much [more](https://www.w3schools.com/css/css_list.asp)

## Chapter 6 notes from JS

#### Your browser is constantly registering different types of events

1. Interactions create events
1. Events trigger code
1. Code responds to users

Different event types (theres a lot):
- load
  - web page has finished loading
- unload
  - web page is unloading (usually if a new page is requested)
- error
  - browser encounters a JS error
- resize
  - browser window has been resized
- scroll
  - user has scrolled up or down the page

Keyboard events:
- keydown
  - user first presses a key (repeats while key is depressed)
- keyup
  - user releases a key
- keypress
  - character is being inserted (repeats while key iss depressed)

And much [more](https://www.w3schools.com/tags/ref_eventattributes.asp)

Flow matters if you have an event on the child of a parent element with an event
- Event bubbling
  - This is when the event starts at the most specific node and flows outwards to the least specific one
- Event capturing
  - This is when the event starts at the least specific node and moves towards the most specific one

[<-- Back](ToC.md)