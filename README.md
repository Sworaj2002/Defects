# Defects
A web-based Defect Management System built with Django to track, filter, and manage software defects. Supports role-based access for developers, testers, admins, and super admins. Features include defect filtering by developer, profile management, analytics, and CRUD operations for efficient bug resolution.
# 🐞 Defects Management System

A web-based application to manage and track software defects effectively.  
This system provides role-based access for developers, testers, admins, and a super admin,  
ensuring streamlined defect tracking and resolution.

---

## 🚀 Features

### 🔐 Authentication & User Roles
- **Register & Login** functionality for:
  - Developers
  - Testers
- **Super Admin** and **Tester Admin** roles with extended permissions.

### 🧾 Defects Management
- **List of All Defects** in a centralized table.
- Each defect record includes:
  - Defect ID
  - Defect Name
  - Assigned By
  - Assigned To
  - Description
  - Defect Status
  - Priority
  - Edit
  - Delete
  - Assigned Date
- **Filtering** of defects based on developer name.
- **Add**, **Edit**, and **Delete** defects (accessible to Super Admin & Tester Admin).

### 📊 Status Tracking
- View **Completed Defects**.
- View **Pending Defects**.

### 👤 Profile Management
- Update personal profile information.
- Developers can view:
  - Total defects assigned to them.
  - Pending defects.
  - Completed defects.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python (Django)
- **Database:**  SQLite
- **Authentication:** Django

---


