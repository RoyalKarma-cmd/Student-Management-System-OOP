# Student Management System (OOP)

## Project Overview

Student Management System is a Python project built using **Object-Oriented Programming (OOP)** concepts.

The project stores student information such as Student ID, Name, Age, Branch, and Marks. It can display student details, greet students, and automatically calculate grades based on their marks.

This project was created as part of my Data Science and Machine Learning learning journey to strengthen my understanding of Classes, Objects, Methods, and Constructors.

---

## Features

### Student Details

Store and display:

* Student ID
* Name
* Age
* Branch
* Marks

---

### Greeting System

Each student receives a personalized greeting.

Example:

```text
Welcome aboard Jaydeep
Welcome to the Extc Department
```

---

### Grade Calculator

Automatically assigns grades based on marks.

| Marks Range | Grade |
| ----------- | ----- |
| 90 - 100    | A+    |
| 80 - 89     | A     |
| 70 - 79     | B     |
| 60 - 69     | C     |
| 50 - 59     | D     |
| Below 50    | F     |

---

## Technologies Used

* Python
* Object-Oriented Programming (OOP)

---

## OOP Concepts Used

### Class

```python
class Student:
```

Acts as a blueprint for creating student objects.

---

### Object

```python
student1 = Student(...)
```

Represents an individual student.

---

### Constructor

```python
def __init__(self):
```

Automatically initializes student data when an object is created.

---

### Attributes

```python
self.student_id
self.name
self.age
self.branch
self.marks
```

Stores student-specific information.

---

### Methods

```python
show_details()
greet()
calculate_grade()
```

Performs actions related to a student.

---

## Sample Output

```text
Student_ID: 100
Name: Jaydeep
Age: 21
Branch: Extc
Marks: 92

Welcome aboard Jaydeep
Welcome to the Extc Department

Grade: A+
```

---

## Example Students

```text
Jaydeep
Bhumi
Saish
Aditya
Aarya
Sarvesh
Swayam
Shantanu
Sayali
```

---

## Learning Outcomes

Through this project, I learned:

* What is Object-Oriented Programming
* Difference between Classes and Objects
* How Constructors work
* Purpose of self
* Creating Attributes
* Creating Methods
* Managing Multiple Objects
* Using Loops with Objects
* Applying Conditions inside Classes

---

## Real-World Applications

Student Management Systems are used in:

* Schools
* Colleges
* Universities
* Online Learning Platforms
* Training Institutes

The same OOP concepts are used in large software systems and Data Science libraries such as:

* NumPy
* Pandas
* Scikit-Learn

---

## Future Improvements

* Add Student Search Feature
* Add Student Update Feature
* Delete Student Records
* Store Data in Files
* Export Data to CSV
* Add Percentage Calculator
* Add Attendance Tracking
* Build GUI Version using Tkinter

---

## Repository Structure

```text
student-management-system-oop/
│
├── student_management_system.py
├── README.md
└── screenshots/
```
