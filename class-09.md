# Class 09 Reading Notes

## HTML Forms

- Why are forms so important in web development?
  - User Data Collection
  - User Interaction
  - Authentication
  - Transactions
  - Searching and filtering
  - Communication
  - When designing a form, what are some key things to keep in mind when it comes to user experience?
  - Clarity/Simplicity
  - Progress indication within the form
  - Mobile responsiveness
  - Feedback
  - Defaults/Autocompletes
  - Load time optimization
  - Minimize distractions
  - Helpful labels and instructions<br>
  
- List 5 form elements and explain their importance.
  - `<form>` - defines a form
  - `<fieldset>` - creates groups within a form
  - `<legend>` - describes the purpose of a `<fieldset>`
  - `<label>` - adds a caption
  - `<input>` - adds buttons, checkboxes, textboxes, etc.<br>

## Introduction to Events

- How would you describe events to a non-technical friend?
  - An event is similar to any particular action occurring within a home gathering. If the entire home represents the entire code, a person cooking dinner would be similar to an event, being that there are different actions and triggers that are individually happening within the home.

- When using the addEventListener() method, what 2 arguments will you need to provide?
  - Type of event - button, drop down, etc.
  - Function to be executed when the event happens

- Describe the event object. Why is the target within the event object useful?
  - An event object stores the details about the event. The target helps to identify what element triggered the event.

- What is the difference between event bubbling and event capturing?
  - Event bubbling is how the browser handles events triggered on a specific element and then to it’s parent element.
  - Event capturing occurs in reverse of event bubbling, meaning the highest ancestor element gets triggered, which then travels to the target element.


