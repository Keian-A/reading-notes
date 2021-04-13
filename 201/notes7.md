# Read-07 notes

## [Article](https://github.com/codefellows/domain_modeling#domain-modeling) notes

#### Domain modeling is the process of creating a conceptual model in code for a specific problem

An *object-oriented model* is an entity that stores properties and methods

When constructing a model for many types of *something* you want to use self-containing objects with the **same attributes and behaviors**

This will make small edits and changes way easier

When discussing and simulating user behavior it is best to use the `Math.random()` method, at least for now

## Chapter 6 from HTML

#### A table represents information in a grid format

Each block in the grid is referred to as a **table cell**

To create a table in HTML: 

(taken right from the book pg 132)

``` html
<table>
  <tr>
    <th></th>
    <th scope="col">Saturday</th>
    <th scope="col">Sunday</th>
  </tr>
  <tr>
    <th scope="row">Tickets sold:</th>
    <td>120</td>
    <td>135</td>
  </tr>
  <tr>
    <th scope="row">Total sales:</th>
    <td>$600</td>
    <td>$675</td>
  </tr>
</table>
```

There are things you can edit the appearance of this with such as:
- Spanning columns
- Spanning rows
- Long tables

## Chapter 3 review from JS

#### You can update an object by calling the `objectName.newProperty = newValue`

This will add the new property along with its new value next to it in the object when listed after

You can call properties and methods with `objectName.propertyName` for properties and `objectName.methodName()` for methods

You can use a function to create many new objects with the same template:

(this example pulled from page 108)

```javaScript
function Hotel(name, rooms, booked) {
  this.name = name;
  this.rooms = rooms;
  this.booked = booked;
  this.checkAvailability = function() {
    return this.rooms - this.booked;
  }
}
```

This automates the production of many objects of a specific type to hold similar information

[<-- Back](ToC.md)