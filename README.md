# Selenium XPath Mastery Suite 🧪🤖

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/Selenium-4.x-green.svg)](https://www.selenium.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A comprehensive, production-ready Python automation script built using **Selenium WebDriver**. This repository demonstrates **20 distinct test cases (TC01–TC20)** covering basic locators, advanced XPath functions, complex logical operators, **XPath Axes**, form interactions, explicit waits, and a complete end-to-end user journey on the official Selenium test web form.

---

## 🚀 Key Features & Concepts Demonstrated

*   **Attribute-Based Locators:** Locating elements by exact attributes (`@name`, `@type`).
*   **Dynamic Matching Functions:** Utilizing `contains()`, `starts-with()`, and text-based lookup (`text()`).
*   **Compound Logical Conditions:** Combining criteria using `and` and `or` operators.
*   **XPath Axes Navigation:** Traversing the DOM hierarchy using `parent`, `ancestor`, `descendant`, and `following`.
*   **Index-Based Selection:** Handling element collections using positional indexing `(//input)[2]`.
*   **Form Controls Handling:** Interacting with text inputs, textareas, checkboxes, radio buttons, and `<select>` dropdowns.
*   **Robust Synchronization:** Implementing `WebDriverWait` with Expected Conditions (`element_to_be_clickable`, `visibility_of_element_located`) to prevent flaky tests.
*   **End-to-End Workflow:** Executing a complete multi-field submission and validation sequence (TC20).

---

## 🛠️ Prerequisites

Ensure you have the following installed on your local machine:
*   **Python** (v3.8 or higher)
*   **Google Chrome** browser
*   **ChromeDriver** (automatically managed by Selenium 4.6+, or compatible with your installed Chrome version)

---

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
