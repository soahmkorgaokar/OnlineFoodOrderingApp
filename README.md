# 🍔 Online Food Ordering System – Spring Boot, Angular & MySQL

A full-stack online food ordering system that implements the **MVC (Model-View-Controller)** architecture. The frontend is built with **Angular 8**, the backend uses **Spring Boot**, and data is stored in a **MySQL** database. This project supports both **users** (customers) and **merchants**, offering login, food ordering, and menu management features.

## 🎯 Project Overview

- Built using a RESTful architecture to enable smooth communication between the Angular frontend and Spring Boot backend
- Users can register/login, browse food items, place orders, and make payments
- Merchants can log in and manage the menu dynamically
- Real-time updates with no page refresh required after inventory updates

## ✅ Features

### User Module
- Login and registration with validation
- Browse menu items and view available quantities
- Add items to cart and proceed to checkout
- Enter card details and complete payment
- Purchased items update the database automatically

### Merchant Module
- Login and registration as merchant
- View merchant-specific dashboard with editable menu
- Add or update item quantities
- Real-time updates without page refresh

## 🧰 Technologies Used

- **Frontend**: Angular 8 (port `4200`)  
- **Backend**: Spring Boot v2.1.6 (port `8080`)  
- **Database**: MySQL (port `3306`)  
- **JPA (Java Persistence API)** for business logic  
- **RESTful APIs** for client-server communication
