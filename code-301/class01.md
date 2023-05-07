### Component-Based Architecture

#### What is a “component”?

> A "component" is a self-contained, reusable piece of code that defines a part of a user interface (UI) in a software application. In React, components are the building blocks of an application, and they can be combined to create more complex UIs.

#### What are the characteristics of a component?

> The characteristics of a component in React include:

 1. Encapsulation: Components are designed to be self-contained and do not affect the rest of the application.

 2. Reusability: Components can be reused throughout an application, which can save development time and effort.

 3. Extensible − A component can be extended from existing components to provide new behavior.

 4. Independence: Components are designed to be independent of each other and can be modified without affecting other components.

#### What are the advantages of using component-based architecture?

> The advantages of using a component-based architecture include:

 1. Reusability: Components can be reused throughout an application, which can save development time and effort.

 2. Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

 3. Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

 4. Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

*Source*

- [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

### What is Props and How to Use it in React
 
 > “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. Data with props are being passed in a uni-directional flow. (one way from parent to child)

#### What is “props” short for?

> Props" is short for "properties" and is a way to pass data from one component to another in React.

#### How are props used in React?

> Props are used in React by passing data from a parent component to a child component as a set of attributes. The child component can then use the data passed in through props to render its own UI or perform other operations.

#### What is the flow of props?

> The flow of props in React is unidirectional, meaning that props are passed from parent components down to child components, but not the other way around. This helps to maintain data consistency and makes it easier to reason about the state of an application. If a child component needs to pass data back to a parent component, it can do so using callbacks or other techniques.

*Source*

- [What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

*Bookmarked and Reviewed*

- [React Tutorial through ‘Passing Data Through Props’](https://reactjs.org/tutorial/tutorial.html)

- [React Docs - Hello world](https://reactjs.org/docs/hello-world.html)

- [React Docs - Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)

- [React Docs - Rendering elements](https://reactjs.org/docs/rendering-elements.html)

- [React Docs - Components and props](https://reactjs.org/docs/components-and-props.html)
