# 🎓 Student Record Management System (C Project)

This is a **console-based Student Record Management System** developed in **C**. It allows users to create, view, add, search, delete, and manage student records with various options through an interactive terminal menu.

---

## 📌 Features

✅ Create new student records  
✅ Add student records at the beginning, end, or middle  
✅ Display records (forward or backward traversal)  
✅ Search a student record by ID  
✅ Delete student records  
✅ View total number of student records  
✅ View top-performing student (feature placeholder)  
✅ Modify student record (feature placeholder)  
✅ Exit the program

---

## 🛠️ Technologies Used

- **Language:** C
- **Compiler:** GCC / Dev-C++ / Code::Blocks
- **Header Files:** `stdio.h`, `stdlib.h`, `conio.h` (for `getch()` and `cls()`)

---

## 💡 How It Works

- Uses a menu-driven interface in the terminal
- Stores student records in memory (likely using linked list or arrays – implement as needed)
- Performs basic operations based on user's numeric input
- Uses helper functions like:
  - `create_students_record()`
  - `add_student_record_at_first()`
  - `display_students_record_from_forward()`
  - `search_students_record(int id)`
  - `delete_students_record()`
  - `length_of_the_students_record()`

> 💬 Functions like modifying and top student are declared but not yet implemented

---

## 🚀 How to Run

1. Clone this repository or download the `.c` file.
2. Open in your favorite C IDE (e.g., Code::Blocks or Dev-C++).
3. Compile and run the program.

### Example using GCC:
```bash
gcc student_record.c -o student_record
./student_record
