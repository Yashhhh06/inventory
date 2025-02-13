# 📦 Inventory Management System

A **PHP-based web application** for managing an inventory system. It allows users to manage products, track stock, and streamline inventory processes efficiently.

## 🚀 Project Overview

This **Inventory Management System** is built using **PHP and MySQL** to provide a simple yet effective way of handling inventory records. Users can add, update, and delete items while maintaining accurate stock levels.

## 📌 Features

- 📋 **User Authentication** – Login system for secure access.
- 🏪 **Product Management** – Add, edit, and remove products.
- 📦 **Stock Tracking** – Monitor item quantities and availability.
- 📊 **Inventory Reports** – Generate reports for inventory analysis.
- ⚡ **User-Friendly Interface** – Responsive and easy-to-use UI.
- 🛠 **Database Integration** – Stores inventory details in MySQL.

## 📁 Project Structure

```
inventory/
│
├── index.php            # Main Dashboard
├── login.php            # User Authentication Page
├── LICENSE.md           # License Information
├── README.md            # Project Documentation
├── assets/              # Stylesheets, JavaScript, and Images
├── data/                # Item Images and Database Files
└── inc/config/          # Configuration Files (Database Connection, Constants)
```

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Web Server:** Apache

## 🏗 Installation

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-repository/inventory-system.git
   ```

2. **Move the root folder to your web server directory:**  
   (For Apache, this is `htdocs`.)

3. **Create a database in MySQL:**  
   ```sql
   CREATE DATABASE shop_inventory;
   ```

4. **Import the SQL dump file into MySQL.**

5. **Configure database settings:**  
   Edit `inc/config/constants.php` and update database credentials.

6. **Start Apache and MySQL servers.**

7. **Access the system via browser:**  
   Open `http://localhost/inventory/login.php`

## 🔑 Default Login Credentials

- **Username:** `guest`
- **Password:** `1234`

## 🗄 Database Structure

- `users` (User login details)
- `products` (Stores inventory items)
- `transactions` (Records stock changes)
- `categories` (Product categorization)

## 🚀 Future Enhancements

- **Admin Dashboard** – Advanced analytics and stock insights.
- **Barcode Scanner Support** – Integrate barcode scanning for quick inventory updates.
- **Multi-User Access** – Role-based user management for admins and staff.
- **REST API Integration** – Extend functionality with external systems.
- **Mobile App Compatibility** – Develop a mobile-friendly version.

## 🤝 Contributing

Contributions are welcome! Feel free to **fork the repository**, make your changes, and submit a pull request.

## 📜 License

This project is licensed under the **MIT License**.

## 📬 Contact

For any issues, suggestions, or contributions, please contact `yashmohite341@gmail.com`.
