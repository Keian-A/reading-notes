# Read-01 notes

## Notes on [components](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

#### Component based architecture is essentially referring to breaking the code into smaller sections (or components) to split the larger problem into more easier to manage chunks.

The prime directive of using a component based architecture is for "component reusability." This refers to the "functionality and behaviors of a software element into a reusable and self-deployable binary unit."

What is a **component**?

A component is:
- A smaller piece of code that has "well-defined" functionality which can be used to export to a higher-level interface.
- A software object, made to interact with other components, with a specific or a set of functionalities.
- A unit of comparison with a contractually specified interface that can be deployed on its own.

A component can have 3 different views:
1. Object-oriented view
  - Where a component is viewed as a set of one or more cooperating classes. This involves defining the interfaces that allow classes to communicate and cooperate.
1. Conventional view
  - It is viewed as a module that can be used to integrate the processing logic, also has an interface that can be used to invoke or pass information to this.
1. Process-related view
  - Instead of creating a component from scratch, the system builds one from existing components in a library.

Components should have or be:
- Reusability
- Replacable
- Not context specific (works in different environments)
- Extensible
- Encapsulated
- Independent

Components should be well planned out first, with the design of data structures, interfaces, and algorithms pre-planned out to establish guidelines to avoid the introduction of errors.

Benefits of using components:
- Ease of deployment
- Reduced cost
- Ease of development
- Reusable
- Modification of technical complexity
- Reliability
- System maintenance and evolution
- Independant

## Notes on [props](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)

#### Also - more on [components](https://codeburst.io/react-js-understanding-functional-class-components-e65d723e909)

React is a component-based library which divides the UI into little reusable sections. In order to send information from and to components, you use props.

`props` is a special keyword in React which stands for `properties`. This keyword is used to pass data from one component to another.

`props` data is "read-only" which means that the data coming in cannot be modified directly from the child component.

Using `props`:
1. First, define an attribute and its data (value).
1. Then pass it to child components with `props`.
1. Finally, render the `props` data.

**Interpolation** is a way, in React, to define attributes and assign values.

``` JavaScript
// Base example
<ChildComponent someAttribute={value} anotherAttribute={value}/>

// With the chosen attribute, "text", and value, "I'm the 1st child"
<ChildComponent text={“I’m the 1st child”} />
```

To pass arguments as a React component:

``` JavaScript
const ChildComponent = (props) => {  
  return <p>I'm the 1st child!</p>; 
};
```

`props` is an object, so in order to call it you can use *string interpolation*:

``` JavaScript
{props}
```

[<-- Back](ToC.md)