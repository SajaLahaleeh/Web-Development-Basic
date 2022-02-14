## HTML Forms

### What is Form in HTML?!

HTML Forms are required to collect different kinds of user inputs, such as contact details like name, email address, phone numbers, or details like credit card information, etc.

Forms contain special elements called controls like inputbox, checkboxes, radio-buttons, submit buttons, etc. Users generally complete a form by modifying its controls e.g. entering text, selecting items, etc. and submitting this form to a web server for further processing.

**Here's a simple example of form:**

```
<form action="/action_page.js" method="POST">
    <input type="text" placeholder='your name'>
    <input type="password" placeholder='your password'>
    <input type="submit" value="Submit">
</form>
```

**The `<form></form>` tag is used to create an HTML form.**

#### HTML Form Attribute

| **Attribute** | **Value**  | **Description**                                                |
| ------------- | ---------- | -------------------------------------------------------------- |
| action        | URL        | Specifies where to send the form-data when a form is submitted |
| autocomplete  | on / off   | Specifies whether a form should have autocomplete on or off    |
| method        | get / post | Specifies the HTTP method to use when sending form-data        |
| name          | text       | Specifies the name of a form                                   |

### HTML Form Controls

There are different types of form controls that you can use to collect data using HTML form

- Text Input
- Checkboxes
- Radio Box
- Select Box
- File Select
- boxes Hidden
- Submit and Reset Buttons

### HTML Input

In HTML **`<input type=" ">`** is an important element of HTML form.The "type" attribute of input element can be various types, which defines information field. Such as :

**`<input type="password" name="name">`**

gives a one-line password input field

### Following is a list of all types of `<input>` element of HTML!

| **type=" "** | **Description**                                                                      |
| ------------ | ------------------------------------------------------------------------------------ |
| text         | Defines a one-line text input field.                                                 |
| password     | Defines a one-line password input field.                                             |
| submit       | Defines a submit button to submit the form to server.                                |
| reset        | Defines a reset button to reset all values in the form.                              |
| radio        | Defines a radio button which allows select one option.                               |
| checkbox     | Defines checkboxes which allow select multiple options form.                         |
| button       | Defines a simple push button, which can be programmed to perform a task on an event. |
| file         | Defines to select the file from device storage.                                      |
| image        | Defines a graphical submit button.                                                   |

---

## Task

HTML5 added new types on `<input>` element, take 10 min to search and read about these new types and explain two or three to your mates!
