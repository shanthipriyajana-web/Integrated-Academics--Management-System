# Integrated-Academics--Management-System
Integrated Academics Management System is a university-level platform with role-based access. The Main Assistant manages departments and grants access to Department Assistants. Departments manage faculty, students, generate semester timetables, and upload syllabus and previous papers. Students can view timetables and download academic resources.

## MySQL setup
This project is configured to use MySQL instead of SQLite.

1. Install dependencies:
   `pip install -r requirements.txt`
2. Create a MySQL database:
   `CREATE DATABASE academics_management_system;`
3. Set these environment variables before running Django:
   `MYSQL_DATABASE`
   `MYSQL_USER`
   `MYSQL_PASSWORD`
   `MYSQL_HOST`
   `MYSQL_PORT`
4. Run migrations:
   `python manage.py migrate`
5. Start the server:
   `python manage.py runserver`

If you do not set the environment variables, Django uses these defaults:
- Database: `academics_management_system`
- User: `root`
- Password: empty
- Host: `127.0.0.1`
- Port: `3306`
