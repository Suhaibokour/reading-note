# React and Forms

## forms
* The form has the default HTML form behavior of browsing to a new page when the user submits the form. If you want this behavior in React, it just works. But in most cases, it’s convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form. The standard way to achieve this is with a technique called “controlled components”.
## What is a ‘Controlled Component’?
* A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state.
## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. 
* In HTML, form elements such as , , and typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState(). 
## How do we target what the user is entering if we have an event handler on an input field? 
* When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## Why would we use a ternary operator?
* Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.


