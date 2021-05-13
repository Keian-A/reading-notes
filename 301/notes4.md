# Read-04 notes

## Notes on [forms](https://reactjs.org/docs/forms.html)

#### form is the html element used by the webpage to collect user input

EX from article:

``` JavaScript
<form>
  <label>
    Name:
    <input type="text" name="name" />
  </label>
  <input type="submit" value="Submit" />
</form>
```

Controlled components in React are updatable components that are updated with the `setState()` method in react, opposed to the traditionally HTML5 self-maintained states in `<input>`, `<textarea>`, and `<select>`.

Review page for example on using React's `this.state` to maintain the form information

In React, the tags are used in a different syntax with different information used and passed into them.

For example, HTML5 `<select>` tags are written as:
- `<select multiple={true} value={['B', 'C']}>` in React

## Notes on [ternary operator](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

#### The ternary operator is just another way of writing an if conditional statement in one line of code.

EX:

``` JavaScript
// This is the traditionally written if statement
if (person.age >= 16) {
  person.driver = 'Yes';
} else {
  person.driver = 'No';
}
// This is the same thing written using the ternary operator
person.driver = person.age >=16 ? 'Yes' : 'No';
```

Here the first value after the ternary operator is what the `person.driver` value is set to if the statement returns true, the second value for false.

Rewritten code for example:

``` JavaScript
console.log( x === y ? true : false );
```

[<-- Back](ToC.md)