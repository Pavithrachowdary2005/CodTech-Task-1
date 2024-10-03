Calculator Application Overview

This project is a simple GUI-based calculator application built using Python's `Tkinter` library. The calculator can perform basic arithmetic operations such as addition, subtraction, multiplication, and division, along with the use of parentheses for order of operations. The GUI is designed to resemble a traditional calculator, featuring buttons for numeric input and arithmetic symbols.

Features
1. Basic Arithmetic Operations : The calculator supports addition, subtraction, multiplication, and division.
2. Parentheses : You can use parentheses to enforce the order of operations.
3. Clear Functionality : The calculator includes a "C" button to clear the current input or result.
4. Real-time Display : The calculator shows the input as you press the buttons, and displays the result after performing the calculation.
5. Responsive GUI : The layout is simple and responsive, with a clear display and large, easy-to-use buttons for each operation.

Components
- Display Area : The result and current input are displayed in a large text area at the top of the window.
- Buttons : There are buttons for each digit (0-9), the arithmetic operators (+, -, *, /), and parentheses. There is also an "equals" button for evaluating the entered expression and a "clear" button to reset the input.

How it Works
1. Button Input : When a number or operator is pressed, the corresponding symbol is added to the calculation string, which is displayed in real-time.
2. Evaluation : When the "=" button is pressed, the string is evaluated using Python’s `eval()` function, which computes the result of the expression.
3. Error Handling: If an invalid expression is entered, the calculator will display "error" when evaluated.
4. Clear Button: Pressing the "C" button resets the calculator's input and output, allowing for a fresh calculation.

Requirements
- Python 3.x
- Tkinter (comes pre-installed with standard Python distribution)

Instructions
1. Clone the repository from GitHub.
2. Run the Python file (`calculator.py`) using any Python IDE or from the command line with:
   "bash
   python calculator.py
   "

Future Enhancements
- Implement advanced functions such as square root, exponentiation, and percentage calculation.
- Add keyboard support to allow users to input numbers and operations via keyboard.
- Improve the design for better user experience and add themes or skins for personalization.

This project is a great introduction to building GUI applications with Python and serves as a useful utility for performing basic arithmetic operations.
![ts-1 p](https://github.com/user-attachments/assets/974b7edd-6c71-41a3-a797-680b53956719)
![ts-1 p2](https://github.com/user-attachments/assets/9a1f73b0-4fa0-4e81-ad67-6cd3e0c0cb62)
