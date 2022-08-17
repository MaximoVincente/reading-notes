# "Class 03" Reading Notes 📖

***Learning about the box model is the very important part CSS when laying out a web application or web site. Learning this will make an exponential difference in future projects. Arrays, operators, conditionals, and loops, really matters, because it is going to help us code more efficiently and faster. These are topics that we will be using day by day.***

## Learn HTML

1. **When should you use an unordered list in your HTML document?**
   - The `<ul>` element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square.
2. **How do you change the bullet style of unordered list items?**
   - The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.
3. **When should you use an ordered list vs an unorder list in your HTML document?**
   - We can use unordered lists when the list does not need any specific order, i.e., list of ingredients. We can use ordered list when the list requires an
order, i.e., Steps in recipe, turn-by-turn directions, etc.
4. **Describe two ways you can change the numbers on list items provided by an ordered list?**
   - By using the romon numeral type, and the start attribute to set a different number to start.

## Learn CSS

1. **Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**
   - *"Once upon a time there was a style called Padding, and no matter how big it made it's box home, it could never get out of the box. One day padding heared a voice outside of the box, the voice came from Margin. Unlike Padding, Margin lived outside of the border box, but have never been inside of one. she had the power to push the boxes around her."*
2. **List and describe the four parts of an HTML elements box as referred to by the box model.**
   - Making up a block box in CSS we have the:
     - Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
     - Padding box: The padding sits around the content as white space; size it using padding and related properties.
     - Border box: The border box wraps the content and any padding; size it using border and related properties.
     - Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

## Learn JS

1. **What data types can you store inside of an Array?**
     - In an array we can store various data types — strings, numbers, objects, and even other arrays. We can also mix data types in a single array, we do not have to limit ourselves to storing only numbers in one array, and in another only strings.
2. **Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**
   - `const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`
   - Yes, it is a multidimensional array. You can access an item inside an array that is itself inside another array by chaining two sets of square brackets together.
3. **List five shorthand operators for assignment in javascript and describe what they do.**
   - The Assignment operator `(=)` is used to assign a value to a variable. The assignment operation evaluates to the assigned value. Chaining the assignment operator is possible in order to assign a single value to multiple variables.
   - The addition assignment operator (+=) adds the value of the right operand to a variable and assigns the result to the variable. The types of the two operands determine the behavior of the addition assignment operator. Addition or concatenation is possible.
   - The subtraction assignment operator (-=) subtracts the value of the right operand from a variable and assigns the result to the variable.
   - The multiplication assignment operator (*=) multiplies a variable by the value of the right operand and assigns the result to the variable.
   - The exponentiation assignment operator (**=) raises the value of a variable to the power of the right operand.
4. **Read the code below and evaluate the last expression and explain what the result would be and why.**
   - `let a = 10;`
   - `let b = 'dog';`
   - `let c = false;`
   - `// evaluate this`
   - `(a + c) + b;`
   - The result would be 10dog, because it will take the number value and the array.
5. **Describe a real world example of when a conditional statement should be used in a JavaScript program.**
   - `if(fire danger is high){` then no campfire allowed `}` `else{` campfire is allowed `}`
6. **Give an example of when a Loop is useful in JavaScript.**
   - In a game like tetris, you can use a loop to have the pieces continuously falling, until the user loses.

## Things I want to know more about

- I would like to know more about Margin Collapsing
- I would like some clarification when removing an array by knowing the index

***References***

- [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
- [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
- [My GitHub Portfolio](https://github.com/MaximoVincente/)
