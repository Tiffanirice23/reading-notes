##  React and Forms

### [React Docs - Forms](https://reactjs.org/docs/forms.html)

#### What is a ‘Controlled Component’?

> A controlled component is typically designed to have a well-defined interface and a clear set of expected behaviors. This allows other components of the system to interact with it in a predictable and reliable way. They are often used in complex systems where there are many interacting parts, such as in distributed systems or large-scale web applications. Controlled components are often used in complex systems where there are many interacting parts, such as in distributed systems or large-scale web applications.

#### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

> Waiting until the user submits the form can be more efficient and help ensure data integrity. If the user's responses are critical and must be validated or processed in a specific order, updating the state with each change could result in inconsistent or invalid data.

#### How do we target what the user is entering if we have an event handler on an input field?

> To target what the user is entering in an input field when we have an event handler on that field, we can access the value of the input field using the event.target.value property within the event handler.

### [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

#### Why would we use a ternary operator?

> We use a ternary operator to write shorter and more concise conditional statements. The ternary operator is represented by the ? and : symbols with the following syntax `condition ? expression1 : expression2;`
The ternary operator takes three operands: a condition, an expression to evaluate if the condition is true, and an expression to evaluate if the condition is false.

#### Rewrite the following statement using a ternary statement:

> if(x===y){
  console.log(true);
} else {
  console.log(false);
}

> `console.log(x === y ? true : false);` or, further simplified `console.log(x === y);`

*Sources*

- [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)

- [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)
