# 🏦 Bank Extension 2 – Console Banking System (C++)

A complete **console-based banking management system** built using **C++**, focusing on real-world logic, file handling, user permissions, and structured menus.

This project simulates a small banking system with **clients management**, **transactions**, and **user roles & permissions**, implemented as an educational but professional-level application.

---

## 📌 Project Overview

The system allows authenticated users to manage bank clients, perform financial transactions, and control system access using permission-based roles.

All data is stored in text files, making the project lightweight while still demonstrating real backend logic.

---

## 🏗️ System Design

- Console-based application
- Menu-driven navigation
- File-based persistence (TXT files)
- Role & permission system
- Modular functional design

---

## 🔐 Authentication & Permissions

- Secure login system (Username & Password)
- Permission-based access control
- Admin users can manage other users
- Each user has a permission mask:
  - List clients
  - Add clients
  - Delete clients
  - Update clients
  - Find clients
  - Perform transactions
  - Manage users

---

## 🚀 Main Features

### 👥 Client Management
- Add new clients
- Update client information
- Delete clients
- Find clients by account number
- List all clients

### 💰 Transactions
- Deposit money
- Withdraw money (with balance validation)
- Show total balances of all clients

### 👤 User Management
- Add new users
- Update users
- Delete users (Admin protected)
- Assign custom permissions
- List all users

### 📂 File Handling
- Clients stored in `Clients.txt`
- Users stored in `Users.txt`
- Custom record format using separators
- Load, save, update, and delete records safely

---

## 🛠️ Technologies Used

- C++
- STL (vector, string, iostream, fstream)
- File I/O
- Structured Programming
- Console UI
- Bitwise Operations (Permissions)

---

## 🧠 Concepts Applied

- Structs & Enums
- File-based databases
- Access control using bitwise flags
- Input validation
- Separation of logic into reusable functions
- Menu-driven system design
- Defensive programming

---

## 📂 Project Structure
Bank Extension 2
├── Bank Extension 2.cpp
├── Clients.txt
├── Users.txt
├── x64/
└── Project Files (.vcxproj, .sln)

---

## ▶️ How to Run

1. Open the project in **Visual Studio**
2. Build the solution
3. Run the program
4. Login using an existing user
5. Navigate through menus using numeric options

---

## 🎯 Purpose of the Project

This project was built to:
- Practice real-world C++ programming
- Understand file-based data storage
- Implement permission-based systems
- Simulate a banking backend logic
- Strengthen problem-solving skills
- Build a strong portfolio console project

---

## ⚠️ Notes

- This is an educational project
- Data is stored in plain text files
- Passwords are not encrypted (for learning purposes)
- Can be extended with:
  - Encryption
  - Database support
  - Logging system
  - GUI version

---

## 👤 Author

**Adnan Ghiyath**  
Self-taught Software Developer  
Focused on C++ & System Logic  
📍 UAE | 🇸🇾 Syrian

