# Integrated Academics Management System

## Project Overview
Integrated Academics Management System is a university-level web platform designed to manage academic operations efficiently using role-based access control.

The system allows the Main Assistant to manage departments and provide access to Department Assistants. Each department independently manages faculty, students, academic resources, and semester timetables without interfering with other departments.

Students can access timetables and download academic materials such as syllabus documents and previous question papers.

---

## Features

- Role-based authentication and authorization
- Department-wise isolated management system
- Faculty and student management
- Semester timetable generation
- Upload and download syllabus materials
- Previous question paper management
- Student academic resource access
- Secure MySQL database integration

---

## Tech Stack

- Python
- Django
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap

---

## Project Structure

```bash
Integrated-Academics--Management-System/
│
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── screenshots/
├── templates/
├── static/
└── application_files/
```

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/shanthipriyajana-web/Integrated-Academics--Management-System.git
cd Integrated-Academics--Management-System
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Configure MySQL Database

Create a MySQL database:

```sql
CREATE DATABASE academics_management_system;
```

Set the following environment variables:

```env
MYSQL_DATABASE=academics_management_system
MYSQL_USER=root
MYSQL_PASSWORD=
MYSQL_HOST=127.0.0.1
MYSQL_PORT=3306
```

---

### 4. Run Migrations

```bash
python manage.py migrate
```

---

### 5. Start Development Server

```bash
python manage.py runserver
```

---

## Default Database Configuration

If environment variables are not configured, Django uses:

- Database: `academics_management_system`
- User: `root`
- Password: empty
- Host: `127.0.0.1`
- Port: `3306`

---

## Screenshots

### Login Page
(Add screenshot here)

### Dashboard
(Add screenshot here)

### Timetable Module
(Add screenshot here)

---

## Future Improvements

- AI-based timetable optimization
- Attendance analytics dashboard
- Email notification system
- Mobile responsive interface
- Cloud deployment support

---

## Author

Shanthipriya Jana

GitHub:
https://github.com/shanthipriyajana-web