# Express REST API

## [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

### Classes are a template for creating ____.

> Objects

### Can a class declaration be hoisted?

> Class declarations are not hoisted like functions. This means you can use a function before declaring it, but you cannot use a class before declaring it.

### How would you describe a constructor and contextual “this” to a non-technical friend?

> A constructor is like a recipe for creating something in programming."This" is like saying, "I'm talking about this thing right now." It helps you work with the thing you're making using the recipe.

## [Using Express Routing](https://expressjs.com/en/guide/routing.html)

### Within Express, what does routing refer to?

> In Express, routing refers to the process of defining how an application responds to different HTTP requests (like GET or POST) and URLs. It's a way to map specific URLs (routes) to functions or code that should be executed when a client (e.g., a web browser) sends a request to that URL

### What is the difference between a route path and a route method?

> A route path determines the URL pattern, while a route method specifies the HTTP method used to trigger a specific route handler. Together, they help your web application decide how to handle different types of requests at different URLs.

### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

> In summary, you add next as a parameter to route handlers and middleware when you want to control the flow of the request-response cycle. If next is passed to your middleware as a parameter, you can use it to decide whether to continue to the next middleware or route handler, or to handle errors and send responses as appropriate.

## [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

### What is an Express Router?

> An Express Router is a feature in the Express.js web application framework that allows you to organize and modularize your routes and middleware in a more structured and maintainable way. They are useful when building larger web applications that require structuring routes and middleware logically to keep your code organized and maintainable.

### By what mean do we initialize express.Router() in an express server?

1. Import Express: `const express = require('express');

2. Create the Router: `const router = express.Router();`

3. Define Routes and Middleware: 

```router.get('/', (req, res) => {
  res.send('This is the main page.');
});

router.get('/about', (req, res) => {
  res.send('About us page.');
});
```

### What do we use route middleware for?

> Route middleware in Express is used to add custom functionality to routes. It can handle tasks like authentication, validation, logging, error handling, and more. This modular approach helps keep route handlers clean and organized, improving code maintainability and readability.

## Reflection

### What are your learning goals after reading and reviewing the [class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-03/)?

> One of my goals is to get better at CRUD, as it's something that I struggled with during my final 301 project. In general, I need to learn more about backend developement alltogether.
