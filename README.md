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
- **Super Admin** and **Tester Admin** roles with extended permissions

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

### 📧 Email Notifications
- Automatic email sent to the **assigned developer** when a new defect is added.  
- Notifications include defect details such as:
  - Defect Name
  - Assigned By
  - Priority
  - Status  
- Ensures developers are immediately informed of new assignments.


---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python (Django)
- **Database:**  SQLite
- **Authentication:** Django

---

## 🛠️ screenshots
<img width="1360" height="631" alt="Screenshot 2025-08-24 214517" src="https://github.com/user-attachments/assets/2efac51c-ff5f-4e40-8a04-288e6c7a45f5" />
<img width="1184" height="630" alt="Screenshot 2025-08-24 214610" src="https://github.com/user-attachments/assets/cfc5cfdf-a65c-4bc7-b406-ecfd13083b06" />
<img width="1344" height="595" alt="Screenshot 2025-09-21 212049" src="https://github.com/user-attachments/assets/075b1fb4-ce3d-46ec-8b52-62f6ff42b2fa" />
<img width="1340" height="630" alt="Screenshot 2025-08-24 214726" src="https://github.com/user-attachments/assets/e9e1d478-622b-4803-bb7b-964d17d56cbf" />
<img width="1351" height="627" alt="Screenshot 2025-08-24 214754" src="https://github.com/user-attachments/assets/d8a4115e-fa4c-48d5-97bb-31ac61365418" />


-- end --
