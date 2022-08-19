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
2. **Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?**
3. **What should you consider when choosing fonts for an HTML document?**
4. **What do font-size, font-weight, and font-style do to HTML text elements?**
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
