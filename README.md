# 🧾 Store Billing System (Java + XAMPP MySQL + JDBC)

A Java console-based Store Billing System that uses **MySQL** for storing items, customers, and billing data.  
✔ The program automatically creates the **database and tables** on first run — you only need to start MySQL from XAMPP!

---

## 🚀 Features

- Auto create database + tables (no manual SQL setup)
- Add/Delete/Update **Items**
- Add and maintain **Customer** details
- Add items to **Cart**
- Remove items from cart
- Automatic Bill calculation
- View final Bill in console
- Data stored permanently in MySQL

---

## 🛠 Technologies Used

| Component | Details |
|----------|---------|
| Programming Language | Java |
| Database | MySQL (XAMPP) |
| Connectivity | JDBC (MySQL Connector/J) |
| IDE (Recommended) | IntelliJ IDEA |

---

## 📂 Code Structure

src/
├─ Main.java → Program entry + Menu + User Input
├─ DBConnection.java → MySQL connection + Auto DB/Tables creation
├─ Item.java → Item Model (id, name, qty, price)
├─ ItemService.java → CRUD operations for Items
├─ Customer_Service.java → Manage Customer information
├─ CartService.java → Add/Remove/View cart items
├─ BillingService.java → Total calculation + bill printing
└─ BaseService.java → Shared utilities
---

## ⚙️ Setup & Installation

### 1️⃣ Install Requirements
- Java JDK 8+ or 17+
- XAMPP (MySQL server)

### 2️⃣ Start MySQL Server
Open XAMPP → Click:

