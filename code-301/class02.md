## State and Props

### React lifecycle

#### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’

> Render occurs first and then componentDidMount is called.

#### What is the very first thing to happen in the lifecycle of React?

> The first thing to happen in the React lifecycle is the mounting phase, which includes the following methods in this order: 1. constructor(), 2. static getDerivedStateFromProps(), 3. render(), 4. componentDidMount()

#### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

> Constructor: This is the first method that gets called when a component is created. It's used to set up the initial state and bind methods to the component instance.

> Render: This method is called after the constructor and every time the component's state or props change. It's used to render the component's UI.

> componentDidMount: This method is called immediately after the component is mounted in the DOM. It's used to fetch data, set up subscriptions, or do other one-time setup.

> React Updates: After the component has been mounted, it may receive new props or have its state updated. When this happens, React will update the component's UI by re-calling the render method.

> componentWillUnmount: This method is called just before the component is removed from the DOM. It's used to clean up any resources that the component has created, such as event listeners or timers.

#### What does componentDidMount do?

> componentDidMount is a lifecycle method in React that is called immediately after a component is mounted or inserted into the DOM (Document Object Model).
This method is often used to perform side effects such as fetching data from an API, setting up event listeners, or initializing a third-party library that requires access to the DOM.

### React State Vs Props

#### What types of things can you pass in the props?

> Primitive data types such as strings, numbers, booleans, and null, JavaScript objects and arrays, functions and methods, react elements and components, event handlers and callbacks.

#### What is the big difference between props and state?

> Props are used to pass data from a parent component down to a child component, while state is used to manage data within a component itself that can change over time.

> Props are read-only and cannot be changed by the child component, and they are defined when the component is first created. Props are typically used to customize or configure a component, or to pass data from a higher-level component down to a lower-level component.

> State is used to keep track of things like user input, form values, and the current state of a component or application.

#### When do we re-render our application?

> We re-render our application whenever there is a change in the component's state or props. When the state or props of a component changes, React automatically re-renders that component, along with any child components that depend on its data. This ensures that the user interface always reflects the latest data and state of the application.

#### What are some examples of things that we could store in state?

1. User input data, such as form data, that can change during the user's interaction with the application.

2. Application configuration settings that can be changed by the user, such as theme, language, or font size.

3. Data retrieved from APIs or other external sources that needs to be updated periodically or in response to user actions.

*Sources*
- [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

- [React Docs - handling events](https://reactjs.org/docs/handling-events.html)

- [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)

- [React Bootstrap Documentation](https://react-bootstrap.github.io/)

- [Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

- [Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)

- [Netlify](https://www.netlify.com/)

## Things I want to know more about,
