# 🎓 Student Management System

## 🌟 Live Demo
🔗 [https://universitymanagement.wuaze.com/](https://universitymanagement.wuaze.com/)

## 📌 Project Overview
A comprehensive web-based Student Management System designed to streamline academic administration, featuring robust user roles, attendance tracking, course management, and real-time reporting capabilities.

<img width="1180" height="903" alt="image" src="https://github.com/user-attachments/assets/eee04ae0-124c-4b0a-980e-c24554c41bba" />


## ✨ Key Features

### 👨‍💻 Role-Based Access Control
- **Admin Panel**: Full system control with user, course, and transport management
- **Teacher Portal**: Attendance tracking and grade management
- **Student Dashboard**: Course enrollment and academic tracking

### 📊 Core Modules
- **Student Management**: Comprehensive student profiles and records
<img width="717" height="889" alt="image" src="https://github.com/user-attachments/assets/7fb669e1-d174-43e5-b027-66b4799c85bd" /><img width="672" height="754" alt="image" src="https://github.com/user-attachments/assets/6a24e3d0-c8c7-4ba3-b237-c7bafe7bb2e8" />
<img width="994" height="912" alt="image" src="https://github.com/user-attachments/assets/14e3dd98-154d-4784-9f5a-b404b0aae92f" /><img width="1184" height="1280" alt="image" src="https://github.com/user-attachments/assets/326583d0-1c4b-41cd-ae4e-fe36fbe34cfa" />
<img width="1180" height="903" alt="image" src="https://github.com/user-attachments/assets/4fd0ef56-0095-43c9-886e-dc9cd30b2a6c" /><img width="1233" height="901" alt="image" src="https://github.com/user-attachments/assets/b2a2e5e6-9589-470c-b397-84426b2f190a" />
<img width="1101" height="1280" alt="image" src="https://github.com/user-attachments/assets/416a3e75-ac52-45d3-ab9a-d549748b039b" />


- **Course Administration**: Enrollment, scheduling, and capacity management
<img width="951" height="587" alt="image" src="https://github.com/user-attachments/assets/1adc9f45-68fc-43ec-b095-434724775865" />

- **Attendance System**: Real-time tracking with status reporting
<img width="1280" height="413" alt="image" src="https://github.com/user-attachments/assets/de7018ae-2b6e-4de1-bbe7-77f94b543a8a" />
<img width="1072" height="767" alt="image" src="https://github.com/user-attachments/assets/b2397d7d-439d-4c4d-88eb-1abd32a8b6b8" /><img width="1019" height="881" alt="image" src="https://github.com/user-attachments/assets/65ad86e1-accd-442e-88b9-11dfef3e25ba" />


- **Academic Calendar**: Event scheduling with visual uploads
<img width="1280" height="728" alt="image" src="https://github.com/user-attachments/assets/fa4f1e84-33d5-4074-91d8-7c3cdb729ac5" />
<img width="1164" height="867" alt="image" src="https://github.com/user-attachments/assets/b0634bd1-00d4-46eb-963c-5cb496cc9f77" />
<img width="804" height="883" alt="image" src="https://github.com/user-attachments/assets/9322f4e2-2440-437d-a3ef-d5d1ff9becc9" />

- **Transport Management**: Route scheduling with image support
<img width="1228" height="1198" alt="image" src="https://github.com/user-attachments/assets/eb80e4d5-924e-4ff5-a65d-56aa799a3c8f" />

- **Reporting**: Automated statistics and analytics

## 🛠 Technology Stack

### Frontend
- **Tailwind CSS** for responsive, modern UI
- **Alpine.js** for interactive components
- **Chart.js** for data visualization

### Backend
- **PHP 8.1+** with MySQLi for database operations
- **Secure Authentication**: Password hashing with PHP password_hash()
- **Session Management**: Role-based access control

### Database
- **MySQL** relational database
- Optimized schema for academic operations


## 🚀 Technologies Used

* **Frontend**: HTML, CSS, JavaScript, Bootstrap
* **Backend**: PHP, Node.js
* **Database**: MySQL
* **Version Control**: Git, GitHub

---


## 🚀 Installation Guide

### Prerequisites

* PHP 7.4 or higher
* MySQL 5.7 or higher
* Apache/Nginx server
* Composer (for PHP dependencies)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/university-management-system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd university-management-system
   ```

3. Set up the database:

   * Create a new database in MySQL:

     ```sql
     CREATE DATABASE ums;
     ```

   * Import the database schema:

     ```bash
     mysql -u root -p ums < database_schema.sql
     ```

4. Configure environment variables:

   * Copy the `.env.example` file to `.env`:

     ```bash
     cp .env.example .env
     ```

   * Update the `.env` file with your database credentials and other settings.

5. Install PHP dependencies:

   ```bash
   composer install
   ```

6. Set up the web server:

   * Configure your Apache/Nginx server to point to the `public` directory.

7. Access the application:

   * Open your browser and navigate to `http://localhost/ums/public`.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your proposed changes.

---

## 📞 Contact

For support or inquiries, please contact:

* Email: [mailto:ashabulyamintuhin@gmail.com]
* GitHub: [https://github.com/infernoYam1n/studentmanagement]

---

Feel free to customize this template further to match the specific features and technologies of your University Management System.
