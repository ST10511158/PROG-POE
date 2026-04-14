# PROG-POE
# Java Login and Registration System

## 📌 Overview
This is a simple Java console-based application that handles user registration and login.  
It validates user input and ensures that all credentials meet specific security requirements before allowing login.

---

## ⚙️ Features

### 🔐 Registration
The system checks:
- Username must contain an underscore (_) and be no longer than 5 characters
- Password must:
  - Be at least 8 characters long
  - Contain at least one uppercase letter
  - Contain at least one number
  - Contain at least one special character
- Cell phone number must start with +27 and contain 9 digits after it

---

### 🔑 Login
- Users must enter the correct username and password
- If correct → welcome message is displayed
- If incorrect → user is prompted to try again

---

## 🧠 Concepts Used
- Object-Oriented Programming (OOP)
- Encapsulation
- Methods and Classes
- Input validation
- Regular expressions (regex)
- Loops for repeated input

---

## 📂 Project Structure
- `Main.java` → Handles user input and program flow
- `Login.java` → Handles validation and authentication logic

---

## ▶️ How to Run
1. Clone the repository:
