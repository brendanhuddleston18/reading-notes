# Reading Class 11

## Why are these important?

- Video and audio content are important in order to implement more visual and audio aspects into your website which could make it more appealing and even accessible.

- Grid allows users to adjust the layout of content on a page in a two dimensional manner and that allows seamless cooperation with flex.

- Image responsiveness is important for making your website and its content available for all users and that they see the website how you intend. 

## Video and Audio Content

1. The ability to use video and audio has evolved drastically since the early 2000s.  Flash and silverlight were used to incorporate online videos and audio but were prone to security and accessibility issues.  Native HTML and JavaScript APIs are preffered and more modern tools to use.

2. The `src` attribute is the path to the content you want displayed inside of the element.  `controls` Allow for more accessibility and the ability to control video/audio playback.  Interface must include a way to start and stop the media and the ability to adjust the volume.

3. Fallback content provides a backup element of content in case the browser that is accessing the page doesn't support the video element.

4. There once was a time in a land far far away where there were these two elements, Video and Audio.  Video and Audio had special abilities.  They were able to join together and provide a piece of media to become a conjoined superhero.  THE END.

## A complete guide to grid

1. Grid is two dimensional while flex is one, allowing the dev more freedom in where they can place content on the webpage.  They work really well together.

2. 
    1. The grid container is the div or elements that wrap the content you want to display in a grid pattern.  
    2. The grid items are the direct children of the grid container. (The actual content that you want to arrange).
    3. Grid lines are the dividers between each cell of the grid.  There are both row and column grid lines.


## Responsive Images

1. Making images responsive saves user bandwidth and can avoid resolution switching problems.

2. `srcset` and `sizes` are two attributes that devs can use to provide additional source images to help the browser pick the right picture/size. [source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

3. `srcset` is more helpful because you are unable to load an image and dynamically change the image to a smaller one with JS.  It would just load the image twice.

## Things I want to know more about

- `srcset` doesn't dynamically change the image?

- If using HTML to inbed video/audio is a modern way of doing things, why don't all browsers make it a standard so they will always load the video/audio elements.