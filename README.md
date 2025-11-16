# 🏫 University Management System

### 📌 Overview
This project is a **C++ console-based University Management System** that simulates three core modules:
1. **Teacher Portal**  
2. **University Café**  
3. **Gaming Zone**

It provides interactive functionality for academic record keeping, cafeteria billing, and entertainment through a two-player game.

---

### 🎓 Teacher Portal
- Enter classes and subjects (e.g., CE-112L MTS II B, CE-115L BEBME II-A)  
- Select a class and add student names, roll numbers, and marks  
- Assessments include:
  - Lab Performance
  - Lab Reports
  - Midterm
  - CEA
  - Final Term  
- Option to assign weights to each assessment  
- Calculate total marks and grades  
- Supports CSV file reading for demo or scalable input  

---

### ☕ University Café
- Displays menu with item names and prices  
- Allows multiple item selection  
- Option to “buy more items” or “show bill”  
- Calculates and displays total bill  

---

### 🎮 Gaming Zone
- Two-player **Tic-Tac-Toe** game  
- Players alternate turns using X and O  
- Win condition: 3 in a row (horizontal, vertical, diagonal)  
- Draw condition if no winner after all moves  

---

### 🛠️ Technologies Used
- Language: **C++**  
- Libraries: `<iostream>`, `<fstream>`, `<string>`, `<sstream>`, `<iomanip>`  
- Platform: Windows console (uses `system("cls")`, `getch()`)

---

### 📂 Files
- `src/UniversityManagement.cpp` → Main source code  
- `.gitignore` → ignored files configuration  
- `.gitattributes` → repository attributes  
- `README.md` → project documentation  
- `data/` → (optional) CSV files for student records 

---

### 🙌 Acknowledgment
Developed as part of my **Mechatronics Engineering coursework**, showcasing modular programming, file handling, and interactive console design in C++.
