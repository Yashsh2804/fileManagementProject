# File Management System (C++)

A simple and interactive **File Management Tool** built using C++. This project demonstrates essential file-handling operations such as:

- Creating and writing to a file
- Reading data from a file
- Appending new content to an existing file

The program is **menu-driven** and uses standard C++ file I/O libraries. It is ideal for beginners, academic assignments, and internship tasks.

---

## 📁 Project Structure
```
FileManagementSystem/
│
├── src/                      # All C++ source files
│   └── file_management_tool.cpp
│
├── include/                  # (Optional) header files for code splitting
│   └── file_manager.h
│
├── bin/                      # Compiled executable
│   └── file_tool   (file_tool.exe on Windows)
│
├── data/                     # Text files used by the program
│   └── data.txt
│
├── docs/                     # Documentation for submissions
│   └── Project_Report.pdf
│
└── README.md                 # Instructions for compiling & running
```

---

## 🚀 Features
- Write text to a file (create or overwrite)
- Read and display file contents
- Append new text to an existing file
- Clean and simple menu interface
- Uses only **standard C++ libraries** (no external dependencies)

---

## 🛠️ Technologies Used
- **C++ (Standard Library)**
- `fstream`, `ifstream`, `ofstream`
- Terminal / Command-line interface

---

## ✅ How to Compile (Mac / Linux)
Make sure you are inside the root project folder:
```bash
g++ src/file_management_tool.cpp -o bin/file_tool
```
Run the program:
```bash
./bin/file_tool
```

---

## 📌 Example Usage
```
===== FILE MANAGEMENT TOOL =====
Enter the file name (e.g., data.txt): data/data.txt

========== MENU ==========
1. Write to file
2. Read from file
3. Append to file
4. Exit
```
