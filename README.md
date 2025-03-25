# **Bank Management System (BMS)** 

This project is a **simple Java-based bank account management system** that allows users to perform basic transactions like deposits and withdrawals through a simple user interface built with **Swing**.

## **Project Overview**

### **1. `BankAccount.java`**
Represents a bank account and handles core operations:  
- **Balance management**  
- **Deposit** functionality  
- **Withdrawal** functionality with error checking  
- **Displays** the current balance  

### **2. `BankReader.java`**
Responsible for reading commands and monetary amounts from the user:  
- Reads commands using **JOptionPane**  
- Extracts and converts the monetary amount from input  

### **3. `TestController.java`**
A simple test class that verifies the functionality of `BankAccount`:  
- Creates a bank account with an initial balance  
- Performs deposit and withdrawal operations  
- Displays the current balance in the **console**  

### **4. `TestController2.java`**
An interactive class using `BankReader` to take user commands and execute transactions:  
- Reads commands (`D` for deposit, `T` for withdrawal, `Q` to quit)  
- Executes corresponding transactions on the bank account  
- Displays the final balance in a readable format  

---
 
##  If you want to clone this repository:  
   ```bash
   git clone
https://github.com/gjergjquni/bank_account_java.git
