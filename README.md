# Insta-Love-Button

**Project: Heart Icon Animation**

**Description:**
This project demonstrates a simple animation of a heart icon using HTML, CSS, and JavaScript. The heart icon changes color when the user hovers over it.

**Step-by-Step Explanation:**

1. **HTML Structure:**
   - The HTML file consists of a container `div` with an `id` of `"container"`.
   - Inside the container, there is an `<img>` element that displays the heart icon. The image source is specified in the `src` attribute.
   - There is also an `<i>` element with the class `"ri-heart-3-fill"`. This element is used to display the heart icon using the Remix Icon library.

2. **CSS Styling:**
   - The CSS file contains styles for the container and the heart icon.
   - The container is positioned absolutely and centered using `position

## Image Viewer

This code creates a simple image viewer using HTML, CSS, and JavaScript. It displays an image within a container and provides a button to toggle the visibility of a heart icon overlay.

- The `<div>` element with the id `container` serves as the main container for the image viewer.
- Inside the container, an `<img>` element is used to display the image. The `src` attribute specifies the path to the image file.
- A `<i>` element with the class `fa fa-heart` is positioned absolutely within the container. This element will be used to display the heart icon.

3. **Animation Effects:**
   - Upon a double-click, the following animation effects are applied to the heart icon:
     - `transform: translate(-50%,-50%) scale(1);`: This line positions the heart icon at the center of the container and scales it to its original size.
     - `opacity: 0.8;`: This line sets the opacity of the heart icon to 80%, making it slightly transparent.
     - `setTimeout(function(){love.style.opacity = 0;},1000);`: This line uses `setTimeout` to fade out the heart icon after 1 second.
     - `setTimeout(function(){love.style.transform = "translate(-50% ,-50%) scale(0)";},2000);`: This line uses `setTimeout` to scale down the heart icon to zero after 2 seconds, making it disappear.



