# CAPTCHA Solver Demo

This project provides a simple, single-page web application demonstrating a client-side CAPTCHA solver. It's designed to be a functional proof-of-concept, allowing users to input text from an image CAPTCHA and validate it.

## Features

- **Dynamic Image Loading**: Displays a CAPTCHA image from a URL parameter (`?url=https://.../image.png`) or defaults to a local `sample.png`.
- **User Input**: An input field for users to type the characters they see in the CAPTCHA image.
- **Client-Side Validation**: Compares the user's input against a hardcoded correct answer for the provided `sample.png` (or a known CAPTCHA if a URL is used).
- **Responsive Design**: Built with Tailwind CSS for a modern and mobile-friendly interface.
- **Immediate Feedback**: Provides instant success or failure messages upon submission.

## Usage

1.  **Open `index.html` in your browser.**
2.  The application will automatically load `sample.png` as the default CAPTCHA image.
3.  To test with a different image, append a `?url=` parameter to your browser's address bar. For example:
    `file:///path/to/your/index.html?url=https://example.com/some-captcha.png`
4.  Type the characters you see in the image into the input field.
5.  Click the "Solve" button or press Enter to submit your answer.
6.  The correct answer for the default `sample.png` is `ADORS` (case-insensitive).
7.  Click "Refresh CAPTCHA" to clear the input and message.

## Setup

This project is a single HTML file and requires no complex setup. Simply download `index.html`, `README.md`, `LICENSE`, and `sample.png` into the same directory. 

## Technologies Used

-   **HTML5**: For the basic page structure.
-   **Tailwind CSS**: For styling and responsive design (via CDN).
-   **JavaScript**: For dynamic content, URL parameter handling, and CAPTCHA validation logic.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.