# "JavaScript Basics" Reading Notes 📖

***Learning the basics of HTML, and JavaScript is very crucial, as it will be the foundation of the upcoming classes. Understanding how HTML and JS works makes it easier to understand; knowing what each element, attribute, tag, variable, function does, is the first step to know how to use it, and effectively apply it.***

## Getting Started

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

## Introduction to HTML

1. **What is an HTML attribute?**
   - Attributes contain extra information about the element that won't appear in the content. **An attribute should have:**
     - A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
     - The attribute name, followed by an equal sign.
     - An attribute value, wrapped with opening and closing quote marks.(*Getting started with HTML*)
   - Some of the attributes are:
     - `class` attribute, an identifying name used to target the element with style information.
     - The Anchor element `<a>`, which makes the enclosed text a hyperlink, uses `href` attribute to specify the web address for the link, `title` attribute to specify extra information about the link, and `target` to specify the browsing context used to display the link.
     - Boolean attributes
2. **Describe the Anatomy of an HTMl element.**
   - The opening tag: This consists of the name of the element (e.g. `<p>` for a paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect.
   - The content: This is the content of the element. E.g., `My name is Maximo`.
   - The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results. E.g., `<p>My name is Maximo</p>`.
   - **The element is the opening tag, followed by content, followed by the closing tag.**
3. **What is the Difference between `<article>` and `<section>` element tags?**
   - `<article>` encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
   - `<section>` is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break `<article>`s up into different `<section>`s, or `<section>`s up into different `<article>`s, depending on the context.
4. **What Elements does a “typical” website include?**
   - `<!DOCTYPE html>` is the shortest string of characters that counts as a valid doctype.
   - `<html></html>`: The `<html>` element. This element wraps all the content on the page. It is sometimes known as the root element.
   - `<head></head>`: The `<head>` element. This element acts as a container for everything you want to include on the HTML page, that isn't the content the page will show to viewers. This includes keywords and a page description that would appear in search results, CSS to style content, character set declarations, and more. You will learn more about this in the next article of the series.
   - `<meta charset="utf-8">`: The `<meta>` element. This element represents metadata that cannot be represented by other HTML meta-related elements, like `<base>`, `<link>`, `<script>`, `<style>` or `<title>`. The charset attributes sets the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. With this setting, the page can now handle any textual content it might contain. There is no reason not to set this, and it can help avoid some problems later.
   - `<title></title>`: The `<title>` element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.
   - `<body></body>`: The `<body>` element. This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.(*Getting started with HTML*)
   - Inside `<body></body>` The typical elements are:
     - header: `<header>`.
     - navigation bar: `<nav>`.
     - main content: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
     - sidebar: `<aside>`; often placed inside `<main>`.
     - footer: `<footer>`.
5. **How does metadata influence Search Engine Optimization?**
   - By using meta elements to specify a description, name, etc., that includes keywords relating to the content of the web page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines, and improve search rankings.
6. **How is the `<meta>` HTML tag used when specifying metadata?**
   - By including the `name` and `content` attribute to the `<meta>` element.
      - The `name` attribute specifies the type of meta element it is; what type of information it contains.
      - The `content` attribute specifies the actual meta content.
      - Here's and example: `<meta name="description" content="This is the content of your web page">`

## Miscellaneous

***How to start to design a Website***

1. What is the first step to designing a Website?
   - The first step to designing a website is *"Project Ideation"*:
     - What exactly do I want to accomplish?
     - How will a website help me reach my goals?
     - What needs to be done, and in what order, to reach my goals?
2. What is the most important question to answer when designing a Website?
   - What exactly do I want to accomplish? (List all the goals you want to reach.)

***Semantics***

1. Why should you use an `<h1>` element over a `<span>` element to display a top level heading?
   - `<h1>` has semantic value, `<span>` does not. HTML should be coded to represent the data that will be populated and not based on its default presentation styling. For presentation, you should use **CSS**
2. What are the benefits of using semantic tags in our HTML?
   - Search engines will consider its contents as important keywords to influence the page's search rankings, influencing Search Engine Optimization.
   - Screen readers can use it as a signpost to help visually impaired users navigate a page
   - Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
   - Suggests to the developer the type of data that will be populated
   - Semantic naming mirrors proper custom element/component naming

***What is JavaScript?***

1. Describe 2 things that require JavaScript in the Browser?
   - Adding browser APIs.
   - To make the web browser dynamic.
2. How can you add JavaScript to an HTML document?
   - JavaScript uses `<script>` to add it to HTML.
   - Internal Javascript: Adding it directly to the HTML
   - External Javascript: Adding an external .js file.

## Things I want to know more about

1. What is the best practice to add JavaScript, and ensure that HTML runs prior to it to avoid error?
2. How do I add APIs?
3. What is the best use for `<div>`?

***References***

- [Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/)
- [How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
- [Javascript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/)
- [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- [HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)
- [How to start to design a website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)
- [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

- [My GitHub Portfolio](https://github.com/MaximoVincente/)
