# 🍕 Roman's Pizza Ordering & Delivery App

> Developed by **XDev Studios** | © 2025 Roman's Pizza. All rights reserved.

---

## 📱 Overview

The **Roman's Pizza Ordering & Delivery App** is a modern, responsive, and user-friendly platform that transforms the pizza ordering experience. Developed for both web and mobile platforms, this app allows customers to browse the menu, customize their pizzas, place orders, track deliveries, leave reviews, and play games to win promotions.

---

## 🧠 Key Features

### 🔹 Customer-Facing Features
- 🛒 Online ordering with pizza customization
- 🔄 Live delivery tracking
- 🎮 Gamification to win discounts
- ⭐ Review & rating system
- 🔐 Secure login, order history, and reordering

### 🔹 Admin Panel
- 📦 Manage orders, menu items, and inventory
- 📊 View customer feedback and ratings
- 🎯 Launch promotions and marketing campaigns
- 👥 Oversee delivery assignments and logistics

### 🔹 Delivery Driver Module
- 🚚 Receive and accept delivery requests
- 📍 Real-time navigation and status updates

---

## 🏗️ Architecture

- **3-Tier Architecture**: Customer UI, Staff/Admin Dashboard, Backend Database
- **Database Normalization**: Follows 3NF for optimal performance
- **Technology Stack**:  
  - Frontend: Figma (design), HTML/CSS/JS (optional for implementation)  
  - Backend: .NET Core / SQL  
  - Tools: MS Teams, WhatsApp, GitHub, Agile boards

---

## 📂 Core Modules

| Module             | Description                                                  |
|--------------------|--------------------------------------------------------------|
| Customer Portal     | Registration, ordering, customization, reviews, games       |
| Admin Dashboard     | Order management, promotion tools, inventory, reporting     |
| Delivery System     | Assignments, real-time tracking, status updates             |
| Gamification Engine | Mini-games for user engagement and rewards                  |

---

## 🧾 Database Design

**Core Tables**:  
- `Customer`, `Staff`, `Order`, `MenuItem`, `Payment`, `Delivery`, `Driver`, `OrderItem`  
- **Relationships**:  
  - One-to-Many: Customer → Orders  
  - Many-to-Many: Orders ↔ MenuItems (via OrderItem)  
  - One-to-One: Order → Payment  
  - One-to-Many: Driver → Deliveries  

---

## 🎯 Business Value

- **Improved customer experience** through delivery tracking and customization
- **Increased sales** via promotions and gamified user engagement
- **Better operations** with real-time logistics and centralized management

---

## 👥 Team

| Role                     | Member                     |
|--------------------------|----------------------------|
| Project Manager          | Ayanda Mantshinga (ST10161370) |
| Lead Developer           | Tshepo Motloung (ST10127853)   |
| Analyst & Designer       | Fikile Sekati (ST10158923)     |

---

## 📚 References

- Chaffey, D. (2022). *Digital Business and E-commerce Management*. Pearson.  
- Laudon, K. & Traver, C. (2021). *E-commerce 2021: Business, Technology, Society*. Pearson.  
- Statista (2023). Online Food Delivery. [statista.com](https://www.statista.com)  
- YouTube (2025). *PERT Chart Tutorial*. [Watch Video](https://youtu.be/6S6zfbq2vcE)


---

## 🛡️ License

© 2025 Roman's Pizza. All rights reserved.  
*App developed by XDev Studios (independent contractor).*


