# Basic Calculator

This is a simple web-based calculator built using HTML, CSS, and JavaScript. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Live Demo

(https://susmitha-eluri.github.io/basic_calculator/)

## Features

- Performs basic arithmetic operations: `+`, `-`, `*`, `/`
- Supports decimal numbers
- Clear (C) button to reset the display
- Displays "Error" for invalid expressions
- Responsive layout for use on desktop and mobile devices

## How to Use

1. Click on the number and operator buttons to build an expression.
2. Press `=` to calculate the result.
3. Press `C` to clear the display and start a new calculation.

## How It Works

- **HTML** provides the structure using a table layout.
- **CSS** styles the calculator, including button appearance and layout.
- **JavaScript** handles user interaction:
  - `appendValue(val)`: adds the clicked button’s value to the display.
  - `calculate()`: evaluates the expression using `eval()`, with error handling.
  - `clearDisplay()`: resets the display to empty.

## Testing

The calculator has been tested with the following expressions:

| Input Expression | Expected Output |

| 7 + 3            | 10              |
| 12 / 4           | 3               |
| 6 * 2 - 1        | 11              |
| 5 - 9            | -4              |
| 10 / 0           | Infinity        |
| 2..5 + 1         | Error           |


