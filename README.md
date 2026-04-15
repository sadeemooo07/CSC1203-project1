## 🎓 Student Management System

## 📌 Overview
This project is a Student Management System developed using Python.  
It demonstrates key Object-Oriented Programming (OOP) concepts such as classes, inheritance, encapsulation, along with file handling.

The system allows users to manage student records through a simple and interactive menu.

---

## 🎯 Objectives
- Apply OOP concepts in a real-world scenario  
- Implement inheritance between classes  
- Use encapsulation to protect data  
- Store and retrieve data using a text file  

---

## ⚙️ Features
- ➕ Add a new student  
- ❌ Delete an existing student  
- ✏️ Update student information  
- 👀 Display all students  
- 💾 Save data to a file  
- 📂 Load data automatically at startup  

---

## 🧠 OOP Concepts Used

### 1. Classes & Objects
- Person class (Parent)  
- Student class (Child)

### 2. Inheritance
- Student inherits from Person  

### 3. Encapsulation
- Private attribute: __student_id  
- Accessed using getter and setter methods  

---

## 📁 File Handling
- Data is stored in a file named data.txt  
- The program:
  - Reads data at startup  
  - Writes data when exiting  

---

## ▶️ How to Run
```
python project.py
```
---

## 🧪 Example Code
```
s = Student("Ali", "123", 90)
s.display()
```
---

## 🖥️ Sample Output
```
--- Student Management System ---
1. Add Student
2. Delete Student
3. Update Student
4. Display Students
5. Exit
```
---

## 📂 Project Structure
```
project/
│
├── project.py     # Main program file
├── data.txt       # Stores student data
└── README.md      # Project documentation
```
---

## 🚀 Future Improvements
- 🔍 Add search functionality  
- 🎨 Improve user interface (GUI)  
- 🗄️ Use a database instead of text file  
- 📊 Add sorting and filtering options  

---
---

## 👩‍💻 Team Members
- Sadeem Abdullah
- Maryam waheed
- Afrah enazy
- Aseel saad
- Haya enazy

## ⭐ Notes
This project was created as part of a programming course to demonstrate practical implementation of OOP concepts in Python.
