# Exploring Divs and Positioning

There are several items for you to explore today.

1) The images do not currently work. Look at the code for the images and fix the mistakes so that the Ghost images are properly displayed. This is a common mistake that many students are making...
2) Examine at the `style.css` stylesheet. What properties and values have we not learned yet?
    * Take some time with your partner to modify some of the new values to figure out what they do.
    * You can always use the history to undo changes that you don't want to save.
    * You could also use the inspect tool to do this without actually modifying the `style.css` document.
    * Finally which property would you like us to discuss?
4) Currently the section on Blinky has a `.blinky` class applied to it. This is why the Blinky section has some style.
    * Fix the **Inky** section with your partner to match the Blinky section (only with colors that apply to Inky).
    * Do the same for **Pinky** and **Clyde**.

## Divs and flex
A `<div></div>` element represents a division of the page. It is used to group elements together. This is a common way to position and style elements on a webpage.

The CSS property of `display` can be set to `flex` which allows us to place elements on the page horizontally. It also allows more options for spacing out items.

1) Create a set of `<div></div>` tags above the Pinky section. Then create a blank line between them like:
    ```
    <div>
    
    </div>
    ```
Next move all of the code from the Pinky section to between the opening and closing `div` tags.
1) Add a `.ghost` class to `style.css` so that it follows the same pattern as the Blinky class but with Pink. Finally add a `class="pinky"` attribute to the opening `<div>` tag.
