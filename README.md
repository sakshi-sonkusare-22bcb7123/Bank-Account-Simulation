# 🛰️ Bank Account Simulation – Java OOP Project  

## 🧁 Overview  
This project is a **console-based Bank Account Simulation** built in **Java** using **Object-Oriented Programming (OOP)** principles.  
It allows users to:  
- Create a bank account with an initial deposit.  
- Perform **Deposit** and **Withdrawal** transactions.  
- Check the account balance.  
- View the full **Transaction History**.  

The program includes **input validation** and maintains a record of all transactions during the session.  

---

## 🦓 Features  
- **Account Creation** → User provides name and initial deposit.  
- **Deposit Money** → Adds funds and updates balance instantly.  
- **Withdraw Money** → Deducts funds with insufficient balance check.  
- **Check Balance** → Displays current account balance.  
- **Transaction History** → Keeps a session log of all deposits and withdrawals.  
- **Exit Option** → Ends the program safely with a thank-you message.  

---

## 🏀 Classes & Responsibilities  

### 1. `Account`  
Handles all account-related operations.  
- **Fields**:  
  - `accountHolder` → Name of the account owner  
  - `balance` → Current account balance  
  - `transactionHistory` → List of all transactions in session  
- **Methods**:  
  - `deposit(amount)` → Add money and log transaction  
  - `withdraw(amount)` → Deduct money with validation  
  - `checkBalance()` → Display balance  
  - `printTransactionHistory()` → Print all past transactions  

### 2. `BankAccountSimulation` (Main Class)  
- Handles **user input** and menu navigation.  
- Creates the `Account` object.  
- Uses a loop-driven menu for deposit, withdraw, check balance, history, and exit.  

---

## 🗺️ Concepts Used  
- **Java Classes & Objects**  
- **Encapsulation** (private fields, public methods)  
- **ArrayList** for transaction history  
- **Conditional statements** for validations  
- **Looping** for menu-driven program flow  
- **User input handling** using `Scanner`  

---

## 🛸 Future Improvements  
- Save transaction history to a file for **persistence across sessions**.  
- Add account authentication with **username & PIN**.  
- Support for **multiple accounts** in one session.  
- Implement **interest calculations** or account types (Savings, Current).  

---

## 🚴‍♀️ How to Run  

1. Save the code in a file named **`BankAccountSimulation.java`**  
2. Compile the program:  
   ```sh
   javac BankAccountSimulation.java
   ````

3. Run the program:

   ```sh
   java BankAccountSimulation
   ```
4. Follow the **menu options** to interact with the banking system.

---

## 🥤🍀 About the Author

**Sakshi Bhojraj Sonkusare**

Aspiring software developer with a strong interest in creating impactful, user-friendly applications. Passionate about continuous learning and bringing ideas to life through code.

* LinkedIn: [https://www.linkedin.com/in/sakshi-sonkusare-381362354/](https://www.linkedin.com/in/sakshi-sonkusare-381362354/)
* Portfolio: Coming Soon

---

## ❤️ Contributions and Support

Feedback, suggestions, and contributions are always welcome.
Pull requests for improvements, bug fixes, or feature additions are encouraged.

---
