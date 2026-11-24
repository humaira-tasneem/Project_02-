# 🎓 Student Record Management System (SRMS)

A console-based student record management system written in **C**. It includes a **login system** and uses **file handling** to store data, so records are saved between runs.

## ✨ Features

- **Login system:** access is protected by a username and password
- **File handling:** student records are stored in a text file and persist after the program closes
- **Menu-driven interface:** simple console menu, no setup needed

## 🧠 Concepts Used

- File handling in C (reading and writing text files)
- Structures (`struct`) for student data
- Functions and modular code
- Basic authentication logic

## 📁 Project Structure

```
.
├── srms.c             # Source code
├── srms.exe           # Compiled program (Windows)
├── students.txt       # Student records storage
├── credentials.txt    # Login credentials used by the program
└── README.md
```

## ⚙️ How to Compile

Make sure you have a C compiler such as `gcc` installed, then run this from the project folder:

```bash
gcc srms.c -o srms
```

## ▶️ How to Run

Keep `students.txt` and `credentials.txt` in the same folder as the program.

**Linux / WSL / macOS**

```bash
./srms
```

**Windows**

```bash
srms.exe
```

## 🔐 Login

Enter the username and password stored in `credentials.txt` when prompted.

> **Note:** The credentials file in this repo is for demo purposes only. Do not store real passwords in a public repository.

## 🚀 Possible Improvements

- Hash passwords instead of storing them as plain text
- Add input validation
- Add sorting and searching of student records
