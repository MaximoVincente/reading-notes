# "JavaScript Basics" Reading Notes 📖

***Getting Started***

1. **Compose a short poem describing how HTTP sends data between computers.**
   - The browser sends an HTTP request message to the server, requesting a copy of the website for the client. The data or message sent to the server from the client, and vice-versa, is sent through the internet connection, by using the *Transmission Control Protocol and Internet Protocol (TCP/IP).* If the server approves the client's request, the server sends the client a "200 OK" message, and then start sending data packets to the web browser. The browser assembles the data packet to complete the full web page, and then display it the client.
2. **Describe how HTML, CSS, and JS files are “parsed” in the browser.**
   - The browser parses the HTML file first, and that leads to the browser recognizing any `<link>`-element references to external CSS stylesheets and   any `<script>`-element references to scripts.
   - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
   - The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
   - As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
3. **How can you find images to add to a Website?**
   - Youcan Google search the image you want for your web page, and go to google images. Right click the image you want, click *Save image as*, save it to your desired location, and copy the web address to add later when attaching the image to your code. Additionally, in Google images, click on the tools button and select *Creative Commons licenses*, to not violate copyright.
4. **How do you create a String vs a Number in JavaScript?**
   - To create a string, you use quotes `''` between the letters or numbers, and for a number, type just the number. E.g., `let myVariable = '11';`(String) vs `let myVariable = 11;` (Number).
5. **What is a Variable and why are they important in JavaScript?**
   - Variables are containers that stores values. You can declare a variable with the const or let keyword, followed by the name you give to that variable, and closing it with a semicolon `;` to end the statement. JavaScript is case sensitive. This means `myVariable` is not the same as `myvariable` (*JavaScript Basics*). Variables may hold values that have different data types:
     - String `let myVariable = 'Max';`
     - Number`let myVariable = 10;`
     - Boolean`let myVariable = true;`
     - Array`let myVariable = [1,'Max','Pete',11];` Refer to each member of the array like this: `myVariable[0], myVariable[1], etc.,`
     - Object`let myVariable = document.querySelector('h1');` All of the above examples too.

***Introduction to HTML***

s
