# 🎓 Student Management System

## 📌 Overview
This project is a Student Management System developed using Python. 
It demonstrates Object-Oriented Programming (OOP) concepts such as classes, inheritance, encapsulation, and file handling.

---

## 🧠 Code Explanation

### 🔹 Class: Person
```python
class Person:
```
This is the parent class that represents a general person.

```python
def __init__(self, name, student_id):
```
Constructor used to initialize name and ID.

```python
self.name = name
```
Stores the name as a public attribute.

```python
self.__student_id = student_id
```
Stores the student ID as a private attribute (Encapsulation).

---

### 🔹 Getter and Setter
```python
def get_id(self):
```
Returns the private ID.

```python
def set_id(self, new_id):
```
Updates the private ID.

---

### 🔹 Class: Student
```python
class Student(Person):
```
Child class that inherits from Person.

```python
super().__init__(name, student_id)
```
Calls the parent constructor.

```python
self.grade = grade
```
Stores student grade.

---

### 🔹 File Handling
```python
open("data.txt", "r")
```
Reads data from file.

```python
open("data.txt", "w")
```
Writes data to file.

---

### 🔹 Functions (Operations)

#### Add Student
Adds a new student after validating input.

#### Delete Student
Removes a student using ID.

#### Update Student
Modifies student data.

#### Display Students
Prints all student information.

#### Delete All Data
This feature allows the user to delete all stored data from the file at once,
clearing the entire student database with a single action.

---

### 🔹 Main Function
Controls the program using a menu system.

---
## 🖼️ Output Screenshots

### 🔹 Main Menu
![Main Menu](images/menu.png)

### 🔹 Add Student
![Add Student](images/add.png)

### 🔹 Display Students
![Display](images/display.png)

### 🔹 Update Student
![Update](images/update.png)

### 🔹 Delete Student
![Delete](images/delete.png)

### 🔹 Clear All Data
![Clear](images/clear.png)

---

## ▶️ How to Run

```bash
project1.py
```

---

## 👩‍💻 Team Members
-Sadeem abdullah
-Maryam waheed
-Afrah enazy
-Aseel enazy
-Haya enazy
