# CollegeCloud

![GitHub repo size](https://img.shields.io/github/repo-size/rahul-jaiswar-git/CollegeCloud?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/rahul-jaiswar-git/CollegeCloud?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/rahul-jaiswar-git/CollegeCloud?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/rahul-jaiswar-git/CollegeCloud?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/rahul-jaiswar-git/CollegeCloud?style=for-the-badge)

> **CollegeCloud** is a modern, cloud-based College Management System built with Django. Streamline academic and administrative operations for colleges and universities with a powerful, user-friendly platform.

## What is CollegeCloud?

CollegeCloud is a web-based platform designed to simplify and automate the management of colleges and universities. It provides modules for handling students, staff, courses, attendance, results, notifications, and more. The system supports multiple user roles (Admin/HOD, Staff, Student) and offers a user-friendly interface for each.



### Key Features

- [x] User Registration and Authentication (Admin, Staff, Student)
- [x] Student, Staff, and Course Management
- [x] Attendance Tracking
- [x] Result Management
- [x] Leave and Feedback System
- [x] Notifications
- [x] Role-based Dashboards
- [x] Responsive UI with HTML templates

## 💻 Prerequisites

- Python 3.6+
- Django 3.1.1
- MySQL or PostgreSQL (or SQLite for development)
- pip (Python package manager)
- Git

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/rahul-jaiswar-git/CollegeCloud.git
cd CollegeManagement-Django
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Apply migrations and set up the database:
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser for admin access:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

## ☕ Usage

- Access the application at `http://127.0.0.1:8000/`
- Log in as Admin, Staff, or Student to access respective dashboards and features.
- Admin can manage students, staff, courses, sessions, and view reports.
- Staff can manage attendance, results, and communicate with students.
- Students can view attendance, results, notifications, and submit feedback/leave requests.

## 🛠️ Technology Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript (AdminLTE, Bootstrap)
- **Database**: MySQL, PostgreSQL, or SQLite
- **Deployment**: Gunicorn, Whitenoise (for static files)

## 🏗️ File Structure

```
CollegeManagement-Django/
├── college_management_system/   # Django project settings
├── main_app/                    # Main app logic, templates, static
├── media/                       # Uploaded media files
├── requirements.txt             # Python dependencies
├── manage.py                    # Django management script
├── Procfile                     # Deployment process file
├── LICENSE                      # Project license
Materials/                       # Project docs, images, and resources
```

## 📂 Materials Folder

All project-related documents, images, and resources are stored in the `Materials/` directory. This includes:
- Project reports (PDF, DOCX)
- System diagrams (JPG)
- Gantt charts, WBS, and other planning docs

## 🤝 Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/rahul-jaiswar-git" title="Rahul Jaiswar">
        <img src="https://avatars.githubusercontent.com/rahul-jaiswar-git" width="100px;" alt="Rahul Jaiswar's GitHub photo"/><br>
        <sub>
          <b>Rahul Jaiswar</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details. 