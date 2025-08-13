# 🛰️ Bank Account Simulation – Java OOP Project  

## 🧁 Overview  
This project is a **console-based Bank Account Simulation** built in **Java** using **Object-Oriented Programming (OOP)** concepts.  
It allows a user to:  
- Create a bank account with an initial deposit.  
- Perform **Deposit** and **Withdrawal** transactions.  
- Check account balance.  
- View complete transaction history.  

The program ensures proper **input validation** and keeps a record of all transactions in memory.  

---

## 🦓 Features  
- **Account Creation** – Create an account with the account holder’s name and initial balance.  
- **Deposit Money** – Add funds to the account with real-time balance updates.  
- **Withdraw Money** – Withdraw funds with insufficient balance checks.  
- **Check Balance** – View the current account balance.  
- **Transaction History** – See a detailed log of all deposits and withdrawals.  
- **Exit Option** – End the program safely.  

---


### **Classes**  

#### 1. Account  
- **Fields**:  
  - `accountHolder`  
  - `balance`  
  - `transactionHistory`  
- **Methods**:  
  - `deposit(amount)` – Adds money to balance and logs the transaction.  
  - `withdraw(amount)` – Deducts money if funds are sufficient.  
  - `checkBalance()` – Displays current balance.  
  - `printTransactionHistory()` – Shows all past transactions.  

#### 2. BankAccountSimulation (Main Class)  
- Handles user input and menu options.  
- Creates an `Account` object and calls appropriate methods based on user choice.  

---

## 🗺️ Concepts Used

Java Classes & Objects
Encapsulation (private fields with public methods)
ArrayList for storing transaction history
Conditional Statements for validation
Looping & Menu-Driven Programs
User Input Handling with Scanner

---

## 🛸 Future Improvements

Save transaction history to a file for persistence.
Add account authentication with username & PIN.
Support for multiple accounts in one session.

---

## 🥤🍀 About the Author

**Sakshi Bhojraj Sonkusare**  

Aspiring software developer with a strong interest in creating impactful, user-friendly applications. Passionate about continuous learning and bringing ideas to life through code.

- LinkedIn: [https://www.linkedin.com/in/sakshi-sonkusare-381362354/](https://www.linkedin.com/in/sakshi-sonkusare-381362354/)  
- Portfolio: Coming Soon  

---

## Contributions and Support ❤️

Feedback, suggestions, and contributions are always welcome.   
Pull requests for improvements, bug fixes, or feature additions are encouraged.

---


