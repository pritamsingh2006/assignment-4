# Calculator Project Documentation

## 1. Project Overview
**Project Name:** Simple Console Calculator
**Description:**
This project is a command-line interface (CLI) based calculator application developed to perform fundamental arithmetic operations. The primary goal of this project was not only to implement logical programming concepts but also to demonstrate proficiency in modern software development tools including **Visual Studio Code**, **Git**, and **GitHub**.

**Key Features:**
* **Arithmetic Operations:** Supports Addition, Subtraction, Multiplication, and Division.
* **Error Handling:** Includes safeguards against division by zero.
* **User-Friendly Interface:** Simple text-based menu for easy navigation.

**Tools Used:**
* **Language:** Python (Selected for its readability and concise syntax).
* **Editor:** Visual Studio Code (Used for coding and integrated terminal testing).
* **Version Control:** Git (Used for tracking changes and managing versions).
* **Hosting:** GitHub (Used for remote repository storage and documentation).

---

## 2. Development Process
The development of this project followed a structured "Feature-by-Feature" workflow to ensure clean version control history.

**Phase 1: Initialization**
* Created the project directory and initialized a local Git repository using `git init`.
* Configured a `.gitignore` file to exclude `.vscode` settings and Python `__pycache__` files to keep the repository clean.

**Phase 2: Core Implementation**
* **Step 1:** Created `main.py` and built the basic menu structure.
* **Step 2:** Implemented the **Addition** function and committed the change (`git commit -m "Added addition logic"`).
* **Step 3:** Implemented **Subtraction**, **Multiplication**, and **Division** functions sequentially, committing after each major change to maintain a detailed version history.

**Phase 3: Testing & Debugging**
* Tested the application with various integer and float inputs.
* identified a potential crash when dividing by zero. Added a conditional check (`if y != 0`) to handle this edge case gracefully.

**Phase 4: Documentation & Deployment**
* Created this documentation in the `docs/` folder.
* Pushed the final codebase to GitHub using `git push`.

---

## 3. Future Improvements
While the current version is fully functional, the following enhancements are planned for future updates:

1.  **Graphical User Interface (GUI):**
    * Transition from a console-based app to a windowed application using the **Tkinter** or **PyQt** library to make it more visually appealing.

2.  **Scientific Calculations:**
    * Add advanced mathematical functions such as square root, exponents (power), sine, cosine, and tangent.

3.  **History Feature:**
    * Implement a feature to store the last 5 calculations in a text file or list so users can review previous results.

4.  **Continuous Integration (CI):**
    * Set up a basic GitHub Action to automatically run tests whenever code is pushed to the repository.