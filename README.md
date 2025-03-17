# 🎯 Laravel Employee Management System

## 📌 Requirements
This project is a **Laravel-based web application** featuring a simple authentication system and an **employee management module**.

---
## 🚀 Features

### 🔐 1. Authentication System
✅ Uses Laravel's built-in authentication (`php artisan make:auth`) or Laravel Breeze/Sanctum.  
✅ Login, Register, Logout functionality.  
✅ Middleware to protect employee pages.  

---
### 👨‍💼 2. Employee Management
**Employees Table Includes:**
📌 `id` (Primary Key)  
📌 `name` (Text Input)  
📌 `email` (Email Input)  
📌 `phone` (Number Input)  
📌 `department` (Dropdown Select: IT, HR, Sales, etc.)  
📌 `position` (Text Input)  
📌 `salary` (Number Input)  
📌 `joining_date` (Date Picker)  
📌 `status` (Radio: Active/Inactive)  
📌 `profile_picture` (File Upload)  
📌 `created_at` and `updated_at` timestamps  

---
### ⚙️ 3. CRUD Operations

#### ➕ Create Employee:
📝 Form with all fields.  
📂 File upload for profile picture.  
🛢️ Store in database.  

#### 📋 View Employee List:
📊 Paginated table with employee details.  
🖼️ Profile picture preview.  

#### ✏️ Edit Employee:
🛠️ Pre-filled edit form with existing data.  
🔄 Update database on submission.  

#### 🗑️ Delete Employee:
⚠️ Confirmation prompt before deletion.  

---
### 🎯 Additional Requirements
✅ **Validation:** Proper validation for each field.  
✅ **UI:** Clean Bootstrap/Tailwind UI.  
✅ **Routes & Controllers:** Uses Laravel resource controllers (`php artisan make:controller EmployeeController --resource`).  
✅ **Database Migration & Model:** Creates migration and model for Employee (`php artisan make:model Employee -m`).  

---
## 💻 Tech Stack
- 🏗 **Laravel** (Latest Version)
- 🗄 **MySQL** (Database)
- 🎨 **Bootstrap/Tailwind** (Frontend)
- 🔑 **Laravel Breeze** for Authentication

---
## 📜 Pages Overview

### 🔑 1. Login Page
**Route:** `/login`  
📧 Email & password fields with validation.  
✅ "Remember me" checkbox.  
🔗 "Forgot password?" link.  
🆗 Submit button.  

### 📝 2. Register Page
**Route:** `/register`  
👤 Name, Email, Password, Confirm Password fields.  
🆗 Submit button.  
🔗 Link to Login.  

### 📊 3. Dashboard Page
**Route:** `/dashboard`  
👋 Welcome message with logged-in user’s name.  
📌 Navigation menu with links to Employee List and Logout.  

### 📜 4. Employee List Page
**Route:** `/employees`  
📊 Table with columns: Name, Email, Phone, Department, Position, Salary, Status, Actions.  
🛠 Actions: **Edit & Delete buttons.**  
📌 Pagination for large datasets.  

### ➕ 5. Create Employee Page
**Route:** `/employees/create`  
📑 Form with all required fields.  
📂 File upload for profile picture.  

### ✏️ 6. Edit Employee Page
**Route:** `/employees/{id}/edit`  
🛠 Similar to "Create Employee" but with pre-filled values.  

### 🗑️ 7. Delete Confirmation Modal
⚠️ Displays a confirmation message before deleting an employee.  
✅ "Yes, Delete" and "Cancel" buttons.  

---
## 🎉 Final Thoughts
This **Laravel Employee Management System** provides:
✅ **Clean authentication pages**  
✅ **Well-structured CRUD pages for employees**  
✅ **A simple but effective UI for user interactions**  

Would you like Blade template structure for these pages? 🚀
