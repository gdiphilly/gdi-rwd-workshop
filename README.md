# Responsive Web Design

This is the Girl Develop It Responsive Web Design course. Materials by Catherine Farman, based on material by Sophie Shepherd.

The course is meant to be taught in 1 five-hour workshop. Each of the slides and practice files are customizable according to the needs of a given class or audience.

## Class Goals

### Goal 1
Create a page that changes when you resize the browser viewport, and that fits on a mobile device screen.

### Goal 2
Add media queries to optimize our layout for different screen sizes - making a mobile-first website!

### Goal 3
Learn best practices in responsive design and how to optimize our site design for small screens and mobile devices.

### Goal 4
Build a responsive navigation menu that toggles open on small screens, with CSS and jQuery.


## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});
```
