# 🏦 Banking Simulation System (Tkinter + SQLite)

> A desktop application that simulates core banking functions like deposits, withdrawals, account creation, and transaction history.

## 🔹 Features
- ✅ **Login System**
  - Existing users can log in with account number and password
  - New users can create accounts
  - Password recovery with email and mobile verification

- ✅ **Banking Operations**
  - Withdraw funds (with balance validation)
  - Deposit funds
  - Check balance
  - View detailed transaction history

- ✅ **Account Management**
  - Update profile (name, password, mobile, email)
  - Upload/set profile picture

- ✅ **Transaction Logging**
  - Each transaction (Cr/Dr) stored with account number, type, amount, updated balance, and timestamp

## 🔹 Database Design (SQLite)
- **accounts** table: stores user details and balance  
- **txn** table: stores transaction logs  

## 🔹 Tech Stack
- **Python**  
- **Tkinter** (GUI framework)  
- **SQLite** (database)  
- **Pillow** (profile picture handling)  

## 🔹 Example Workflow
1. Open a new account → system auto-generates account number  
2. Deposit/Withdraw funds → balance updated + transaction logged  
3. View transaction history → scrollable history of all Cr/Dr operations  
4. Update details (name, email, password, etc.)  

---

✨ *“Simulating banking operations — secure, simple, and interactive.”*
