# 03 - Developer tools

Every modern web browser includes a powerful suite of developer tools. These tools do a range of things, from inspecting currently-loaded HTML, CSS and JavaScript to showing which assets the page has requested and how long they took to load.

- :books: Documentation

  - [Chrome Dev Tools - DOM](https://developer.chrome.com/docs/devtools/dom/)

  - [Chrome Dev Tools - Change styles](https://developer.chrome.com/docs/devtools/css/)

  - [Chrome Dev Tools - Network](https://developer.chrome.com/docs/devtools/network/)

* :link: Links

  - [Using the styles panel](https://www.sitepoint.com/css-debugging-and-optimization-browser-based-developer-tools/)

  - [Computed styles](https://support.google.com/webdesigner/answer/9008244?hl=en-GB)

* :headphones: Screencasts

  - [Inspect elements](https://egghead.io/lessons/misc-chrome-devtools-elements-inspect-elements-vs-view-source)

  - [Make changes in your browser](https://egghead.io/lessons/misc-chrome-devtools-elements-make-changes-in-your-browser)

- :fast_forward: Next Lesson

  - [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Browser Differences

The exercises are using Chromium/Chrome but there are developer inspectors in all browsers.

| Browser        |           Setting            |
| -------------- | :--------------------------: |
| Microsoft Edge |   Tools > Developer Tools    |
| Firefox        |    Tools > Browser Tools     |
| Chrome/Brave   |       View > Developer       |
| Safari         | Develop > Show Web Inspector |

## Exercises

1. In this class we are looking at the hidden gems of the Developer Tools! I promise, it will make your life a lot easier. For these exercises you'll need everything in the [resources](./resources/) folder. Copy the content (index.html, style.css and images folder) to a new folder on your computer and open up the page in your browser.

2. Right click the web page and select `Inspect`. A keyboard shortcut is <kbd>CMD</kbd> + <kbd>Option/Alt</kbd> + <kbd>I</kbd> (on a Mac) or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>J</kbd> (on Windows). This will open up the developer tools inspector panel.

3. You have probably noticed that the CSS isn't loaded properly. Figure out why by using the Network tab and later fix the error in the HTML file.

4. There's also an image which isn't rendered correctly. Figure out why using either the Document tree view in the Elements tab, or the Network tab. Fix the error once you've found it.

5. Go to the `Elements` tab where you can find the HTML document. Try deleting the `h1` element by either right clicking it and pressing `Delete element` or marking one and pressing the `delete` button. Did you notice how it disappeared? (But don't worry, it will be back if you refresh the page)

6. Refresh the page and, instead of deleting, drag the `h1` so it's below the `<p>` tag.

7. Update the text in the `h2` tag to something more suitable.

8. Did you notice the hover effect on the images? Force this effect to be permanent by right clicking any `.season` element and press `Force state -> Hover`. This is great for testing when you don't want to keep hovering to see the result.

9. Classes can also be manipulated. Try adding a `.faded` class to an `.season` by double clicking the element's classes and typing a new class.

10. The Styles section is great for debugging and testing your CSS. Below the `Elements` tab in developer tool you can find the `Styles` section. Try changing the background color on `body` using the color picker and try adding a font color to `h3`.

11. The H1 on the page is using a REM value to set its font size. Can you find out what that translates to in pixels by using the [Computed Styles](https://css-tricks.com/computed-values-more-than-meets-the-eye/) section in Developer tools?

12. **Extra:** The creator of the page is specified in the footer, but unfortunately the text isn't wrapped in a `<p>` tag. Use the Developer Tools and edit the footer contents so the text inside the footer is wrapped within a `<p>`.

    > Note: The `<footer>` element should not change.

13. **Extra:** One nice thing is that we can change the [transition easing](https://cssreference.io/property/transition/) with a built in tool. Press an `.season` element and look at its styles. Press the small curve icon next to `transition: 0.2 ease` and play around with the curve. Try to hover an season image to see how the easing changes depending on your settings. If it's hard to see the effects, try increasing the transition time (`0.2`) right there in the dev tools.
