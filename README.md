# 🧮 Basic Arithmetic Calculator

<div align="center">

![Java](https://img.shields.io/badge/Language-Java-orange)
![Internship](https://img.shields.io/badge/CODTECH-Internship-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

## 👨‍💻 Internship Information

| Category | Details |
| :--- | :--- |
| **Name** | **SUMIT KOLGIRE** |
| **Company** | CODTECH IT SOLUTIONS |
| **Intern ID** | CT12DFT |
| **Domain** | JAVA PROGRAMMING |
| **Duration** | DEC 2024 TO FEB 2025 |
| **Mentor** | NEELA SANTHOSH KUMAR |

---

## 📝 Project Overview

**Project Goal:** Create a Java program that acts as a basic calculator.

This project is a console-based application designed to perform fundamental arithmetic operations. It prompts the user to enter two numbers and select an operation (addition, subtraction, multiplication, or division), then processes the input to display the accurate result.

### 🎯 Objective
To develop a simple, user-friendly Java program that performs basic arithmetic operations based on user input. This project demonstrates the use of Java's control structures and basic arithmetic operators to solve a practical problem.

---

## 🔑 Key Activities

The development process involved the following key stages:

- **📊 Requirement Analysis:** Defined core functionalities (input handling, operation selection) and error handling strategies (e.g., division by zero).
- **🎨 Design:** Created a logical flow for the command-line interface to ensure a user-friendly experience.
- **💻 Implementation:** Utilized Java constructs like `Scanner` for inputs and `switch/if-else` statements for logic control.
- **🧪 Testing:** Verified the program against various inputs, including edge cases like zero input and invalid choices.
- **📄 Documentation:** Commented code for clarity and created user manuals.

---

## 🛠️ Technology Used

* **Programming Language:** Java
* **Input Handling:** `java.util.Scanner`
* **Logic Control:** `Switch-Case`, `If-Else`

---

## 📸 Output Screens

<div align="center">
  <img src="https://github.com/user-attachments/assets/a0816ed7-f25a-4260-ad61-60921fa7d6b9" width="45%" alt="Screenshot 1"/>
  <img src="https://github.com/user-attachments/assets/8e0408bf-ead6-47fd-8243-40e708478693" width="45%" alt="Screenshot 2"/>
</div>
<div align="center">
  <img src="https://github.com/user-attachments/assets/4b2d5163-edb2-4c74-a3b7-78c4bd84a15d" width="60%" alt="Screenshot 3"/>
</div>

---

## 💻 Code Snippet

Here is a glimpse of the core logic used to handle operations:

```java
// Perform the selected operation
switch (choice) {
    case 1:
        result = num1 + num2;
        System.out.println("Result: " + result);
        break;
    case 2:
        result = num1 - num2;
        System.out.println("Result: " + result);
        break;
    // ... Additional cases for Multiplication and Division
    default:
        validChoice = false;
        System.out.println("Invalid choice. Please choose a valid operation.");
}
