# 🩸 Blood Bank Management System (BBMS)

A full-featured **Blood Bank Management System** designed to streamline the management of blood donors, blood requests, and blood inventory for hospitals and donation centers. The system ensures safe, fast, and organized handling of blood-related data to support life-saving efforts.

## 📌 Key Features

- 🧑‍💼 Admin Dashboard for managing the entire system
- 🩸 Donor Registration and Blood Group Tracking
- 📦 Blood Inventory Management
- 🆘 Blood Request Handling (by patients or hospitals)
- 🔍 Search & Filter Donors by Blood Group, Location, or Availability
- 📅 Donation History Tracking
- 📧 Contact & Query Management System

---

## 🧱 System Architecture

- **Frontend:** HTML, CSS, JavaScript (optionally Bootstrap)
- **Backend:** PHP / Python / Node.js *(customizable)*
- **Database:** MySQL
- **Optional Tools:** phpMyAdmin, Apache (XAMPP/LAMP)

---

## 🗃️ Database Schema Overview

| Table Name             | Purpose                                                 |
|------------------------|----------------------------------------------------------|
| `tbladmin`             | Stores admin login credentials                          |
| `tblblooddonars`       | Holds detailed records of registered blood donors       |
| `tblbloodgroup`        | Reference table for all blood group types               |
| `tblbloodrequirer`     | Stores details of patients or hospitals requesting blood|
| `blood_request_log`    | Logs all historical blood requests                      |
| `activeblooddonors`    | View or table for actively available donors             |
| `tblcontactusinfo`     | Contact information for communication                   |
| `tblcontactusquery`    | Stores user-submitted contact or help queries           |
| `view_blood_requests`  | A database view for aggregated blood request details    |

---


