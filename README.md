# Simple  Calculator 

A dynamic and customizable calculator application built with **HTML**, **CSS**, and **JavaScript**. This project showcases advanced web development techniques to deliver an intuitive and responsive user experience.

---

## Key Highlights

### Interactive Features

- **Arithmetic Operations**: Perform addition, subtraction, multiplication, and division seamlessly.
- **Theme Customization**: Switch between three distinct themes for personalized aesthetics.
- **State Management**:
  - Clear all inputs with the `RESET` button.
  - Erase the last digit using the `DEL` button.
  - Track calculations with live display of previous and current operands.
- **Responsive Design**: Ensures optimal functionality across devices and screen sizes.

---

## Project Directory Overview

```
calculator-project/
|-- index.html        # Core structure of the application
|-- css/
|   |-- styles.css    # Default styles
|   |-- theme1.css    # Theme 1 styles
|   |-- theme2.css    # Theme 2 styles
|   |-- theme3.css    # Theme 3 styles
|-- index.js          # Application logic and interactivity
```

---

## Quick Start Guide

### Prerequisites

- A modern web browser is the only requirement to run this project.

### Steps to Use

1. **Setup**:
   - Clone this repository or download the project files.
   - Open `index.html` in your browser.

2. **Usage**:
   - Enter numbers using the numeric buttons.
   - Choose an operator to perform calculations.
   - Press `=` to view results.
   - Use `DEL` to delete the last digit, or `RESET` to clear all inputs.
   - Toggle themes using the radio buttons.

---

## Code and Functionality Breakdown

### HTML

Defines the structural components of the calculator, including input fields, buttons, and theme toggles.

### CSS

Applies:

- Visual styling for all components.
- Theming capabilities through pre-defined color variables.
- Responsive design for enhanced usability across devices.

### JavaScript

Handles:

- **Dynamic Theme Switching**: Radio buttons trigger theme changes by dynamically linking appropriate CSS files.
- **Calculation Logic**: Processes input, executes arithmetic operations, and updates the display in real time.
- **Interactive Buttons**:
  - `DEL`: Deletes the last character in the current operand.
  - `RESET`: Clears all stored values and resets the calculator state.
  - `=`: Computes and displays the result of operations.

---

## How It Works

### 1. Theme Customization

Users can toggle between three predefined themes by interacting with the radio buttons. JavaScript dynamically updates the active stylesheet to reflect the selected theme.

### 2. Calculation Flow

1. Users input numbers and choose operators.
2. JavaScript evaluates and processes inputs.
3. The `=` button triggers calculation logic, displaying the result dynamically.

### 3. State Management

- Real-time display updates ensure clarity.
- Previous and current operands are displayed to guide the user.

---

## Screenshots (Optional)

Add screenshots showcasing:

- Default layout and design.
- Theming options in action.
- Functional operations like addition or deletion.

---

## Future Enhancements

- Implement advanced calculations (e.g., percentages, exponents).
- Add voice-input capabilities for accessibility.
- Optimize performance for larger datasets or extended operations.

---

## License

This project is released under the [MIT License](LICENSE). Contributions and forks are welcome!

---

Start exploring the Calculator Project and customize it to your needs!
