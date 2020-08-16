## What It Does ##
This is the codebase for my first project, a site coded only in HTML5 and CSS3 from scratch without any templates or external libraries, which were the limitiations given to me. 

## What I Learned ##
To fulfil all the design requirements for this project, I needed to create a site that validated correctly, was easy to navigate with accessibility in mind, was responsive to resizing, embedded external features (such as maps), featured an image gallery, embedded social media links and ensure it ran the same in all modern browsers.

## Usage Notes ##
Just go to https://tjeepot.github.io/Canary-Canoes/ to see the site in action.

## Guidance Notes ##
* Verdana font has been chosen for the main text as it’s considered one of the best web fonts for readability across different devices and displays.

* \<nav>, \<header>, \<footer> and \<section> tags have been used to order content. This helps accessibility for screen-readers and other web tools.

* Complex CSS used to display images in the navbar, using a combination of image anchors in HTML, z-index values to push the image behind other elements, dynamic scaling and positioning to look decent on all display sizes and use of the ‘overflow’ attribute to ensure the image doesn’t overrun into the page content.

* Almost all boxes that make up the page are designed as CSS3 Flexboxes to allow content to move around the page independent of screen resolution. They were designed for 1024x768 (960px Horizontal) but tested to correctly scale from a width of 460px to beyond ‘2K’.

* The Homepage is accessible on all pages except index.html via the darkened boarder at the top of the page.

* Multiple classes used on some elements to create customisation between similar pages, such as the tables used on achievements.html and news.html.

* Shuffling images on front page link to bookmarks in news page on associated articles. Bookmark intentionally links a little higher up the page to allow for the menu bar running across the top. This was achieved using CSS on the anchors on news.html to offset their position.
