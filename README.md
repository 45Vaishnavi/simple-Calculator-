# simple-Calculator-A# 🧮 Simple C++ Calculator

A **console-based C++ calculator** application that performs basic arithmetic operations using user-input equations. It continuously takes expressions in the format `number operator number` and displays results until the user types `exit`.

---

## 📘 Instructions

- Input expressions like: `10 + 5`, `8 * 3`, `6 / 2`, `12 - 4`
- Type `exit` or `EXIT` to end the application
- Avoid using brackets `()`, `[]`, or complex expressions
- Input is **case sensitive**, and any malformed input may cause incorrect behavior

---

## ➗ Supported Operations

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)

---

## 💻 How to Run

### Compile using g++

```bash
g++ calculator.cpp -o calculator
./calculator
```

⚠️ This application uses `system("CLS")`, so works best on **Windows**.

---

## 💡 Example

```
Enter the equation :- 10 + 5
The ans of the Eq is : 10 + 5 = 15
```

---

## 🔄 Features

- **Looping behavior** until `exit` is typed
- Uses `stringstream` to parse input
- Handles division by zero errors gracefully
- Clean terminal interface with instructions and output

---

## 🚧 To Improve

- Add support for floating-point precision formatting
- Extend to handle brackets and operator precedence
- Add error messages for invalid input (e.g., missing operands or extra characters)
- Support keyboard shortcuts or GUI version

---

## ✍️ Author

Developed with ❤️ by Vaishnavi      
C++ Beginner Project | CLI Calculator Enthusiast

---
