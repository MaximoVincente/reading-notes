# "Class 04" Reading Notes 📖

## Creating Hyperlinks

1. **To create a basic link, we wrap text or other content inside what element?**
   - A basic link is created by wrapping the text or other content, see Block level links, inside an `<a>` element and using the href attribute, also known as a Hypertext Reference, or target, that contains the web address.

    ``` html
   <p> I'm creating a link to <a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>. </p>




    ```

2. **The href attribute contains what information?**
   - The href attribute, also known as a Hypertext Reference, or target, that contains the web address.
3. **What are some ways we can ensure links on our pages are accessible to all readers?**
   - We need to make our links accessible to all readers, regardless of their current context and which tools they prefer. For example:
     - Screen reader users like jumping around from link to link on the page, and reading links out of context.
     - Search engines use link text to index target files, so it is a good idea to include keywords in your link text to effectively describe what is being linked to.
     - Visual readers skim over the page rather than reading every word, and their eyes will be drawn to page features that stand out, like links. They will find descriptive link text useful.

## CSS Layouts Normal Flow, and Positioning

1. **What is meant by “normal flow”?**
   - Is the system by which elements are placed inside the browser's viewport. By default, block-level elements are laid out in the block flow direction, which is based on the parent's writing mode (initial: horizontal-tb).It ensures that your content is readable even if the user's using a very limited browser or a device such as a screen reader that reads out the content of the page. In addition, since normal flow is designed to make a readable document, by starting in this way you're working with the document rather than struggling against it as you make changes to the layout.
2. **What are a few differences between block-level and inline elements?**
   - By default, a block level element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content. The size of Inline elements is just the size of their content. You can't set width or height on inline elements — they just sit inside the content of block level elements.
3. **___ positioning is the default for every html element.**
   - Static Positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here."
4. **Name a few advantages to using absolute positioning on an element.**
   - We can create isolated UI features that don't interfere with the layout of other elements on the page. For example, popup information boxes, control menus, rollover panels, UI features that can be dragged and dropped anywhere on the page, and so on.
5. **What is a key difference between fixed positioning and absolute positioning?**
   - Whereas absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), fixed positioning usually fixes an element in place relative to the visible portion of the viewport. **This means that you can create useful UI items that are fixed in place, like persistent navigation menus that are always visible no matter how much the page scrolls.**

## JS Functions

1. **Describe the difference between a function declaration and a function invocation.**
   - Declaring a function is the function after it has been defined, and invoking it, is to call it or run it where you want it.
   - E.g.,:

 ```Javascript
    //This is a Function Declaration
     function myFunction() {

  alert('hello');
 }
    //This is a Function Invocation 
    myFunction();//calling the function 




 ```

2. **What is the difference between a parameter and an argument?**
   - Parameters are sometimes called arguments. "I did not read any difference"

## Miscellaneous "6 Reasons for Pair Programming

1. **Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.**
   - **"Engaged Collaboration", and "Learning from Fellow Students"**: This benefit to pair programming has already helped me exponentially, in code fellows. Collaborating with my classmates in Remo, where we would ask questions about the projects, and inspect each other's code. It has been helpful to read a fellow cassmate's code and understand what their code is doing, and identify any bugs, also when I have a bug and read my code out load to a classmate, I identify the buy; having someone to read out loud your code definitely helps! Additionally, when working with a TA has really helped me too, having that expertise explanation of why the code was not working, and how the solution worked.

## References

- [HTML Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)
- [CSS Layouts(Normal Flow and Positioning)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
- [JS Functions](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)
- [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)
- [My GitHub Portfolio](https://github.com/MaximoVincente/)
