video:https://drive.google.com/file/d/1OYhnq4Ci66hisY0r9ZFyYn8jMhl-Z8qA/view?usp=drivesdk
Multi-Utility Toolkit 🛠️

📌 Project Description

The Multi-Utility Toolkit is a menu-driven Python application that combines multiple useful utilities in one program. It allows users to perform date and time operations, mathematical calculations, random data generation, UUID generation, file handling, and module exploration.

This project demonstrates the use of Python built-in modules, custom modules, functions, loops, conditional statements, and user input.

✨ Features

1. 📅 Datetime and Time Operations

- Display the current date and time.
- Calculate the difference between two dates.
- Display the date in a custom format.
- Start and stop a basic stopwatch.
- Run a countdown timer.

2. 🔢 Mathematical Operations

- Calculate the factorial of a number.
- Calculate compound interest.
- Perform trigonometric calculations (sine, cosine, and tangent).
- Calculate the area of a circle.
- Calculate the area of a rectangle.

3. 🎲 Random Data Generation

- Generate a random number between 1 and 100.
- Generate a list of five random numbers.
- Create a random alphanumeric password.
- Generate a six-digit random OTP.

4. 🆔 Unique Identifier Generation

- Generate a universally unique identifier (UUID) using Python's "uuid" module.

5. 📁 File Operations

Using a custom module, the program supports:

- Creating a new file.
- Writing content to a file.
- Reading file contents.
- Appending content to a file.

6. 🔍 Explore Module Attributes

- Explore available attributes and functions of the "math", "random", and "datetime" modules using Python's "dir()" function.

🛠️ Technologies Used

- Programming Language: Python
- Built-in Modules:
  - "datetime" – Date and time operations.
  - "time" – Stopwatch-related timing and countdown delays.
  - "math" – Mathematical module exploration.
  - "random" – Random numbers, lists, passwords, and OTP generation.
  - "uuid" – Unique identifier generation.
- Custom Modules:
  - "fileoperation" – File-handling operations.
  - "calculation" – Mathematical calculations.

📂 Project Structure

Multi-Utility-Toolkit/
│
├── main.py
│
└── package/
    ├── __init__.py
    ├── fileoperation.py
    └── calculation.py

Note: "main.py" is the suggested filename for the main program. Adjust the structure to match your actual project files.

▶️ How to Run the Project

Prerequisites

- Python 3 installed on your system.
- A code editor such as VS Code or PyCharm.

Steps

1. Clone or download this repository.
2. Open the project folder in your code editor.
3. Make sure the "package" folder contains the required custom modules.
4. Open a terminal in the project directory.
5. Run the following command:

python main.py

On some systems, use:

python3 main.py

6. Select an option from the main menu.
7. Follow the instructions displayed on the screen.

📚 Python Concepts Demonstrated

- Functions and modular programming.
- "while" loops and "if-elif-else" statements.
- User input and formatted output.
- Exception handling in custom modules, if implemented.
- Importing built-in and user-defined modules.
- File handling.
- Date and time calculations.
- Random data generation.
- UUID generation.
- The "dir()" function for module exploration.

🎯 Learning Objectives

The main objective of this project is to understand how Python's built-in modules and custom modules can be combined to develop a practical, menu-driven application. It also helps improve problem-solving skills and knowledge of modular programming.

⚠️ Notes

- Enter valid inputs when prompted.
- The countdown timer requires a positive number of seconds to behave as expected.
- The stopwatch currently measures the start and stop interaction but does not calculate or display the elapsed time.
- The password and OTP generators use Python's "random" module and are intended for educational purposes, not security-sensitive applications.
- The custom "calculation" and "fileoperation" modules must be implemented for the corresponding features to work.

👩‍💻 Author
 
Florence David 

📄 License

This project is intended for educational and learning purposes.
