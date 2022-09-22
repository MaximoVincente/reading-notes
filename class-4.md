# "Class 04" Reading Notes 📖

***This topic matters, because forms is used often to recieve input from the user. Additionally, as we learn more about JS we need to learn about the operators that are not often used but we should know how to use it if needed, or if encountered on a code.***

## React Docs - Forms

1. **What is a ‘Controlled Component’?**
   - An input form element whose value is controlled by React in this way is called a “controlled component”. It handles the submission of the form and has access to the data that the user entered into the form.
2. **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**
   - Update as soon as they enter them. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.
3. **How do we target what the user is entering if we have an event handler on an input field?**
   - You can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## The Conditional (Ternary) Operator Explained

1. **Why would we use a ternary operator?**
   - It is an alternative to if else statement. The syntaxt is mush shorter, and you can also nest ternary operators.
2. **Rewrite the following statement using a ternary statement:**

``` js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

- `x===y ? console.log(true) : console.log(false);'

## Things I want to know more about

I want to know more about handling multiple inputs in forms. 

## References

- [React Doc - Forms](https://reactjs.org/docs/forms.html)
- [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
