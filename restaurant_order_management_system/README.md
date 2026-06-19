# 🍔 Restaurant Order & Billing System

An interactive terminal order system containing extensive menu matrices (BBQ, Fast Food, Drinks, Desserts), automated order receipt generations, and ID-based record manipulation (CRUD).

## 🛠️ Features

- **Categorized Menus:** Separates items into BBQ, Fast Food, Drinks, and Desserts.
- **Dynamic Order Logging:** Real-time console interaction for adding items to the current checkout sequence.
- **Order ID Tracking:** Assigns unique IDs to orders for fast lookup.
- **CRUD Operations (In-Memory):**
  - **Create:** Add items to custom orders.
  - **Read:** View specific order items and costs by Order ID, or list all orders.
  - **Delete:** Remove active orders by ID.

---

## 🏗️ Structure Overview

- **`Menu`**: Generic abstract class representing standard menu items with names and prices.
- **`BBQ`, `FastFood`, `Drinks`, `Desserts`**: Specialized menu categories.
- **`RestMenu`**: Builds the core restaurant database menu.
- **`Bill`**: Manages customer checkouts, active order maps, console inputs, and logs receipt details.
- **`Restaurant_Order_Management_System`**: Houses the main execution menu and terminal input scanner.

---

## 🚀 How to Run

1. Open your terminal in this directory:
   ```bash
   cd restaurant_order_management_system
   ```

2. Compile all files:
   ```bash
   javac *.java
   ```

3. Run the driver class:
   ```bash
   java Restaurant_Order_Management_System
   ```
