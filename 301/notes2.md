# Read-02 notes

## Notes on [article](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

#### When you write components with either classes or functions in React, the methods you are able to utilize are called lifecycle events. These allow you to update the UI at any point during the lifecycle of the component runtime.

The three stages of the components lifecycle are:
- Mounting
  - This is when the component instance is created and the code is being inserted into the DOM. The code that is run for this part is: "Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount" (taken from [here](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093))
- Updating
  - Anytime a component updates or has the state change then rerenders. The code that is run for this part is: "static getDerivedStateFromProps, shouldComponentUpdate, render,
  getSnapshotBeforeUpdate, componentDidUpdate, UNSAFE_componentWillUpdate UNSAFE_componentWillReceiveProps" (taken from the link above)
- Unmounting
  - "componentWillUnmount" is the only lifecycle event during this phase, and refers to when components are removed from the DOM.

"The constructor for a React component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined." (quote taken directly from the article).

The method `static getDerivedStateFromProps()` exists for rare cases when the state relies on props changing over time.

`render()` is the only required method in the component's class.

The correct way to call in a piece of JS code for rendering:

``` JavaScript
<FishTable fishes={fishData}/>,
document.getElementById('app');
```

Code example taken from article

What types of things can you pass in the props?
  - `props` can be thought of as arguments being passed into a function. Initial values that you change or edit through the component's class or function.
What is the big difference between props and state?
  - `props` you pass into the component. Whereas `state` occurs within the component.
When do we re-render our application?
  - When you change the state of something in a component.
What are some examples of things that we could store in state?
  - State is for when you need to re-render and update something based on user input.

[<-- Back](ToC.md)