# Bank Management System (Java | OOP | MVC)

This is a simple **Bank Management System** implemented in **Java** using  
**OOP concepts** and the **MVC (Model–View–Controller)** architecture.  
It supports multiple account types, transactions, freezing logic, and  
EOD (End-of-Day) reporting.

---

## 🚀 Features

### ✔ **Account Types**
1. Saving Account  
2. Salary Account  
3. Current Account  
4. Loan Account  

### ✔ **Core Functionalities**
- Create / Search / Delete Accounts  
- Deposit Money  
- Withdraw Money  
- Freeze Salary Account  
- Display All Accounts  
- EOD Report  
- Transaction History (All + By Account No.)

### ✔ **OOP Concepts Used**
- Inheritance  
- Abstraction  
- Method Overriding  
- Polymorphism  
- Encapsulation  

### ✔ **MVC Architecture**
- **Model:** Account classes, BankModel, Transaction  
- **Controller:** BankController  
- **View:** BankView (User input/output handling)

---

## 📂 Project Structure  

JavaCaseStudy1/
│
├── README.md
└── BankTest/


---

## 🧠 **Account Rules**

### **Saving Account**
- Minimum balance → ₹10,000  
- Withdraw allowed only if balance stays above min balance  
- Interest: `3%`

### **Salary Account**
- Freezes automatically after **2 inactive months**  
- Frozen account cannot withdraw/deposit  
- Interest: `4%`

### **Current Account**
- Overdraft limit → ₹10,000  
- Interest: `0%`

### **Loan Account**
- Withdraw not allowed  
- Deposit reduces loan EMI  
- Interest: calculated on remaining loan amount  

---

## 📝 **How to Run**

1. Clone the repository:
https://github.com/roshanichaudhari738/Java_Case_Study_1.git


2. Open your project folder and compile all `.java` files:

javac BankTest.java


3. Run the main file:

java Practise.BankTest

---

## 📌 **Sample Menu (Console Output)**

1. Create Account

2. Search Account

3. Delete Account

4. Deposit Money

5. Withdraw Money

6. Freeze Account

7. Show EOD Report

8. Show Transaction History

9. Display All Accounts

10.Exit


---

## 📒 **Transaction Record Format**

Acc:101 DEPOSIT 5000 2025-11-28 13:20:15 

Acc:201 WITHDRAW 2000 2025-11-28 14:02:11


---

## 🛠 Technologies Used
- **Java (Core)**
- **Object-Oriented Programming**
- **MVC Architecture**
- **Console-based UI**

---
## 📘 UML Class Diagram

Below is the UML diagram representing the full architecture:

![Class Diagram](https://github.com/roshanichaudhari738/Java_Case_Study_1/blob/main/Diagram.drawio.png)

UML diagram

---

## 🙌 Author
**Roshani Chaudhari**
