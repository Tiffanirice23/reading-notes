## Audio, Video, Images

### Video and Audio Content

#### Explain how the ability to use video and audio on the web has evolved since the early 2000s.

> In the early 2000s, the most common way to add video and audio to a web page was to use third-party plugins like Flash, QuickTime, or Windows Media Player. These plugins were not always reliable, and users had to install them separately, which created compatibility and security issues.

#### Describe the use of the src and controls attributes in the `<video>` element.

> The `src` attribute specifies the URL of the video file that should be played, and the `controls` attribute is a Boolean attribute that displays the browser's built-in video controls, such as play/pause, volume, and fullscreen.

#### Why is it important to have fallback content inside the `<video>` element?

> It's important to have fallback content inside the `<video>` element due to browser compatibility and accessibility. Not all browsers support the `<video>` element so having fallback content ensures that users can still access the content if the video fails to load or play. Also, users who are visually impaired may use screen readers to access content on the web. 

#### Write a very short story where `<audio>` and `<video>` are characters.

> `<audio>` and `<video>` were two best friends who loved to go hiking together. `<audio>` used his sound engineering skills and recorded the soothing sounds of a waterfall while `<video>` was inspired by the majestic visual display of the waterfall and decided to capture it on camera. Together, `<audio>` and `<video>` created a multimedia experience for users.

*Source*

- [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)


### A Complete Guide To Grid

#### How does Grid layout differ from Flex?

> Flexbox is best suited for simpler layouts, where you need to align elements along a single axis, while Grid is ideal for complex layouts where you need to align elements in multiple rows and columns.

#### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

1. Grid container is an element that has been set to `display: grid`. It is the parent element of all the grid items and establishes the grid formatting context.

2. A Grid item is any child element of a grid container that has been set to `display: grid`. Each grid item is positioned within the grid container according to the grid lines.

3. Grid line are the lines that define the rows and columns of the grid. Grid lines are numbered starting from 1 and can be referred to using positive or negative integer values. Negative values are used to count from the end of the grid, so -1 would refer to the last row or column.

*Sources*
- [A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Responsive Images

#### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

> Making images responsive is an important best practice for web development, as it can improve site performance, user experience, and accessibility, and ensure that websites are accessible and usable on all devices.

#### Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.

> `Srcset` and `sizes` are attributes of the `<img>` element that allow developers to specify multiple image sources and sizes to ensure that the appropriate image is loaded based on the user's device and screen size

#### How is `srcset ` more helpful for responsive images than CSS or JavaScript?
> `srcset` is more helpful for responsive images than CSS or JavaScript because it allows the browser to choose the most appropriate image for the user's device and screen size, while also reducing the amount of data that needs to be downloaded.

*Source*
- [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

- [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

- [Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
