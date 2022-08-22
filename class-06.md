# "Class 06" Reading Notes 📖

***These subjects are very important, using objects is more efficient than just using arrays, since you can store value, but also a function to call it, in this case the function would be a method. It further explains the built in methods we've been using, and how they work***

## Javascript Object Basics

1. **How would you describe an object to a non-technical friend you grew up with?**
   - Objects are like the function contacts in your phone. They have a list of names, phone numbers, address, ect., and you select a contact and press message, and your phone selecta that number associated with that name to be messaged
2. **What are some advantages to creating object literals?**
   - It is a simpler, and shorter syntax for an object
3. **How do objects differ from arrays?**
   - Arrays just stores data types, object and store it and call it with a function (method.)
4. **Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
   - If an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable inside brackets
5. **Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?**

       ```javascript
        const dog = {
        name: 'Spot',
        age: 2,
        color: 'white with black spots',
        humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
          }
        } 
       ```

   - It refers to "dog" in this case. The advantage is, when using constructors to create more than one object from a single object definition, and that's the subject of the next section.

## Intro to the DOM

1. **What is the DOM?**
   - The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. This guide will introduce the DOM, look at how the DOM represents an HTML document in memory and how to use APIs to create web content and applications. Is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.
2. **Briefly describe the relationship between the DOM and JavaScript.**
   - Javascript uses the DOM to access the documents and its elements for a web page for example. They can all be accessed and manipulated using the DOM and JavaScript.

## Things I want to know more about

- I want to know more about constructors, and how to use them.

## References

- [Javascript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

## Misc Review

- [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
- [What’s the Difference Between Primitive Values and Object References in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
- [My GitHub Portfolio](https://github.com/MaximoVincente/)
