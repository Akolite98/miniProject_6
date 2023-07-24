# Event Listeners

This is a mini project showcasing the implementation of event listeners using HTML, CSS, and JavaScript. The web application allows users to create three input elements and dynamically change the background color, text color, and font size of the page as they type in the input fields.

## Getting Started

To experience the Event Listeners mini project, simply open the provided HTML file named `index.html` in your web browser. The application doesn't require any additional setup or installation and should work on modern web browsers.

## How to Use

1. Open the `index.html` file in your web browser.

2. The web page will display a heading "Mini Project #5: Event Listeners" and two list items describing the functionality.

3. Below the list, there are three input fields labeled "Background Color," "Text Color," and "Font Size."

4. As you type in each input field, the page will dynamically update according to the changes made.

5. In the "Background Color" input, type a valid CSS color value (e.g., "red," "#FF5733," "rgb(255, 99, 71)") to change the background color of the page.

6. In the "Text Color" input, type a valid CSS color value to change the text color of the page.

7. In the "Font Size" input, type a numeric value (e.g., 16, 24, 36) to change the font size of the entire page.

8. Observe the page's appearance change in real-time based on the input values.

## Code Details

The implementation uses HTML, CSS, and JavaScript to create a simple interactive web page.

### HTML and CSS

The HTML file provides the structure of the web page, including the heading and list items explaining the functionality of the mini project. Additionally, it defines three input elements for background color, text color, and font size changes.

The CSS styles the elements using Bootstrap for responsiveness and a clean layout. It also includes custom styles for the input fields and ensures proper alignment.

### JavaScript Logic

The JavaScript code inside the `<script>` tag defines three event listeners, one for each input element.

- `bgColor.addEventListener()`: This event listener listens for the "keyup" event on the "Background Color" input. When the user types in a color value, the page's background color is updated accordingly using `body.style.backgroundColor`.

- `textColor.addEventListener()`: This event listener listens for the "keyup" event on the "Text Color" input. When the user types in a color value, the page's text color is updated using `body.style.color`.

- `fontSize.addEventListener()`: This event listener listens for the "keyup" event on the "Font Size" input. When the user types in a numeric value, the font size of the entire page is updated using `body.style.fontSize`.

The event listeners ensure that the changes take effect in real-time as the user types in the input fields, providing an interactive and responsive user experience.
