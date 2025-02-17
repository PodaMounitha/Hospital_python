# 🏥 Hospital Management System

## 📌 Introduction
The **Hospital Management System** is a Python-based application that helps in managing hospital operations like patient admission, staff details, and administration. It uses **MySQL** as the database backend for storing and retrieving information.

## 📋 Features

✅ **User Authentication** - Sign Up and Sign In functionality for secure access.
✅ **Patient Management** - Admit and discharge patients.
✅ **Staff Management** - Maintain doctor, nurse, and worker details.
✅ **Administration Panel** - Add, view, and delete hospital staff records.
✅ **Database Integration** - Uses MySQL for data storage.

## 🛠️ Installation

### 1️⃣ Prerequisites
Make sure you have the following installed:
- Python 3.x 🐍
- MySQL Database 🗄️
- MySQL Connector for Python (`mysql-connector-python`)

### 2️⃣ Setting Up MySQL
1. Open MySQL and create a database (it will be created automatically if not present).
2. Ensure you have a MySQL user with appropriate privileges.

### 3️⃣ Installing Dependencies
Run the following command to install MySQL connector:
```sh
pip install mysql-connector-python
```

### 4️⃣ Running the Application
Execute the Python script:
```sh
python hospital_management.py
```

## 📌 Usage Guide

1️⃣ **Run the script** and enter your MySQL database password.
2️⃣ Choose an option:
   - **Sign Up** (Register as a new user)
   - **Sign In** (Login with existing credentials)
3️⃣ Navigate through:
   - **Administration Panel** for managing staff
   - **Patient Management** for handling admissions and discharges
   - **Sign Out** to exit

## 📂 Database Structure

| Table Name | Description |
|------------|-------------|
| `patient_details` | Stores patient information (ID, Name, Age, Address, Doctor Recommended) |
| `doctor_details` | Stores doctor details (Name, Specialization, Age, Address, Contact, Fees, Salary) |
| `nurse_details` | Stores nurse details (Name, Age, Address, Contact, Salary) |
| `other_workers_details` | Stores other hospital workers' details |
| `user_data` | Stores user credentials for authentication |

## 📢 Contributing
Want to improve this project? Contributions are welcome! Feel free to fork this repository and make a pull request.

## 🏆 Credits
Developed by **[Your Name]** 🧑‍💻

## ⚖️ License
This project is licensed under the **MIT License**. 📝

