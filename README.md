# 🍽️ Restaurant Management System – *Platinia House*
**Oracle Academy Project (2024)**  
Developed as part of the Oracle Academy program using **Oracle SQL Developer**.  
This project models and manages the operations of a restaurant, handling employees, clients, suppliers, ingredients, and orders through a relational database system.

---

## 📘 Overview
The *Platinia House* restaurant database aims to ensure efficient organization and data management in a restaurant environment.  
It provides structured handling of:
- **Employee records** (roles, salaries, contact details)
- **Client information** (registrations, orders)
- **Dishes and ingredients** (categories, preparation time, price)
- **Suppliers** (ingredient source and stock tracking)
- **Orders and deliveries** (management of drivers, vehicles, and delivery tracking)

The system helps managers monitor best-selling dishes, daily revenue, and ingredient availability.

---

## 🧩 Features
- **User login interface** (secure access for restaurant staff)
- **Relational database design** with fully normalized tables
- **Entity–Relationship Diagram (ERD)** for logical data modeling
- **Dynamic SQL queries** for:
  - Ingredient expiration tracking  
  - Order and sales reports  
  - Customer statistics  
  - Employee and delivery analysis
- **Form-based input system** for inserting and updating data
- **Statistical reports** on categories, daily orders, and client activity

---

## ⚙️ System Design
The project uses a normalized relational model with the following tables:
`Restaurant`, `Employees`, `Clients`, `Dishes`, `Ingredients`, `Suppliers`, `Orders`, `Vehicles`, and relationship tables for linking entities.
Each table includes appropriate **constraints**, **foreign keys**, and **relationships** ensuring data integrity and referential consistency.

---

## 📈 Example Queries
- Display ingredients expiring within 5 days  
- List best-selling dishes  
- Show daily total revenue  
- Find clients with more than 3 orders  
- Retrieve orders handled by each driver  

---

## 🚀 Possible Extensions
- Accounting module for profit tracking  
- Real-time map integration for delivery tracking  
- Multi-branch restaurant database

---

## 🔗 Resources
- [Oracle Academy](https://iacademy2.oracle.com/)
- [Oracle SQL Developer Documentation](https://www.oracle.com/database/sqldeveloper/)
