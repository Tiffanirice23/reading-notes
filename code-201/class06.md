## Problem Domain, Objects, and the DOM

### JavaScript Object Basics

#### How would you describe an object to a non-technical friend you grew up with?
> An object is a way of oragnizing information in a effecient way. Think of a backpack with zippers, pockets, and straps where each part has a specific purpose. In short, an object is like a container that holds related information and actions that make it easy to work with and manipulate that information.

#### What are some advantages to creating object literals?
1. Concise Syntax: Object literals allow you to create objects using a concise syntax, making it easy to create and initialize an object in a single step. 

2. Readability: Object literals can make your code more readable by making it clear what properties are associated with an object.

3. Flexibility: Object literals allow you to define an object with any number of properties, making it a flexible tool for creating complex data structures.

4. Cloning: Object literals can be used as a quick and easy way to clone an object, providing a convenient shorthand for copying an object's properties.

5. Privacy: Object literals can be used to create private properties and methods by encapsulating them within the object, providing a way to hide implementation details from the rest of the code.

#### How do objects differ from arrays?
> An array is an ordered collection of values that can be of any data type. The values in an array are accessed using numeric indices, starting from zero. Arrays are often used when you need to store a list of items or a sequence of values.

> An object is an unordered collection of key-value pairs, where each key is a string that is associated with a value. Objects are often used when you need to store related data together and want to access it using a descriptive name.
> In summary, objects and arrays differ in terms of their structure, the way they store and organize data, and the type of data they are used to represent. 

#### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
> An example of when you would need to use bracket notation to access an object's properties is when the property name contains special characters, such as spaces or hyphens. In this case, you won't be able to use dot notation to access the property, as it will be interpreted as a syntax error


*Source*
- [Javascript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

### Introduction To The DOM

#### What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents. It represents the structure and content of an HTML or XML document as a hierarchical tree-like structure, where each node in the tree represents an element, attribute, or text in the document. The DOM provides a way for programs to access and manipulate the content and structure of a web document using a set of standard methods and properties. 

#### Briefly describe the relationship between the DOM and JavaScript.
> JavaScript is a programming language that can interact with the DOM to manipulate the structure and content of a web page dynamically. JavaScript can be used to select and modify individual nodes in the DOM, add or remove nodes from the tree, change the content of nodes, and respond to user actions such as clicks and keystrokes. The DOM provides a standard interface that JavaScript can use to access and modify the structure and content of a web page, and JavaScript provides the programming logic to perform those actions.


*Sources*
- [Introduction to the Dom](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction_)

- [Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

- [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
