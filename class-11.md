# "Class 10" Reading Notes 📖

***This topic matters since most web applications have video and audio. Grid is one of the most useful CSS tool available for layout, and this topic teaches us its purpose. Additonally, with many devices having different screen resolutions and sizes, we wnt to create a web app that gives the user the same experience, regardless of resolution, or devices***

## HTML Video Audio Content

1. **Explain how the ability to use video and audio on the web has evolved since the early 2000s.**
   - When we first started using videos and audio in the web, we had to have silverlight or flash, now we have the `<video>` and `<audio>` elements, and even better, JavaScript to control them! Additionally, we have simpler ways to implement an audio or video file nowadays.
2. **Describe the use of the src and controls attributes in the `<video>` element.**
   - The `<video>` element allows you to embed a video very easily.
     - `src` In the same way as for the `<img>` element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.
     - `controls` Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.
3. **Why is it important to have fallback content inside the `<video>` element?**
   - It allows us to provide a content for when browsers do not support the video. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
4. **Write a very short story where `<audio>` and `<video>` are characters.**
   - Once upon a time in the land of  "The Internet Browser", there were words and images in a box, everyone enjoyed reading the words and and seeing images describing the words. One day, a meteor hit the box, and when everyone gathered, to see if the box was ok, the box was emmiting the sounds words and the images were moving at the same speed of the sounds, displaying what the words described. This changed the Internet Broswer forever, and since then the box has evolved. 

## CSS A Complete Guide To Grid

1. **How does Grid layout differ from Flex?**
   - Flexbox is a one-directional based layout, comparder to grid that has a two-dimensional grid based layout.
2. **Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**
   - **Grid Container:** The element on which display: grid is applied. It’s the direct parent of all the grid items
   - **Grid Item:** The children (i.e. direct descendants) of the grid container.
   - **Grid Line:** The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

## Responsive Images

1. **Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**
   - This helps to improve performance across different devices. Responsive images are just one part of responsive design. Additionally, for UI and UX purpose. 
2. **Define the following `<img>` attributes srcset and sizes. Write an example of how they are used.**
   - `srcset` defines the set of images we will allow the browser to choose between, and what size each image is.
   - `sizes` defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true
3. **How is srcset more helpful for responsive images than CSS or JavaScript?**
   - When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but to be helpful for responsive images, we can implement `srcset`.

## Things I want To More More About

How do I make a mobile and a desktop site, and how will the web app know which size content to show? 

## References

- [HTML Video an Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [A complete Guide to Grind](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
