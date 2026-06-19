# 🍽️ Restaurant Staff Management System

A Java system modeling the workplace workflows, shift structures, and role relationships inside a modern dining establishment.

## 🛠️ Features

- **Staff Inheritance Matrix:** Implements specific duties, salary schemes, and shift constraints.
- **Unified Staff Management:** Enlists and displays active staff logs.
- **Inter-Object Communication:** Simulates interactions like Chefs cooking ordered items requested by Waiters, Cashiers generating bills, and Cleaners maintaining tables.

---

## 🏗️ Structure Overview

- **`Person` (Base Class)**: Maps shared parameters like name, id, age, shift, and basic details.
- **`Waiter`**: Handles order routing and delivery simulation.
- **`Cheff`**: Cooks dishes and links to requesting waiters.
- **`Manager`**: Handles new hiring, shifts, and operations checklists.
- **`Cashier`**: Balances drawer assets and formats receipts.
- **`Cleaner`**: Performs sanitation loops across tables.
- **`Management`**: Handles aggregate records of active employees.
- **`Restaurant`**: Initiates a mock day's operational lifecycle.

---

## 🚀 How to Run

1. Open your terminal in this directory:
   ```bash
   cd "Restaurant Management System java"
   ```

2. Compile all files:
   ```bash
   javac *.java
   ```

3. Run the driver class:
   ```bash
   java Restaurant
   ```
