# "Class 05" Reading Notes 📖

***This topic matters, because it is important to understand the structure of how react works. Thinking in React, is the first step to understand it, and to learn it to create great web applications.***

## React Docs - Thinking in React

1. **What is the `single responsibility principle` and how does it apply to components?**
   - One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
2. **What does it mean to build a ‘static’ version of your application?**
   - A version of the application that takes your data model and renders the UI but has no interactivity.
3. **Once you have a static application, what do you need to add?**
4. **What are the three questions you can ask to determine if something is state?**
   - Is it passed in from a parent via props? If so, it probably isn’t state.
   - Does it remain unchanged over time? If so, it probably isn’t state.
   - Can you compute it based on any other state or props in your component? If so, it isn’t state
5. **How can you identify where state needs to live?**
   - Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions

1. **What is a “higher-order function”?**
   - Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.
2. **Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?**
   - If m is greater than n return true.
3. **Explain how either map or reduce operates, with regards to higher-order functions.**
   - It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum. The parameters to reduce are, apart from the array, a combining function and a start value.

## Things I want to know more about

I would like to se a demo of transforming with map, to better understand.

## References

- [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Higher-Order Functions](<https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK>)
