# CAPTCHA Solver Web Page

A simple, single-file web application to demonstrate a CAPTCHA verification process using a provided sample image. The frontend is built with pure HTML, CSS (Tailwind CSS), and JavaScript, offering a responsive and dark-themed user experience.

## Features

*   **Dark Theme:** Light text on a dark background for comfortable viewing.
*   **Responsive Design:** Adapts to various screen sizes using Tailwind CSS.
*   **CAPTCHA Display:** Clearly presents the CAPTCHA image for user input.
*   **User Input:** An input field to type the CAPTCHA text.
*   **Verification Logic:** Client-side JavaScript to simulate CAPTCHA verification (case-insensitive).
*   **Visual Feedback:** Clear success or failure messages after verification attempts.
*   **Interactive Button:** A circular "Verify" button with hover effects.

## How to Run/Test

To get this application up and running, follow these simple steps:

1.  **Save the files:** Ensure that `index.html` and the CAPTCHA image `image.png` are saved in the **same folder**.
2.  **Open in Browser:** Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file or by right-clicking and choosing "Open with" and selecting your browser.

The application will load, displaying the CAPTCHA and an input field.

### Testing the CAPTCHA

*   **Correct Answer:** The correct CAPTCHA text to enter is `V4XBG` (case-insensitive).
*   **Verification:** Type the text into the input field and click the circular "Verify" button. A message indicating success or failure will appear.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS (CDN):** For styling and responsive design.
*   **JavaScript:** For client-side CAPTCHA verification logic and UI interactions.