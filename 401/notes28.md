# Read-28

- Why do we not need more .html pages in a multi-page React app?
  - We don't need more than one html file to load because React renders different content depending on current supplied data.
- If we wanted a component to show up on every page, where would we put it and why?
  - Inside the <BrowserRouter />, outside a <Route />. This will render the components that are caught without a specified route.
- What does routing do with the components that were rendered when a new route is requested?
  - re-renders the page with the new component, disregarding anything that existed before.
- What does props.children contain?
  - This is the data that is passed down the the child component to use from the parent component.
- How do useState() and this.setState() differ?
  - useState is a hook which allows state-setting in functional components, whereas this.setState is used in a class-based component.

## Define
- State Hook
  - This is a hook that allows you to set state in functional components using React.
- Mounting and Un-Mounting
  - Mounting is the part of the component lifestyle when a component renders on the page, and un-mounting is when React re-renders the page with other components.

[<-- Back](ToC.md)