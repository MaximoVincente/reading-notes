# "Class 05" Reading Notes 📖

***mmm***

## Using Images in HTML, Common Image Types, Choosing Image Formats

1. **What is a real world use case for the alt attribute being used in a website?**
   - The user is visually impaired, and is using a screen reader to read the web out to them. In fact, having alt text available to describe images is useful to most users.
   - The spelling of the file or path name might be wrong.
   - The browser doesn't support the image type. Some people still use text-only browsers, such as Lynx, which displays the alt text of images.
   - You may want to provide text for search engines to utilize; for example, search engines can match alt text with search queries.
   - Users have turned off images to reduce data transfer volume and distractions. This is especially common on mobile phones, and in countries where bandwidth is limited or expensive.

2. **How can you improve accessibility of images in an HTML document?**
   - Decoration. You should use CSS background images for decorative images, but if you must use HTML, add a blank alt="". If the image isn't part of the content, a screen reader shouldn't waste time reading it.
   - Content. If your image provides significant information, provide the same information in a brief alt text – or even better, in the main text which everybody can see. Don't write redundant alt text. How annoying would it be for a sighted user if all paragraphs were written twice in the main content? If the image is described adequately by the main text body, you can just use alt="".
   - Link. If you put an image inside `<a>` tags, to turn an image into a link, you still must provide accessible link text. In such cases you may, either, write it inside the same `<a>` element, or inside the image's alt attribute – whichever works best in your case.
   - Text. You should not put your text into images. If your main heading needs a drop shadow, for example, use CSS for that rather than putting the text into an image. However, If you really can't avoid doing this, you should supply the text inside the alt attribute.

3. **Provide an example of when the figure element would be useful in an HTML document.**
   - To provide semantic value to a description of an image. use `<figure></figure>` `<figcaption></figcaption>` instead of `<p></p>`, since the p tags will not give any semantic value.
4. **Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.**
   - Gifs can be animated, and .svg are used mostly for icons, and diagrams.
5. **What image type would you use to display a screenshot on your website and why?**
   - I would choose .jpeg, for compatability.

## Using Colors in CSS, Styling HTML Text Elements

1. **Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.**
   - Background color is the text's background and used in areas with not foreground content, and foreground color is the color property.
2. **Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?**
   - I would research colore blindness, and ensure the colors chosen can be readable for a user thart is color blind.
   - A color that is naturally associated with the topic of my frined's content, such as the existing color identified with a product or idea or a color representative of the emotion you wish to convey.
   - A color that comes from imagery associated with what the content is about.
   - Browse websites that let you look at lots of existing color palettes and images to find inspiration.
3. **What should you consider when choosing fonts for an HTML document?**
   - We should conseider color, font-family, web safe fonts, font size, font weight, font transform (for uppercase, lowercase, capitalize first letter, etc.), text layouts, letter and word spacing.
4. **What do font-size, font-weight, and font-style do to HTML text elements?**
   - `font size` (set with the font-size property) can take values measured in most of these units (and others, such as percentages); however, the most common units you'll use to size text are: `px`, `em`, `rem`. The font-size of an element is inherited from that element's parent element. This all starts with the root element of the entire document — `<html>` — the standard font-size of which is set to 16px across browsers. Any paragraph (or another element that doesn't have a different size set by the browser) inside the root element will have a final size of 16 px. Other elements may have different default sizes. For example, an `<h1>` element has a size of 2 em set by default, so it will have a final size of 32 px.
   - `font-style` is used to turn italic text on or off. Possible values are as follows (you'll rarely use this, unless you want to turn some italic styling off for some reason):
     - normal: Sets the text to the normal font (turns existing italics off).
     - italic: Sets the text to use the italic version of the font, if available; if not, it will simulate italics with oblique instead.
     - oblique: Sets the text to use a simulated version of an italic font, created by slanting the normal version.
   - `font-weight` sets how bold the text is. This has many values available in case you have many font variants available (such as -light, -normal, -bold, -extrabold, -black, etc.), but realistically you'll rarely use any of them except for normal and bold:
normal, bold: Normal and bold font weight.
lighter, bolder: Sets the current element's boldness to be one step lighter or heavier than its parent element's boldness.
100–900: Numeric boldness values that provide finer grained control than the above keywords, if needed.
5. **Describe two ways you could add spacing around the characters displayed in an h1 element.**

## Things I want to Know More About

- 

## References

- [Using Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
- [Choosing Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)
- [Using Colors in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
- [Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
- [My GitHub Portfolio](https://github.com/MaximoVincente/)
