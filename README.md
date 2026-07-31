# Week 4 Assignment: Password Validator

**Institution:** North Seattle College  
**Term:** Summer 2026  
**Author:** Harry Lampert Martinez  

## Project Overview
An interactive, real-time password strength checker and confirmation validator built with vanilla JavaScript, HTML, and CSS. This project was completed as coursework to demonstrate proficiency in Document Object Model (DOM) manipulation, event handling, and conditional logic. 

## Features
*   **Real-Time Validation:** Uses `input` event listeners to evaluate password strength on every keystroke.
*   **Dynamic Visual Feedback:** Updates a strength meter (progress bar) and a requirements checklist (✓ and ✖) dynamically based on user input.
*   **Algorithmic Checks:** Evaluates strings for minimum length, numeric characters, and specific special characters using standard loops and string methods (no RegEx).
*   **Match Confirmation:** Strictly compares the primary password against a confirmation field, including edge-case handling to prevent false-positive matches on empty strings.

## Technologies Used
*   HTML5
*   CSS3
*   JavaScript (ES6+)

## Setup and Usage
1. Clone this repository to your local machine.
2. Open the `password-validator.html` file in any modern web browser.
3. Type in the **Password** field to see the strength meter and checklist update in real-time.
4. Type in the **Confirm Password** field to test the strict matching logic.
