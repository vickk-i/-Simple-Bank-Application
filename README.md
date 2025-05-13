Perfect! Now that you’ve provided the source code, here’s a polished version of the GitHub README including a short project description, features, usage instructions, and code structure—all based on your `BankingApplication.java` file:

---

# 💳 Java Project – Simple Bank Application (Beginner Level)

This is a **beginner-friendly Java project** that simulates basic banking operations using object-oriented programming. It is a **console-based application** that allows a user to deposit money, withdraw funds, check balance, and view the last transaction.

---

## 🚀 Features

* ✅ Deposit Money
* ✅ Withdraw Funds
* ✅ Check Current Balance
* ✅ View Previous Transaction
* ✅ Exit the Application

---

## 📂 Project Structure

```bash
BankingApplication.java
└── BankAccount class
    ├── deposit(int amount)
    ├── withdrawn(int amount)
    ├── getprevioustransaction()
    └── showmenu()
```

---

## 💡 How It Works

* The program starts by creating a `BankAccount` object with a customer's name and ID.
* A menu-driven interface allows the user to interact with their account.
* All transactions (deposit/withdraw) are handled using Java methods.
* The application keeps track of the last transaction.
* Data is stored only during runtime (no database is used).

---

## 🛠️ How to Run

1. Make sure you have Java installed.
2. Compile the code using:

   ```
   javac BankingApplication.java
   ```
3. Run the application:

   ```
   java com.sumanth.project.BankingApplication
   ```

---

## 🎯 Skills Demonstrated

* Java Basics (Classes, Objects, Methods)
* Constructors
* Conditionals and Loops
* User Input Handling (Scanner)
* Menu-based Console Applications

---
