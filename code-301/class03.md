## Passing Functions as Props

### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

#### What does .map() return?

> The .map() method is a function in JavaScript that operates on an array and returns a new array with the same number of items. It applies a callback function to each element of the original array and uses the return value of the callback function to create the corresponding element of the new array. 

#### If I want to loop through an array and display each value in JSX, how do I do that in React?

> Use the .map() method along with JSX to create a new array of React elements. 

#### Each list item needs a unique ____.

> Each list item in React needs a unique "key" prop. 

#### What is the purpose of a key?

> The purpose of a "key" prop in React is to help React efficiently update the user interface when the data changes. When a list of items is rendered in React, React uses the "key" prop to keep track of which items have been added, removed, or modified. 

### [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

#### What is the spread operator?

> The spread operator is a syntax in JavaScript that allows an iterable such as an array or an object expression to be expanded or "spread" into multiple elements. It is used with three consecutive dots ....

#### List 4 things that the spread operator can do.

> Copying an array, concatenating or combining arrays, using Math functions, using an array as arguments

#### Give an example of using the spread operator to combine two arrays.

> ` const arr1 = [1, 2, 3];`
`const arr2 = [4, 5, 6];`
`const combined = [...arr1, ...arr2];`

#### Give an example of using the spread operator to add a new item to an array.

> `const oldArr = [1, 2, 3];`
`const newItem = 4;`
`const newArr = [...oldArr, newItem];`

#### Give an example of using the spread operator to combine two objects into one.

> `const person = { name: 'John', age: 30 };`
`const address = { street: '123 Main St', city: 'Anytown', state: 'CA' };`
`const contactInfo = { ...person, ...address };`

### [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

#### In the video, what is the first step that the developer does to pass functions between components?

#### In your own words, what does the increment function do?

#### How can you pass a method from a parent component into a child component?

#### How does the child component invoke a method that was passed to it from a parent component?

*Sources*
- [React Tutorial through ‘Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html)

- [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)
