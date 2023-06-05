# Calculator with Neumorphism

This is a simple calculator project implemented using JavaScript. It allows users to perform basic arithmetic calculations such as addition, subtraction, multiplication, and division.

## Features

- **Inputting Digits**: Users can input digits by clicking on the corresponding buttons. The calculator displays the entered digits on the screen.

- **Decimal Point**: Users can input decimal numbers by clicking on the decimal point button. The calculator ensures that only one decimal point can be entered for each number.

- **Operators**: Users can perform calculations by clicking on operator buttons (+, -, *, /). The calculator supports consecutive calculations and updates the result accordingly.

- **Clearing**: The calculator provides an all-clear (AC) button to reset the calculator to its initial state.

## Usage

To use the calculator, follow these steps:

1. Load the HTML document containing the calculator.
2. The calculator screen will display "0" initially.
3. Click on the digit buttons to enter the desired numbers.
4. Click on the decimal point button to add a decimal point if needed.
5. Click on an operator button (+, -, *, /) to perform calculations.
6. Continue entering numbers and operators to perform consecutive calculations.
7. Click on the all-clear (AC) button to reset the calculator.

## Code Structure

The calculator project consists of the following components:

- **Calculator Object**: This object keeps track of the calculator's current state, including the display value, first operand, second operand wait flag, and operator.

- **Input_Digit Function**: This function handles digit input and updates the display value accordingly.

- **Input_Decimal Function**: This function handles decimal point input and ensures that only one decimal point is added to a number.

- **Handle_Operator Function**: This function handles operator input and performs calculations based on the current state of the calculator.

- **Perform_Calculation Object**: This object contains functions for performing various arithmetic calculations (division, multiplication, addition, subtraction, and equality).

- **Calculator_Reset Function**: This function resets the calculator to its initial state.

- **Update_Display Function**: This function updates the calculator screen with the current display value.

- **Event Listeners**: The code includes event listeners to capture button clicks and trigger the corresponding actions.

## Dependencies

This calculator project requires the following:

- JavaScript: The calculator logic is implemented using JavaScript.

- HTML: The calculator interface is created using HTML elements.

- CSS: The calculator styling is implemented using CSS.

## Getting Started

To use this calculator project, follow these steps:

1. Include the HTML code for the calculator interface in your HTML document.
2. Add the JavaScript code provided in this README to handle the calculator's functionality.
3. Style the calculator using CSS or use the provided CSS code for basic styling.

## Contributions

Contributions to this calculator project are welcome. If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue.

## License

This calculator project is open-source and is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the code.
