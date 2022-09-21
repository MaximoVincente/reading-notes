# "Class 03" Reading Notes 📖

***This topic matters, because to have the effect we want in our applications we need to pass functions. Additonally, it is important to know the spread operator if we need to combine, add, or copy an array***

## React Docs - lists and keys

1. **What does .map() return?**
   - It returns a new array.
2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**
   - We have to use curly braces `{}`
3. **Each list item needs a unique ____.**
   - key
4. **What is the purpose of a key?**
   - Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

## The Spread Operator

1. **What is the spread operator?**
   - The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments. It refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
2. **List 4 things that the spread operator can do.**
   - It can be used for:
     - Finding the largest number in an array with Math.max()
     - Copying an array
     - Concatenating or combining arrays
     - Using Math functions
     - Using an array as arguments
3. **Give an example of using the spread operator to combine two arrays.**
   - Combining words to a sentence.
4. **Give an example of using the spread operator to add a new item to an array.**
   - Adding an item to an inventory list.
5. **Give an example of using the spread operator to combine two objects into one.**
   - Adding a first and last name, or name and date of birth.

## How to Pass Functions Between Components

1. **In the video, what is the first step that the developer does to pass functions between components?**
   - create a function that create an array using map().
2. **In your own words, what does the increment function do?**
   - It effect a change in one component state from within another component, to increment the count when the button is clicked.
3. **How can you pass a method from a parent component into a child component?**
   - By using this."function name", passing it to the object
4. **How does the child component invoke a method that was passed to it from a parent component?**

## Things I want to more about

I would like to know the structure if many functions are used. does it have to be in order (top down)?

## References

- [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
- [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
- [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
