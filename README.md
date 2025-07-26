# 📚 Offline Library Management System (LMS)

Successfully developed an **Offline Library Management System (LMS)** for student use. This project enables users and administrators to manage book borrowing, returns, digital downloads, and user activity tracking — all without internet access.

---

## 🚀 Features

### 👨‍🎓 User Features
- Register and Login
- View available physical and digital books
- Download book PDFs
- Borrow and return books
- Track borrowing history

### 🛠️ Admin Features
- Secure Admin Login
- Add/Edit/Delete books (physical & digital)
- Upload and manage book PDFs
- View and manage user accounts
- Monitor borrowing and return records

---

## 🏗️ Tech Stack

- **PHP** (Core Logic)
- **MySQL** (Database)
- **HTML/CSS** (Frontend)
- **XAMPP** (Apache Server + MySQL)
- Fully **Offline Capable**

---

## 🖥️ Installation Steps

1. **Install XAMPP**  
   Download from [https://www.apachefriends.org](https://www.apachefriends.org) and install.

2. **Place Project Folder**  
   Extract and move the `hussy` folder to:


3. **Start Server**
- Launch XAMPP
- Start **Apache** and **MySQL**

4. **Import Database**
- Open [phpMyAdmin](http://localhost/phpmyadmin)
- Create a new database named `lms`
- Import the `lms.sql` file from the project folder

5. **Launch the App**  
Visit:  http://localhost/hussy/


---

## 🔐 Default Login Credentials

**Admin Login**  
- Username: `admin`  
- Password: `admin`

**User Login**  
- Username: `gigz6`  
- Password: `1234`  
- (New users can register)

---

## 📁 Project Structure

hussy/
├── dbconn.php
├── index.php
├── login.php
├── register.php
├── dashboard/
├── admin/
├── uploads/ # For PDFs
└── lms.sql # Database dump


---

## 📦 Key Benefits

- 100% **Offline** – works without internet access.
- Simple interface for both students and admins.
- Easy to customize and extend.
- Ideal for school libraries or personal cataloguing.

---

## 📃 License

This project is open for academic use. Feel free to modify and extend.

---

## 👨‍💻 Developer

**Name:** [Your Name]  
**Contact:** [Your Email or LinkedIn]  

