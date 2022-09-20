# "Class 01" Reading Notes 📖

***This topic matters, because we are going to render more than just text and images in our application, and understanding the lifecycle of React gives us a better understanding of its methods. Additionally, applications are dynamic, and we are going to need to learn state to make it happen.***

## React Lifecycle

1. **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**
   - The `render` happens first.
2. **What is the very first thing to happen in the lifecycle of React?**
   - Mounting is the first thing that happens in the lifecycle of react.
3. **Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`**
   - `constructor`
   - `render`
   - `componentDidMount`
   - `React Updates`
   - `componentWillUnmount`
4. **What does `componentDidMount` do?**
   - This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

## React State Vs Props

1. **What types of things can you pass in the props?**
   - The counter component (the initial counter) inside of the props. We can also pass a title and a subtitle.
2. **What is the big difference between props and state?**
   - State is inside the component. Props you pass into a component. State is handled inside that component and you can update it inside the component, while  props you handle outside the component, and must be updated outside the component.
3. **When do we re-render our application?**
   - When there is change or update in the application we use state to re-render.
4. **What are some examples of things that we could store in state?**
   - We use state when there is a going to be a change like using a counter, the counter is going to keep updating based on user input, and we need to use state for it.

## Thing I want to know more about

- I would like to see a demo on React lifecycle.

## References

- [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
- [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
