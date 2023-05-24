# Online Calculator

This is a simple online calculator implemented using HTML, CSS, and JavaScript. It provides basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator has a user-friendly interface and allows users to perform calculations easily.

## Features

- Addition: Use the "+" button to add numbers.
- Subtraction: Use the "-" button to subtract numbers.
- Multiplication: Use the "*" button to multiply numbers.
- Division: Use the "/" button to divide numbers.
- Clear: Click on the "CLEAR" button to clear the calculator display.
- Delete: Click on the "DELETE" button to remove the last entered character.
- Result: Click on the "=" button to calculate and display the result.

## Usage

1. Open the HTML file in a web browser.
2. The calculator interface will be displayed.
3. Enter numbers and perform calculations by clicking the respective buttons.
4. The result will be displayed in the text area.

## Styling

The calculator interface is styled using CSS to provide an attractive and user-friendly appearance. The main container has a background color, border, padding, and box shadow to create a visually appealing design. Buttons are styled with different colors and sizes to distinguish between operators and numeric values.

## Scripting

JavaScript is used to handle user interactions and perform calculations. The script defines several functions:

- `insert(num)`: This function is called when a button is clicked, and it appends the clicked number or operator to the calculator display. It also handles special cases such as preventing consecutive operators or exceeding the display limit.
- `equal()`: This function is called when the "=" button is clicked, and it evaluates the expression entered in the calculator display using the `eval()` function and displays the result.
- `clean()`: This function is called when the "CLEAR" button is clicked, and it clears the calculator display.
- `back()`: This function is called when the "DELETE" button is clicked, and it removes the last entered character from the calculator display.

## Limitations

- The calculator supports a maximum of 30 characters in the display.
- Division by zero or other mathematical errors are not handled explicitly.
- Scientific notation or advanced mathematical functions are not supported.

Feel free to explore and modify the code to enhance the calculator's functionality according to your requirements.
