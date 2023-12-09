# Class-11 Reading Notes

## Video and Audio

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.

  - In the early 2000s the only way to use audio or video was with third party plugins, most common being Adobe Flash. HTML 5 decreased the requirement of plugins required for multimedia.<br>

- Describe the use of the `src` and `controls` attributes in the `<video>` element.

  - `src` is an attribute that references the source path of the video and  `controls` is an attribute that adds volume, play, and pause controls to the video element.<br>

- Why is it important to have fallback content inside the `<video>` element?

  - The fallback content is the paragraph inside the `<video>`. It’s important for browser compatibility and offers either alternate text or content.<br>


- Write a very short story where <audio> and <video> are characters.
  - Once upon a time there was a little boy, `<video>`, who had a hard time making friends because he was unable to talk. Until one day he met `<audio>` who had a similar challenge, but he spoke often but had difficulty with physical movement. Until one day, they saw a shooting star and wished they could each have both abilities. The next day they woke up and could both speak and move as they pleased and they felt more alive than ever and were able to fully share their expressions with the world.


## Grind

- How does Grid layout differ from Flex?

  - Grid- two dimensional(vertical and horizontal) with more precise placement of elements than flexbox and allows for more complex designs
  - Flexbox- one dimensional(vertical or horizontal) focuses on the order of elements for placement and allows for flexible and responsive components. 

- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms.

  - Grid Container- parent element containing grid items
  - Grid Item- children of container and placed within the grid based on the rows and columns
  - Grid Line- separates the grid cells horizontally and vertically and are numbered starting at 1
  - Grid Track- space between grid lines and defines the size of the grid
  - Grid Area- is the area between four grid lines.


## Responsive Images

- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

  - Bandwidth optimization
  - User experience
  - Faster loading
  - Accessibility


- Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.

  - `srcset`- is a set of image sources and their sizes, which then the browser chooses which image to use based on the user’s device.
  - `sizes`- defines the intended size of the image to help the browser choose the best image from the `srcset`.

- How is `srcset` more helpful for responsive images than CSS or JavaScript?

  - `srcset` is more automated and efficient than using CSS and JavaScript to create responsive images.
