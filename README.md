Overview

This program is a functional calculator built using HTML, CSS, and JavaScript. It provides both button-based and keyboard-based input functionality. The calculator allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

Features

Arithmetic Operations: Supports addition (+), subtraction (-), multiplication (*), and division (/).

Clear Screen: Clear the input field using the "C" button or the Escape key.

Keyboard Input: Users can interact with the calculator using keyboard keys for numbers, operators, Enter (to calculate), and Backspace (to delete the last character).

Stylized Interface:

A background image adds aesthetic value.

Buttons are styled with a black background and white text for better visibility.

Error Handling: Displays "Error" for invalid inputs.

How to Use

Button Input:

Click the numeric and operator buttons to form an expression.

Click the = button to calculate the result.

Use the C button to clear the screen.

Keyboard Input:

Use number keys (0-9) and operator keys (+, -, *, /) to form an expression.

Press Enter to calculate the result.

Press Backspace to delete the last character.

Press Escape to clear the screen.

Code Structure

HTML:

Defines the structure of the calculator including the input field and buttons.

A table is used to arrange the buttons in a grid format.

CSS:

Styles the calculator for better appearance.

Adds a background image and customizes button colors.

JavaScript:

Handles the functionality of the calculator.

Includes functions for clearing the screen, appending input, evaluating expressions, and managing keyboard input.

Keyboard Shortcuts

Key

Function

0-9

Input numbers

+, -, *, /

Input operators

.

Input decimal point

Enter

Calculate the result

Backspace

Delete the last input

Escape

Clear the screen

Notes

The eval() function is used to evaluate expressions. While it is effective for this simple calculator, avoid using eval() in larger projects as it can introduce security risks.

Ensure that the image file calculator.jpg is in the same directory as this HTML file for the background image to display properly.

Future Improvements

Add support for parentheses ((, )).

Implement advanced mathematical functions like square root, exponentiation, etc.

Enhance error handling to provide more descriptive messages.

Optimize the layout for responsiveness on different devices.

Setup Instructions

Save the provided code in an index.html file.

Place the calculator.jpg file in the same directory.

Open the index.html file in any modern web browser.

License

This program is free to use for educational and personal purposes.

Author

G Darshankumar

MERN Stack Student, Pentagonspace
