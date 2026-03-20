Scientific Calculator (Light/Dark Mode)

Overview

A desktop-based Scientific Calculator built using Python and "tkinter".
It supports basic arithmetic operations along with scientific functions such as trigonometry, logarithms, and square roots.
The application includes a Light/Dark theme toggle for improved usability.

---

Features

- Basic operations: "+", "-", "*", "/"
- Scientific functions:
  - "sin(x)"
  - "cos(x)"
  - "tan(x)"
  - "log(x)" (base 10)
  - "sqrt(x)"
  - Power ("^")
- Parentheses support for complex expressions
- Clear ("C") button
- Real-time expression display
- Light/Dark mode toggle
- Error handling for invalid inputs

---

Tech Stack

- Language: Python 3
- Library: tkinter (built-in GUI library)
- Math Module: math

---

Installation

1. Clone Repository

git clone https://github.com/your-username/scientific-calculator.git
cd scientific-calculator

2. Requirements

No external dependencies required.
"tkinter" comes pre-installed with most Python distributions.

«If tkinter is missing:»

pip install tk

---

Usage

Run the application:

python calculator.py

---

How It Works

- User inputs are captured through button clicks.
- Expressions are built as strings.
- Scientific functions are mapped to Python's "math" module.
- The expression is evaluated using "eval()" after conversion.
- The result is displayed in the entry field.

---

Controls

Button| Function
Numbers (0–9)| Input digits
"+ - * /"| Arithmetic operations
"sin cos tan"| Trigonometric functions
"log"| Logarithm (base 10)
"sqrt"| Square root
"^"| Power
"C"| Clear input
"="| Evaluate expression
Toggle Theme| Switch Light/Dark mode

---

Project Structure

scientific-calculator/
│── calculator.py
│── README.md

---

Future Enhancements

- Degree/Radian mode switch
- Memory functions (M+, M-, MR)
- Keyboard shortcuts
- Graph plotting using matplotlib
- Advanced UI using PyQt or Kivy

---

Limitations

- Uses "eval()", which is not सुरक्षित for untrusted input
- Trigonometric functions use radians only
- Limited UI customization (tkinter-based)

---

License

This project is open-source and available under the MIT License.

