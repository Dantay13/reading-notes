# Class 11 Readings: Audio, Video, Images

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
<br> In the early days videos and audios were being displayed using plugin-based technology like `Flash` and `Silverlight`. But these had security and accessibility issues. These are now obsolete and the HTML `<video>` and `<audio>` tags are rge replacements.

2. Describe the use of the `src` and `controls` attributes in the `<video>` element.
<br> `src`: In the same way as for the `<img>` element, the `src` (source) attribute contains a path to the video you want to embed. It works in exactly the same way.
<br> `Control`: Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate `JavaScript API`. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

3. Why is it important to have fallback content inside the `<video>` element?
<br> This is important because it will be displayed if the browser accessing the page doesn't support the `<video>` element, allowing a fallback for older browsers. This can be anything; Inexample, provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.

4. Write a very short story where `<audio>` and `<video>` are characters.
<br> 


[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

1. How does Grid layout differ from Flex?
<br> Flex is 2D while grid is 3D.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid Container: The element on which `display: grid` is applied. It’s the direct parent of all the grid items. 
- Grid Item: The children (i.e. direct descendants) of the grid container.
- Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical `(“column grid lines”)` or horizontal `(“row grid lines”)` and reside on either side of a row or column.

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
<br>

2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
<br> `srcset`: Defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma. For each one, we write:
<br> a). An image filename (elva-fairy-480w.jpg)
<br> b). A space
<br> c). The image's intrinsic width in pixels (480w) — note that this uses the `w` unit, not `px` as you might expect. An image's `intrinsic size` is its real size, which can be found by inspecting the image file on your computer (for example, on a Mac you can select the image in Finder and press `Cmd` + `I` to bring up the info screen).

<br> `sizes`: Defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true — these are the hints we talked about earlier. In this case, before each comma we write:
<br> a). A media condition ((max-width:600px)) — Media condition describes a possible state that the screen can be in. In this case, we are saying "when the viewport width is 600 pixels or less".
<br> b). A space
<br> c). The width of the slot the image will fill when the media condition is true (480px)

3. How is `srcset` more helpful for responsive images than CSS or JavaScript?
<br> Because when a browser loads a page it downloads any images before the main parser has started to loadand interpret the pages's CSS and JavaScript. This mechanism is not useful for responsive images.

[<== BACK](reading-notes/README.md)
