# 💵 Loan Management System

Calculates monthly installments and interest logic for distinct financial products including Car, Home, and Personal Loans.

## 🛠️ Features

- **Abstract Formula Evaluation:** Shared parent class `Loan` handles core parameters (`principal`, `tenureYears`, `annualRate`).
- **Overhead Adjustments:** Subclasses calculate installments including specific variables:
  - **Car Loan:** Downpayment deduction.
  - **Home Loan:** Property tax & insurance overhead calculation.
  - **Personal Loan:** Base processing fees, setup costs, and interest offsets.

---

## 🏗️ Structure Overview

- **`Loan` (Abstract Base Class)**: Base interface outlining standard loan details and abstract monthly calculation hooks.
- **`Carloan`**: Implementation of specific automobile lease parameters.
- **`Homeloan`**: Computes mortgage interest, taxes, and property insurance offsets.
- **`Personalloan`**: Calculates basic unsecured signature line configurations.
- **`Loan_managementsystem`**: Runner compiling and logging monthly calculations for all product types.

---

## 🚀 How to Run

1. Open your terminal in this directory:
   ```bash
   cd "Loan Management System java"
   ```

2. Compile all files:
   ```bash
   javac *.java
   ```

3. Run the driver class:
   ```bash
   java Loan_managementsystem
   ```
