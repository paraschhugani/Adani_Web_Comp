
# Adani University Online Platform
A learning management and online assessment system for academic education.


## Features

- The administrator adds courses, teachers, and students, as well as assigns them courses.
- The teacher prepares course content, makes announcements, assigns homework and quizzes, takes attendance, and so on. A teacher can view the assessment details and analyses.
- Using the access key, students can enrol in courses, view course content, engage in tests, and view their outcomes in detail.
- A section for both the teacher and the student to discuss.


Login as admin and add some courses, teacher and students.

## Admin Login for Administration:  ( http://127.0.0.1:8000/admin )
Username : adani_admin

Password : qwertyuiop10


## Student Login for Usecase:    ( http://127.0.0.1:8000/login )
Id : 1234

Password: 12345

## Relational Schema
![schema](https://user-images.githubusercontent.com/87283264/187967219-55bea00e-3151-488a-a4be-d2a95b9d8a5c.png)

## Tech Stack
1. Django 4.0.4
2. Bootstrap 5.0.2
3. jQuery 3.6.0
5. Chart.js v3.9.1
4. Animate.css 4.1.1

## UI

User
- HOME PAGE

- ONLINE PORTAL LOG-IN

- PROFILE

- DASHBOARD

- DEPARTMENTS

- COURSES

- QUIZ

- COURSE DISCUSSION FORM

- PAYMENT

https://user-images.githubusercontent.com/51089028/206000544-a3f56687-d899-4843-b947-68cec8447a17.mov


ADMIN PORTAL 
  - LOGIN
  
  - ADMINISTRATION
  
  - ADMIN PAGE- QUIZ
  
  - ADMIN PAGE- STUDENT

## Run Locally

1. Clone the project
```bash
git clone https://github.com/nz-m/Adani_University-SWE.git
```
2. Go to the project directory
```bash
cd Adani_University-SWE
```
3. Create a virtual environment and activate it (Windows)
```bash
python -m venv env
```
```bash
env\Scripts\activate
```pip
4. Install dependencies

```bash
pip install -r requirements.txt
```
5. Make migrations and migrate
```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```
6. Create admin/superuser
```bash
python manage.py createsuperuser
```
7. Finally run the project
```bash
python manage.py runserver
```
Now the project should be running on http://127.0.0.1:8000/





