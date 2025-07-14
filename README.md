# Thushari Vision House - Hospital Management System

## 🏥 Project Overview

TVH Hospital Management System is a comprehensive web-based application designed to streamline healthcare operations, improve patient care, and optimize administrative workflows. This project was developed as part of the Information Systems community project Department of Computing and information Systems , faculty of computing Sabaragamuwa University of Sri Lanka.

## ✨ Features

### 🧑‍⚕️ For Patients

- **Online Appointment Booking:** Schedule appointments with preferred doctors
- **Medical History Access:** View personal medical records and history
- **User Authentication:** Secure login and profile management
- **Contact Portal:** Easy communication with healthcare providers

### 👨‍⚕️ For Doctors

- **Appointment Management:** View and manage upcoming appointments
- **Patient Records:** Access patient medical histories
- **Treatment Documentation:** Record diagnoses and treatment plans
- **Schedule Management:** Manage availability and working hours

### 👩‍💼 For Administrators

- **Staff Management:** Add, update, or remove doctors and staff
- **Department Configuration:** Manage hospital departments
- **Analytics Dashboard:** Track key hospital metrics
- **System-wide Reports:** Generate comprehensive reports

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Server Environment:** XAMPP
- **Additional Libraries:**
  - jQuery for enhanced interactivity
  - Font Awesome for icons
  - Chart.js for analytics visualization

## 📋 System Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- XAMPP or similar AMP stack
- Modern web browser (Chrome, Firefox, Edge, Safari)

## 🚀 Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/hospital-management-system.git
```

2. Set up the database

```bash
# Import the database schema
mysql -u username -p < database/hms.sql
```

3. Configure database connection

```bash
# Edit the database configuration in src/hms/include/config.php
```

4. Move to your web server directory

```bash
# For XAMPP
mv hospital-management-system /path/to/xampp/htdocs/
```

5. Access the application

```
http://localhost/hospital/public/index.php
```

<!-- ## 📸 Screenshots

<div style="display: flex; justify-content: space-between;">
    <img src="path/to/screenshot1.png" alt="Homepage" width="30%">
    <img src="path/to/screenshot2.png" alt="Dashboard" width="30%">
    <img src="path/to/screenshot3.png" alt="Appointment" width="30%">
</div> -->

## 👥 User Roles & Access

| Role    | Access Level | Description                              |
| ------- | ------------ | ---------------------------------------- |
| Patient | Basic        | Book appointments, view medical history  |
| Doctor  | Intermediate | Manage patients, update medical records  |
| Admin   | Full         | System-wide management and configuration |

## 🔒 Security Features

- Password encryption
- Session management
- Input validation
- Protection against SQL injection
- Cross-site scripting (XSS) prevention

## 📊 Project Structure

```
hospital/
├── public/           # Public-facing website
├── src/              # Application backend code
│   └── hms/          # Core hospital management system
├── database/         # Database scripts and backups
├── assets/           # Shared assets (CSS, JS, images)
└── docs/             # Documentation
```

## 🔮 Future Enhancements

- Mobile application integration
- Telemedicine functionality
- Advanced analytics and reporting
- Electronic prescription system
- Patient billing and insurance integration

## 📝 License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.

---

Developed with ❤️ by the IS Community Project Team | Sabaragamuwa University of Sri Lanka © 2025
