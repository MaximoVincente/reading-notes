# "Class 09" Reading Notes 📖

***This topic matters because it is an importan topic for UI. These are features that will help your web application be an app that users want to come back to.***

## Your First Web Form and How to Structure Web Form

1. **Why are forms so important in web development?**
   - Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).
2. **When designing a form, what are some key things to keep in mind when it comes to user experience?**
   - Before starting to code, it's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.
3. **List 5 form elements and explain their importance.**
   - `<form>` This element formally defines a form. It's a container element like a `<section>` or `<footer>` element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes:
     - The action attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
     - The method attribute defines which HTTP method to send the data with (usually get or post).
   - The `<label>`, `<input>`, and `<textarea>` elements
   - Our contact form is not complex: the data entry portion contains three text fields, each with a corresponding `<label>`:
     - The input field for the name is a single-line text field.
     - The input field for the e-mail is an input of type email: a single-line text field that accepts only e-mail addresses.
     - The input field for the message is a `<textarea>`; a multiline text field.
   - On the `<input>` element, the most important attribute is the type attribute. This attribute is extremely important because it defines the way the `<input>` element appears and behaves. You'll find more about this in the Basic native form controls article later on.
     - In our simple example, we use the value text for the first input — the default value for this attribute. It represents a basic single-line text field that accepts any kind of text input.
     - For the second input, we use the value email, which defines a single-line text field that only accepts a well-formed e-mail address. This turns a basic text field into a kind of "intelligent" field that will perform some validation checks on the data typed by the user. It also causes a more appropriate keyboard layout for entering email addresses (e.g. with an @ symbol by default) to appear on devices with dynamic keyboards, like smartphones. You'll find out more about form validation in the client-side form validation article later on.

## Introduction to Events

1. **How would you describe events to a non-technical friend?**
   - Hey friend,events are the thing you click on a website that will give you a response back when you type something in and click ok.
2. **When using the addEventListener() method, what 2 arguments will you need to provide?**
   - Inside the `addEventListener()` function, we specify two parameters:
        - The name of the event we want to register this handler for
        - The code that comprises the handler function we want to run in response to it.
3. **Describe the event object. Why is the target within the event object useful?**
   - Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.
   - The are useful because `e` `evt` `event`, are short and easy to remember. It's always good to be consistent — with yourself, and with others if possible.
4. **What is the difference between event bubbling and event capturing?**
   - In the capturing phase:
     - The browser checks to see if the element's outer-most ancestor (`<html>`) has a click event handler registered on it for the capturing phase, and runs it if so.
     - Then it moves on to the next element inside `<html>` and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.
   - In the bubbling phase, the exact opposite of the capturing phase occurs:
     - The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so.
     - Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the `<html>` element.

## Things I want to know more about

How to livk an event that when the user enters an email, it sends an email back to the user.

## References

- [Your First Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
- [How To Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
- [Introductio To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
