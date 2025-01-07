# Frontend Mentor - QR code component solution

This is the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview
![image info](./images/Screenshot%20from%202025-01-07%2021-05-24.png)

### Built with

-HTML5 
- CSS
- Flexbox


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- How to **auto values om margin properties** : 
In CSS, the `margin` property is used to create space around elements. When you set the `margin` to `auto`, it allows the browser to automatically calculate the margin space. This is particularly useful for centering block-level elements within their container.

Here's what `margin: auto;` typically means:

1. **Horizontal Centering**: When applied to a block element (like a `div`), setting the left and right margins to `auto` allows the element to occupy the available horizontal space equally on both sides, effectively centering it within its parent element.

   ```css
   .centered {
       width: 50%; /* or any other width */
       margin: 0 auto; /* top/bottom margin 0, left/right margin auto */
   }
   ```

2. **Vertical Margins**: The `margin: auto;` setting does not have the same effect for vertical margins (top and bottom) unless certain conditions are met (like using flexbox or grid layouts).

3. **Flexbox and Grid**: In flexbox or grid layouts, `margin: auto;` can also be used to distribute space between items or to push items to the edges of their container.

In summary, using `margin: auto;` helps in controlling the layout and positioning of elements within a webpage, particularly for centering elements horizontally.

- Remembered how to change local repository url
`
git remote set-url origin <put the new url there>
`
- How to insert an image with markdown

`
![<alternative tex>t](<image url>)
`
