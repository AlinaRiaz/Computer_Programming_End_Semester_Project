# C++ Learning App – Course and Quiz Management System

This project is a **console-based Learning App** implemented in **C++**, designed to allow users to register, login, enroll in courses, and take chapter quizzes. It demonstrates fundamental C++ programming concepts, file handling, object-oriented design, and user interaction via the console.

---

## Features

- **User Management**
  - Register new users with unique usernames and passwords.
  - Secure password input with hidden characters.
  - User login and logout functionality.
  - Score tracking across quizzes.

- **Course Management**
  - Multiple courses available (e.g., C++ Programming, Java Programming).
  - Each course has multiple chapters.
  - Users can enroll in courses before accessing chapters.

- **Chapter Learning & Quizzes**
  - View chapter definitions and descriptions.
  - Take quizzes for each chapter with multiple-choice questions.
  - Score updates saved in `user_data.txt` for persistent tracking.

- **Data Persistence**
  - User credentials and scores are saved to a text file (`user_data.txt`) for future sessions.

---

## Technologies Used

- **C++** – Core language for program logic.
- **Standard Template Library (STL)** – Vectors, maps, and strings for data storage.
- **File I/O** – `fstream` to save and load user data.
- **Console Input Handling** – `_getch()` from `<conio.h>` to securely input passwords.

---

## Project Structure

- `main.cpp` – Main program file containing all classes, functions, and application logic.
- `user_data.txt` – Stores user credentials and quiz scores (generated automatically after registration/login).

**Key Classes & Structures**
- `User` – Represents a registered user and stores enrolled courses and scores.
- `Course` – Represents a course with chapters and quizzes.
- `Question` – Represents a single multiple-choice question for a chapter.

---

## How to Run

1. Open the project in **VS Code** or any C++ IDE.
2. Compile the code using a C++ compiler (e.g., `g++ main.cpp -o learningApp`).
3. Run the compiled executable:
