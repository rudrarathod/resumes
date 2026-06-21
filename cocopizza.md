# Cocopizza - Pizza Delivery & Restaurant Management Platform

### Full-Stack Food Ordering, POS, and Restaurant Operations System

---

## Project Overview

Cocopizza is a full-stack restaurant management platform developed for a pizza business, combining a customer-facing online ordering website with an integrated Point of Sale (POS) system. The platform streamlines restaurant operations by centralizing order management, inventory tracking, staff access control, and real-time order synchronization between customers and restaurant staff. Built using a client-server-database architecture, the system enables seamless communication between online ordering channels and in-store operations.

---

## Core Technologies

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB

### Authentication & Security

* JWT (JSON Web Tokens)
* Role-Based Access Control (RBAC)

### Real-Time Communication

* Socket.IO

### Architecture

* Client-Server Architecture
* Event-Driven Real-Time Updates

---

## Key Contributions & Engineering Challenges

### Engineered Real-Time Order Synchronization

* Designed and implemented a Socket.IO-based event system to synchronize online customer orders directly with the restaurant POS dashboard in real time.
* Eliminated manual order refresh workflows and reduced order visibility delays to near real-time performance (<1 second).

### Architected Automated Inventory Management

* Built inventory deduction logic integrated with menu items and order workflows.
* Automated stock updates whenever orders were confirmed, reducing manual inventory tracking efforts by approximately 80% and improving operational accuracy.

### Implemented Secure Multi-Role Access Control

* Developed JWT-based authentication and authorization mechanisms supporting Admin, Manager, Cashier, and Kitchen Staff roles.
* Protected critical APIs through middleware-driven permission validation, improving platform security and operational governance.

### Optimized Restaurant Operations Through Centralized Management

* Created a unified management system for menu administration, order processing, inventory monitoring, and staff workflows.
* Streamlined daily restaurant operations while reducing administrative overhead for business owners and employees.

### Developed Scalable Full-Stack Infrastructure

* Built and maintained 25+ RESTful API endpoints connecting customer-facing applications, POS systems, and backend services.
* Optimized database interactions and frontend rendering to ensure responsive performance during high-order activity periods.

---

## Key Architecture & Design Decisions

### Real-Time Event-Driven Communication with Socket.IO

Traditional polling approaches introduce delays and unnecessary server requests. Socket.IO was selected to enable bidirectional communication between customer applications and the POS system, allowing instant order notifications, status updates, and operational synchronization.

### MongoDB for Flexible Restaurant Data Management

MongoDB was chosen for its schema flexibility, enabling efficient management of orders, menu items, inventory records, staff profiles, and customer data. The document-oriented model simplified feature expansion and accelerated development without requiring complex schema migrations.

---

## System Architecture

```text
Client Layer (React)
├── Customer Ordering Website
├── Restaurant POS Dashboard
└── Administrative Management Panel

Backend Layer (Node.js + Express)
├── Authentication Service (JWT)
├── Order Management Service
├── Inventory Management Service
├── Staff & Role Management
└── Real-Time Event Processing (Socket.IO)

Database Layer (MongoDB)
├── Users
├── Orders
├── Menu Catalog
├── Inventory Records
└── Staff Roles
```

---

## Project Highlights

* Built a complete customer ordering website and restaurant POS ecosystem.
* Developed and maintained 25+ backend API endpoints.
* Implemented real-time order synchronization across multiple connected clients.
* Supported role-based access control for 4 distinct staff roles.
* Managed 100+ menu and inventory records through centralized administration tools.
* Reduced manual inventory tracking efforts by approximately 80%.
* Delivered sub-second order synchronization using WebSocket technology.

---

## Key Takeaways & Learnings

* Gained hands-on experience designing scalable real-time systems using WebSockets, event-driven architecture, and role-based security models.
* Strengthened expertise in full-stack application development, database design, operational automation, and production-grade restaurant management workflows.

---

**Role:** Full-Stack Developer
**Project Type:** Client Project
**Ownership:** 100% Individual Development
**Responsibilities:** Frontend Development, Backend Development, API Design, Database Modeling, Authentication, Real-Time Systems, POS Development, Inventory Management, Deployment & Maintenance
