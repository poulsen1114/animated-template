# Animated Template

This project is an animated template that demonstrates a web page with a collapsible navigation bar and scroll animations.

## Description

The project includes an `index.html` file along with two JavaScript files (`navbar.js` and `script.js`) and a CSS file (`styles.css`).

The `index.html` file provides the basic structure of the web page, including a `<head>` section and a `<body>` section. The `<head>` section includes `<meta>` tags for character encoding and viewport configuration, a link to the external CSS file (`styles.css`), and embedded JavaScript code.

The `navbar.js` file contains a JavaScript function called `toggleNavbar(collapseID)`, which is responsible for toggling the visibility of a collapsible menu. It achieves this by adding or removing the CSS classes `"hidden"` and `"block"` from the specified element.

The `script.js` file initializes the AOS (Animate On Scroll) library, which enables scroll animations for elements on the page. It configures various options such as delay, duration, once, and mirror to control the animation behavior.

## Usage

To use this animated template, follow these steps:

1. Download or clone the repository to your local machine.

2. Open the `index.html` file in a web browser.

3. Explore the web page and interact with the collapsible navigation bar. Try clicking on the menu icon to toggle the visibility of the menu.

4. Scroll through the page to see the scroll animations in action.

## Dependencies

This project relies on the following dependencies:

- AOS library: The AOS library is included via a link to an external JavaScript file (`https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js`). This library provides the scroll animation functionality.

## License

This project is licensed under the [MIT License](LICENSE).
