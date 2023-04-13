## Forms and JS Events

### HTML Forms

#### Why are forms so important in web development?
> Forms are an essential part of web development as they allow users to interact with web pages by providing input and submitting data. They provide a way for users to enter information such as text, numbers, dates, and files, and transmit that data to the server for further processing. This is useful for tasks such as user registration, login, checkout, and search.

#### When designing a form, what are some key things to keep in mind when it comes to user experience?
> Keep it simple, make it easy to read, use logical grouping, provide feedback, consider the order, provide defaults, and use validation.

#### List 5 form elements and explain their importance.
1. Text Input Fields - One of the most commonly used form elements, text input fields are used to collect textual information such as names, email addresses, phone numbers, and other alphanumeric data.

2. Radio Buttons - used when users need to select one option from a list of options. They are useful for presenting mutually exclusive options and provide users their choices.

3. Checkboxes - used when users need to select multiple options from a list of options.

4. Select Dropdowns - used when users need to select one option from a long list of options. They take up less space than radio buttons or checkboxes.

5. Submit Button - used to submit the form data to the server. It is the final step in the form completion process and is critical for the form to be submitted successfully.

### Introduction To Events.

#### How would you describe events to a non-technical friend?
> Think of Events as the things that happen when you do something on your computer or phone. Events can trigger a reaction, like opening a new window, displaying a message, or playing a sound and are important because they allow us to interact with technology and control how it behaves.

#### When using the `addEventListener()` method, what 2 arguments will you need to provide?

1. A string that specifies the type of event you want to listen for, such as "click", "submit", "keydown", "load", "change", etc.

2. The second argument is a function or callback that will be executed when the event occurs. This function can be an anonymous function or a named function.

#### Describe the event object. Why is the target within the event object useful?
> The event object is a JavaScript object that represents an event that has occurred, such as a mouse click, key press, or form submission. When an event is triggered, the browser creates an event object and passes it as an argument to the event handler function. This is useful because it allows developers to identify the element that triggered the event enabling them to create more dynamic and interactive web applications.

#### What is the difference between event bubbling and event capturing?
> Event bubbling and event capturing are two different approaches to how events propagate through the DOM (Document Object Model) tree in JavaScript.

> Event capturing refers to the process where an event starts at the top of the DOM tree and works its way down to the element where the event occurred. This is also known as the "top-down" approach.

> Event bubbling refers to the process of propagating the event from the target element that triggered the event up to the root element of the DOM tree. In other words, the event starts at the bottom of the DOM tree and works its way up to the top. 

*Sources*
- [Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

- [How to Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

- [Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

- [HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

- [Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)

## Things I want to know more about
