# "Structure Web Pages with HTML" Reading Notes 📖

- CSS Cascading Style sheets
- Styles we see in in browser from html, is the browsers default, to display the intended content
- CSS is a rule-based language — you define the rules by specifying groups of styles that     should be applied to particular elements or groups of elements on your web page.
- CSS rule opens with a selector from the html element.
- Declarations are made within the `{}`
- All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs"), which are published by standards organizations (such as the W3C, WHATWG, ECMA, or Khronos) and define precisely how those technologies are supposed to behave.
- With an external style sheet, you can change the look of an entire website by changing just one file!
- An internal style sheet may be used if one single HTML page has a unique style.
- The internal style is defined inside the `<style>` element, inside the head section
- An inline style may be used to apply a unique style for a single element.
- To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
- If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be us

- Assume external is navy and internal is orange, If the internal style is defined after the link to the external style sheet, the `<h1>` elements will be "orange”.  However, if the internal style is defined before the link to the external style sheet, the `<h1>` elements will be "navy”.
- All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:
    1. Inline style (inside an HTML element)
    2. External and internal style sheets (in the head section)
    3. Browser default
- The color property specifies the color of text
- CSS Syntax: For color: color|initial|inherit;
- [My GitHub Portfolio](https://github.com/MaximoVincente/)
