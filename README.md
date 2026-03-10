# Book My Stay App

## 📌 Objective
To build a console-based **Hotel Booking Management System** using Core Java while demonstrating the practical use of **Object-Oriented Programming and Data Structures** in real-world scenarios.

This project is developed incrementally through multiple **Use Cases (UC)**.  
Each use case introduces a new concept that improves system design, scalability, and maintainability.

The focus of the project is on **core application logic and system behavior**, rather than graphical interfaces.

---

# 🚀 Features / Use Cases Implemented

## UC1 – Application Entry & Welcome Message
Establishes the starting point of the Java application.

Displays:
- Application Name
- Version Information
- Welcome Message

Concepts used:
- Java `Class`
- `main()` method
- `static` keyword
- Console output (`System.out.println`)
- Program execution flow

---

## UC2 – Basic Room Types & Static Availability
Introduces **Object-Oriented Domain Modeling** using inheritance and abstraction.

Room types implemented:
- Single Room
- Double Room
- Suite Room

Concepts used:
- Abstract Class (`Room`)
- Inheritance
- Polymorphism
- Encapsulation

Room availability is stored using **simple variables** to highlight limitations of scattered state management.

Example:
Single Room → 10 available  
Double Room → 6 available  
Suite Room → 3 available

---

## UC3 – Centralized Room Inventory Management
Refactors the system to introduce **centralized inventory management**.

Room availability is now managed using a **HashMap**, which acts as a single source of truth for the system.

Data Structure used:
- `HashMap<String, Integer>`

Concepts used:
- Centralized state management
- Encapsulation of inventory logic
- O(1) lookup and update operations
- Separation of domain model and system state

Example inventory:
Single Room → 10  
Double Room → 6  
Suite Room → 3  

---

# 🛠 Technologies Used
- Java
- IntelliJ IDEA / VS Code
- Git & GitHub

---

# 🌱 Git Workflow Followed
For each Use Case:

1. Created a new branch
2. Implemented the feature
3. Committed the changes
4. Created a Pull Request
5. Merged the branch into `main`

This workflow reflects **real-world collaborative development practices**.

---

# 📈 Learning Outcomes
Through this project, the following concepts are demonstrated:

- Java application lifecycle
- Object-Oriented Programming
- Abstraction and Inheritance
- Encapsulation
- Polymorphism
- State management using HashMap
- Scalable software design principles

---

# 👩‍💻 Author
**Farjan Alam**
