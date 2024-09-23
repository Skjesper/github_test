# 04 - Flexbox

The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities.

- :scissors: Examples

  - [`base.html`](examples/base.html)

  - [`justify.html`](examples/justify.html)

* :books: Documentation

  - [Basic concepts](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)

  - [Flexbox CSS references](https://cssreference.io/flexbox/)

- :link: Links

  - [A complete guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

  - [How flexbox works](https://www.freecodecamp.org/news/an-animated-guide-to-flexbox-d280cf6afc35/)

- :headphones: Videos

  - [What The Flexbox?!](https://www.youtube.com/playlist?list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid)

  - [Learn FlexBox - Scrimba](https://scrimba.com/g/gflexbox)

## Exercises

1. [Help the frogs](https://flexboxfroggy.com/) to the lily pads using flexbox. These are great exercises to get familiar with how to align items with flexbox.

2. Create a new HTML document and add a `<div>` element with the width and height of 200px and make it green. Position the `<div>` element exactly in center of the viewport (browser window) both vertically and horizontally **with Flexbox**.

3. Create a new HTML document and add a `<nav>` with three `<a>` tags inside. The navigation bar should have a `100%` width and a `#000` background color. Each `a` should be evenly distributed inside the navigation using the `justify-content` property.

4. Continue working on the HTML document from the previous exercise. Add a grid container using a `<section>` tag. Add ten `<div>` elements inside the `<section>` element. Turn it into a grid using flexbox!

   > Note: Don't forget to use `flex-wrap` to make it flow over rows.

5. **Extra:** Remember in [02 - Cascading Style Sheets](../02%20-%20Cascading%20Style%20Sheets/README.md) when we applied bottom margin to our list items, **except** for the last item? We could target the last item with the pseudo selector `:last-child`, but with Flexbox there is another way to style the gap between sibling items. See if you can rewrite the CSS for the list using `flex` and the `gap` property.

6. **Extra:** Create a new HTML document and recreate [this](https://user-images.githubusercontent.com/9930179/90753622-1f5a1780-e2d9-11ea-8dc3-2db9859eedfb.png) wireframed sidebar module **using flexbox**.

7. **Extra:** Try to build a landing page based on this [this](https://user-images.githubusercontent.com/9930179/64235436-a8c1df80-cef8-11e9-8eb3-531762f8d8ca.png) design structure **using flexbox!**

   **Site breakdown:**

   - A top menu section with links and a logo
   - Three text columns with different font sizes and content
   - One full width image in the bottom

   You are allowed to choose your own colors, fonts and images.

8. **Extra:** Another game! Your job is to stop the incoming enemies from getting past your defenses. Unlike other tower defense games, [you must position your towers using CSS!](http://flexboxdefense.com)
