
# **ESD Calculator**

## **Overview**
The ESD Calculator is a GUI-based calculator application built using Python's `tkinter` library. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator also supports keyboard shortcuts for ease of use and a fun feature to change the display color randomly.

---

## **Features**
- **Basic Arithmetic Operations**: Supports addition, subtraction, multiplication, division, and decimal numbers.
- **Dynamic Color Change**: A button to randomly change the display color.
- **Keyboard Shortcuts**: Perform calculations using the keyboard for a smoother experience.
- **Error Handling**: Prevents invalid inputs such as multiple consecutive decimal points or operators.
- **Backspace Functionality**: Use the "correct" button or the Backspace key to remove the last character.

---

## **Installation**
1. Ensure you have Python installed on your system (version 3.6 or later).
2. Install the `tkinter` library (usually included with Python).
3. Download or clone this repository to your local machine.
4. Save a suitable calculator icon file as `calculator.ico` in the project directory.

---

## **Usage**
1. Run the script:
   ```bash
   python calculator.py
   ```
2. Use the calculator's GUI to:
   - Click buttons for inputs.
   - Press `=` or Enter to evaluate expressions.
   - Press `C` to clear the display.
   - Use the `?` button to change the display color.
3. Utilize keyboard shortcuts:
   - Numeric keys (0–9): Enter numbers.
   - Operators (+, -, *, /): Perform operations.
   - Backspace: Remove the last character.
   - Enter: Evaluate the expression.
   - `c`: Clear the display.
   - `q`: Quit the application.

---

## **File Structure**
- **`calculator.py`**: The main script containing the GUI and logic.
- **`calculator.ico`**: Icon file for the application.

---

## **Code Explanation**
### **Core Components**
1. **GUI**:
   - Built with `tkinter` widgets such as `Label` (for the display) and `Button` (for inputs).
   - Grid layout is used for arranging buttons.

2. **Logic**:
   - The `attach_numbers` function processes button presses and updates the display.
   - Keyboard shortcuts are mapped using the `bind` method.

3. **Random Color Feature**:
   - The `change_color` function randomly selects a color for the display text.

---

## **Contributing**
If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with detailed information.

---

## **Acknowledgments**
- Built with Python and the `tkinter` library.
- Inspired by basic calculator functionality with added features for user interaction.
