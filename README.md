# 🐍 Python Basics Demonstration

This repository features a simple Python script designed to demonstrate fundamental programming concepts, including control flow, data structures, and basic input/output operations.

---

## 🎯 Project Goal

The primary goal of this project is to simulate a simple user interaction for managing adventure supplies, demonstrating the following core Python concepts:

| Concept | Python Element |
| :--- | :--- |
| **Data Structure** | `dictionary` |
| **Control Flow** | `while` loop, `if/else` statement |
| **Logic** | **Comparison Operators** (`>=`, `<`, `==`) |
| **User Interaction** | `input()` function |
| **Data Handling** | **Type Conversion** (`int()`) |
| **Output** | `print()` function |
| **Text Formatting** | **Escape Characters** (`\n`, `\t`) |

---

## ⚙️ Concept Breakdown

### 1. Variables and Dictionary

* **Variables:** Used to store dynamic data like the user's name (`user_name`) and fixed limits (`MAX_POTIONS`).
* **Dictionary:** The `inventory` object uses **key-value pairs** (e.g., `"potions": 5`) to logically manage related data.

### 2. Input, Conversion, and Print

* **`input()` function:** Collects text (string) data from the user.
* **Conversion:** The `int()` function is used for **type conversion** to safely turn the user's string input into an integer so that arithmetic operations can be performed (e.g., subtracting gold).
* **`print()` function:** Displays all output, including formatted strings using f-strings.

### 3. While Loop and If/Else

* **`while` loop:** Controls the purchasing process, repeating as long as the inventory is not full.
* **`if` statement:** Checks for conditions, such as whether the user has enough gold to buy a potion, dictating the program's flow.

### 4. Comparison Operators

These operators are essential for control flow:

* `>=` (Greater than or equal to): Checks purchase eligibility.
* `<` (Less than): Used to maintain the `while` loop condition.
* `==` (Equal to): Used to determine the final status message (full vs. not full).

### 5. Escape Characters

Special characters used inside strings for formatting:

* `\n`: Creates a **new line**.
* `\t`: Creates a **tab stop** (indentation).
