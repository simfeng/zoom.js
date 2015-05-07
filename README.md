# ZOOM.JS

A simple jQuery plugin for image zooming; as seen on [Medium](https://medium.com/designing-medium/image-zoom-on-medium-24d146fc0c20).

### Demo
https://fat.github.io/zoom.js

### How

1. Link the zoom.js and zoom.css files to your site or application.

  ```html
  <link href="css/zoom.css" rel="stylesheet">
  <script src="js/zoom.js"></script>
  ```

2. zoom.js is dependent on [transition.js file](https://raw.github.com/twbs/bootstrap/master/js/transition.js) from Bootstrap, so make sure to include that as well.

  ```html
  <script src="js/transition.js"></script>
  ```

3. Add a `data-action="zoom"` attribute to the images you want to make zoomable. For example:

  ```html
  <img src="img/blog_post_featured.png" data-action="zoom">
  ```


### Why

It's the best way to zoom an image. It transitions/zooms in really smoothly, and then when you're done, scrolls away, [esc] keys away, clicks away… clean af.

Also, now if you hold your meta key (`⌘`), it will open in a new tab. wow.


### Where

zoom.js should (in theory) work in all relevant browsers. If not, create an issue! Thanks!


### Who

Written by @fat, made better by you.