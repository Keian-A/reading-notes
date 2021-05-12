# Read-03 notes

## Notes on [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

#### In React, using curly braces, you can add collections of elements in JSX

``` JavaScript
// JavaScript
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);

// React component
ReactDOM.render(
  <ul>{listItems}</ul>,
  document.getElementById('root')
);
```

(All code examples taken from site directly)

This example shows the proper way to connect JSX to React components.

Keys should be added to elements to give them a stable identity. This can be as simple as adding the string variant of the number as the key:

``` JavaScript
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li key={number.toString()}>
    {number}
  </li>
);
```

The value is added between the tags inside the array, but the key is added to the opening tag such that an attribute would in HTML5.

Review the link to see correct key usage.

Keys have to be unique among siblings, but duplicate names can exist among different arrays.

## Notes on [Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

#### The spread operator is a "useful and quick syntax" for adding items to arrays.

The spread operator is written as three dots, or `...` before an array, ex:
- `...arr`

This expands an iterable object into the list of arguments it is composed of.

This can be useful for finding the largest item in an array:

``` JavaScript
Math.max(...[1,2,3])
// Returns 3, the largest value in the array
```

The spread operator can be useful for:
- Copying an array
- Concatenating or combining arrays
- Using math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

Concatenating two arrays with the spread operator can be brought together with a ,

EX:

``` JavaScript
const firstArr = [1,2,3]
const secondArr = ['a','b','c'];
const thirdArr = [...firstArr,...secondArr];
// console.log(thirdArr); = [1, 2, 3, 'a', 'b', 'c']
```

[<-- Back](ToC.md)