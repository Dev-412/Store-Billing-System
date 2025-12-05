🧾 Store Billing System 🛒

A simple and efficient command-line billing software for store owners.
Manage items, customers, and generate bills — all from a clean console UI.
Runs fully offline with MySQL database powered through XAMPP.

✨ Key Features

Add & Manage Items
Enter price, stock quantity, and store inside database.

Customer Records
Store and fetch customer details automatically.

Shopping Cart System
Add & remove multiple items before billing.

Auto Database Setup
First run automatically creates database & tables — no manual SQL needed!

Accurate Bill Calculation
Auto-totals price and prints final bill in console.

Smooth Menu UI
Beginner-friendly command selection.

🛠 Technologies Used
Tech	Purpose
Java	Main application
MySQL via XAMPP	Data storage
JDBC	DB connection driver
IntelliJ IDEA	Recommended IDE
OOP + Service Layer	Code structure
🚀 How to Get Started

You can run this project directly from source.
Follow these steps 👇

📌 Prerequisites

Install these on your PC:

✔ Java JDK (8 or above recommended)
✔ XAMPP (for MySQL server)
✔ MySQL Connector/J (JDBC driver JAR)
✔ IntelliJ IDEA (recommended)

⚙️ Setup

1️⃣ Clone the repository

git clone https://github.com/YOUR-USERNAME/Store-Billing-System.git


2️⃣ Open the project in IntelliJ IDEA

3️⃣ Add MySQL Connector/J library

File → Project Structure → Modules → Dependencies → + Add JAR


4️⃣ Start MySQL in XAMPP

Open XAMPP → Start MySQL
(Do NOT start Apache)


5️⃣ Run the application

src → Main.java → Right-click → Run


💡 Database and tables will auto-create if missing — no phpMyAdmin required!

🎮 In-Game Example
==== Store Billing System ====
1. Add Item
2. View Items
3. Add Customer
4. Add Item To Cart
5. Generate Bill
6. Exit
Enter choice:


Example Bill:

----- FINAL BILL -----
Customer: Rahul
Sugar (₹40 × 2) = ₹80
Rice 5kg (₹200 × 1) = ₹200
Total = ₹280
---------------------

🔐 Security & Data

All data stored securely in MySQL

No external network required

Fully offline local billing app

🧑‍💻 Developer

Dev
Java & DBMS Project — Semester Submission ✔

If you like the project, please ⭐ star the repo!
