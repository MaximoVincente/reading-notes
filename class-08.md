# "Class 08" Reading Notes 📖

***m***

## CSS Flexbox

1. **Flexbox is designed for one-dimensional content. Explain what this means.**
   - It excels at taking a bunch of items which have different
   sizes, and returning the best layout for those items.
This is the ideal layout model for this sidebar pattern. Flexbox not only helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line. Instead of setting rigid dimensions for the browser to follow, with flexbox, you can instead provide flexible boundaries to hint how the content could display.
2. **Explain the difference between the main axis and cross axis.**
   - The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.
   Flex items move as a group on the main axis. Remember: we've got a bunch of things and we are trying to get the best layout for them as a group.
The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column. You can do two things on the cross axis. You can move the items individually or as a group so they align against each other and the flex container. Also, if you have wrapped flex lines, you can treat those lines as a group in order to control how space is assigned to those lines.
3. **How can using certain properties of flexbox negatively impactaccessibility?**

## CSS Layout - Flexbox

1. **What are some advantages of using flexbox over float?**
2. **How does this topic connect with your long term goals?**

## Thing I want to know more about

## References

- [CSS Flexbox](https://web.dev/learn/css/flexbox/)
- [CSS Layout Flebox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
