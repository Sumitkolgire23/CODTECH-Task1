# 🧮 Basic Arithmetic Calculator

![Java](https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=java)
![IDE](https://img.shields.io/badge/IDE-IntelliJ%20%7C%20Eclipse%20%7C%20VS%20Code-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 👨‍💻 Internship Details

| **Category** | **Details** |
|:---:|:---|
| **Name** | SUMIT KOLGIRE |
| **Company** | CODTECH IT SOLUTIONS |
| **ID** | CT12DFT |
| **Domain** | JAVA PROGRAMMING |
| **Duration** | DEC 2024 - FEB 2025 |
| **Mentor** | NEELA SANTHOSH KUMAR |

---

## 📝 Overview

This project is a **robust, console-based calculator application** developed using Java. It is designed to perform fundamental arithmetic operations with precision and error handling.

The primary objective was to develop a simple, user-friendly program that demonstrates the use of Java's control structures (such as `switch` statements) and input handling via the `Scanner` class to solve practical mathematical problems.

---

## 🚀 Key Features

* **User-Friendly Interface:** Clear menu-driven prompts for easy navigation.
* **Arithmetic Operations:** Supports Addition (+), Subtraction (-), Multiplication (*), and Division (/).
* **Error Handling:** Includes specific logic to prevent "Division by Zero" crashes.
* **Input Validation:** Ensures the calculator processes floating-point numbers (`double`) for higher accuracy.

---

## 🛠️ Technologies Used

* **Programming Language:** Java (JDK 8+)
* **Core Logic:** `java.util.Scanner` for Input/Output operations.
* **Concepts:** Control Flow (`if-else`, `switch-case`), Exception Handling mechanisms.

---

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/a0816ed7-f25a-4260-ad61-60921fa7d6b9" alt="Input Screen" width="45%">
  <img src="https://github.com/user-attachments/assets/8e0408bf-ead6-47fd-8243-40e708478693" alt="Operation Menu" width="45%">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4b2d5163-edb2-4c74-a3b7-78c4bd84a15d" alt="Result Output" width="80%">
</p>

---

## 💻 Code Structure

The core logic is contained within the `BasicCalculator` class. Here is a snippet of the operation handling:

```java
// Logic for selecting operations
switch (choice) {
    case 1:
        result = num1 + num2;
        System.out.println("Result: " + result);
        break;
    case 2:
        result = num1 - num2;
        System.out.println("Result: " + result);
        break;
    // ... additional cases
    case 4:
        if (num2 != 0) {
            result = num1 / num2;
            System.out.println("Result: " + result);
        } else {
            System.out.println("Error: Division by zero is not allowed.");
        }
        break;
}
