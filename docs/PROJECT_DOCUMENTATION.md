# 📘 Student Management System – Project Documentation

## 📖 Overview
The **Student Management System (SMS)** is a Salesforce mini-project that demonstrates core **Admin and Developer concepts**.  
It allows educational institutions to manage **students, courses, and enrollments** efficiently.

---

## 🎯 Objectives
- Centralized platform for storing and managing student information.  
- Track courses, subjects, and enrollment records.  
- Generate reports and dashboards for academic insights.  
- Showcase Salesforce skills: **Objects, Flows, SOQL, Apex**.

---

## 🏗️ System Architecture
### Entities
- **Student** → Student details (Name, Email, Phone, Enrollment ID).  
- **Course** → Course details (Name, Duration, Fee).  
- **Enrollment** → Junction object linking Student ↔ Course.  
- **Faculty (Optional)** → Faculty details.

---

## ⚡ Features
- **Custom Objects & Fields** for Students, Courses, Enrollments.  
- **Record Types & Page Layouts** for UG/PG courses.  
- **Validation Rules** for data accuracy (e.g., valid email).  
- **Flows** for automating course assignments.  
- **Reports & Dashboards** for insights.  
- **Apex Triggers (future scope)** for custom logic.

---

## 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/salesforce-student-management-system.git
