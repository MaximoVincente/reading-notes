# "Class 08" Reading Notes 📖

***This topic matters for styling. These are very useful styling options that we frequently see in web appllications.***

## CSS Flexbox

1. **Flexbox is designed for one-dimensional content. Explain what this means.**
   - It excels at taking a bunch of items which have different
   sizes, and returning the best layout for those items.
This is the ideal layout model for this sidebar pattern. Flexbox not only helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line. Instead of setting rigid dimensions for the browser to follow, with flexbox, you can instead provide flexible boundaries to hint how the content could display.
2. **Explain the difference between the main axis and cross axis.**
   - The main axis is the one set by your `flex-direction` property. If that is `row` your main axis is along the row, if it is `column` your main axis is along the column.
   Flex items move as a group on the main axis. Remember: we've got a bunch of things and we are trying to get the best layout for them as a group.
The cross axis runs in the other direction to the main axis, so if `flex-direction` is row the cross axis runs along the column. You can do two things on the cross axis. You can move the items individually or as a group so they align against each other and the flex container. Also, if you have wrapped flex lines, you can treat those lines as a group in order to control how space is assigned to those lines.
3. **How can using certain properties of flexbox negatively impact accessibility?**
   - You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The `row-reverse` and `column-reverse` values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

## CSS Layout - Flexbox

1. **What are some advantages of using flexbox over float?**
   - They can display as a row, or a column.
   - They respect the writing mode of the document.
   - They are single line by default, but can be asked to wrap onto multiple lines.
   - Items in the layout can be visually reordered, away from their order in the DOM.
   - Space can be distributed inside the items, so they become bigger and smaller according to the space available in their parent.
   - Space can be distributed around the items and flex lines in a wrapped layout, using the Box Alignment properties.
   - The items themselves can be aligned on the cross axis.
2. **How does this topic connect with your long term goals?**
   - It is another tool to add for web applications. It is a very functional feature noticed in many popular web apps, which means that it is important as a Dev to know flexbox and floats. 

## Thing I want to know more about

Demo on using a flexbox.

## References

- [CSS Flexbox](https://web.dev/learn/css/flexbox/)
- [CSS Layout Flebox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
