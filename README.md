# Simple Link Popup Example

This repository contains a simple HTML, CSS, and JavaScript example that demonstrates how to open a user-entered link in a new popup window.

## Overview

This project provides a basic web page with:

* An input field where users can enter a URL.
* A button that, when clicked, opens the entered URL in a new popup window.
* Basic validation to ensure the entered link starts with `http://` or `https://`.
* Clear the input field after opening the popup.

**Key Features:**

* **User Input:** Allows users to enter any valid URL.
* **Popup Window:** Opens the entered link in a new browser window.
* **Basic Validation:** Checks if the link starts with `http://` or `https://`.
* **Clear Input:** Clears the input field after the popup is opened.
* **Responsive:** The page is responsive and adapts to different screen sizes.
* **Correct Character Encoding:** The page uses UTF-8 character encoding.

**Limitations:**

* **Address Bar:** Due to modern browser security restrictions, it's **not possible** to reliably hide the address bar in popup windows.
* **Basic Functionality:** This is a very simple example and does not include advanced features like error handling, more complex validation, or custom popup styling.

## Getting Started

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
    ```

    (Replace `YOUR-USERNAME` and `YOUR-REPOSITORY-NAME` with your actual GitHub username and repository name.)

2. **Open `index.html`:**
    Open the `index.html` file in your web browser.

3. **Enter a Link:**
    Type a valid URL (e.g., `https://www.google.com`) into the input field.

4. **Open in Popup:**
    Click the "Open in Popup" button. The entered link will open in a new popup window.

## Code Structure

* **`index.html`:**
  * Contains the HTML structure for the input field, button, and the JavaScript code.
  * Includes basic CSS styling.
  * Includes the meta tags for `charset` and `viewport`.

## Technologies Used

* **HTML5:** For the page structure.
* **CSS3:** For basic styling.
* **JavaScript:** For handling user input, validation, and opening the popup window.

## Customization

* **Styling:** Modify the CSS in the `<style>` tags within `index.html` to change the appearance of the input field and button.
* **Popup Features:** Adjust the `width`, `height`, `resizable`, and `scrollbars` options in the `window.open()` function in the JavaScript code to change the popup window's properties.
* **Validation:** You can add more validation rules in the javascript code.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details. (If you want to use a different license, change this accordingly and add a LICENSE file.)
