# 🏦 Bank Management System

A Java application demonstrating object-oriented concepts like **Abstraction**, **Inheritance**, **Polymorphism**, and **Encapsulation** through a mock banking ecosystem.

## 🛠️ Features

- **Savings Account:** Interest calculation (based on account-specific rules) and simple balance management.
- **Current Account:** Deducts transaction fees for maintenance and records operations.
- **Fixed Deposit:** Integrates lock-in parameters, penalty restrictions, and higher interest rates.
- **Student Account:** Enforces custom overdraft limits and basic verification.
- **Unified Interface:** Interactive console menu to select accounts, perform deposits, withdrawals, and view interest logs.

---

## 🏗️ Class Hierarchy

- **`BankAccount` (Abstract Base Class):** Definement of basic parameters (`accountnum`, `accountholdername`, `balance`) and abstract methods (`calculateInterest()`, `getaccounttype()`, `deposit()`, `withdraw()`).
- **`Savingaccount`:** Extension of BankAccount with specific interest rules.
- **`Currentaccount`:** Features specialized transaction fees and checks.
- **`Fixeddeposit`:** Lock-in term verification logic.
- **`StudentAccount`:** Custom parameters for overdraft bounds.
- **`BankManagementsystem`:** Driver program coordinating the user interface.

---

## 🚀 How to Run

1. Open your terminal in this directory:
   ```bash
   cd "Bank Management system Java"
   ```

2. Compile all files:
   ```bash
   javac *.java
   ```

3. Run the driver class:
   ```bash
   java BankManagementsystem
   ```
