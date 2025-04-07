# School Management System

A web-based application built using Django to manage school operations efficiently. This system provides features for administrators, teachers, and students, enabling seamless management of tasks like attendance, fee tracking, and notices.

## Features

### Admin
- Manage teachers and students (add, update, delete, approve).
- Track attendance and fees for students.
- Post notices for teachers and students.
- View teacher salaries and student fee details.

### Teacher
- Manage attendance for students.
- View notices posted by the admin.
- Post notices for students.

### Student
- View attendance records.
- Access notices from teachers and admin.
- View fee details.

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite
- **Other Tools**: Django Widget Tweaks

## HOW TO RUN THIS PROJECT
Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
Open Terminal and Execute Following Commands :
python -m pip install -r requirements.txt

## Download This Project Zip Folder and Extract it
#### Move to project folder in Terminal. Then run following Commands :
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
### Now enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:8000/
#### CHANGES REQUIRED FOR CONTACT US PAGE
In settins.py file, You have to give your email and password
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'


1. Clone the repository:
   ```bash
   git clone https://github.com/deepti-50/School-Management-System.git
   cd School-Management-System

