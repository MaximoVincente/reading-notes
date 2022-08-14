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
4. **How do you create a String vs a Number in JavaScript?**
5. **What is a Variable and why are they important in JavaScript?**
