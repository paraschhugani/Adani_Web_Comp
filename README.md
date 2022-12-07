
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

<img width="600" alt="Screenshot 2022-12-07 at 11 55 53 AM" src="https://user-images.githubusercontent.com/51089028/206104704-f607b8a2-bcb7-4d3a-aeb3-f6c5441bd4a9.png">

## Tech Stack
1. Django 4.0.4
2. Bootstrap 5.0.2
3. jQuery 3.6.0
5. Chart.js v3.9.1
4. Animate.css 4.1.1

## UI

User
- HOME PAGE
<img width="600" alt="Screenshot 2022-12-07 at 11 45 38 AM" src="https://user-images.githubusercontent.com/51089028/206102842-f24aafe7-f956-4709-8a3a-945c56070054.png">

- ONLINE PORTAL LOG-IN
![Uploading Screenshot 2022-12-07 at 11.46.07 AM.png…]()

- PROFILE
<img width="600" alt="Screenshot 2022-12-07 at 11 47 26 AM" src="https://user-images.githubusercontent.com/51089028/206103150-45456bf7-fe9f-45aa-9fc3-f7722c05388b.png">

- DASHBOARD
<img width="600" alt="Screenshot 2022-12-07 at 11 47 48 AM" src="https://user-images.githubusercontent.com/51089028/206103207-ad41a3f7-7808-4a28-b108-1a0b6ed04915.png">

- DEPARTMENTS

<img width="600" alt="Screenshot 2022-12-07 at 11 48 55 AM" src="https://user-images.githubusercontent.com/51089028/206103398-4f6264af-0d24-4b36-b1e7-aab8155bf467.png">

- COURSES
<img width="600" alt="Screenshot 2022-12-07 at 11 49 11 AM" src="https://user-images.githubusercontent.com/51089028/206103441-f6ca17ce-ccad-4e27-8210-7b2eecc2931d.png">

- QUIZ
<img width="600" alt="Screenshot 2022-12-07 at 12 12 53 AM" src="https://user-images.githubusercontent.com/51089028/206103515-501e83cf-1740-4b11-957c-ed55da4dd137.png">


- PAYMENT

https://user-images.githubusercontent.com/51089028/206000544-a3f56687-d899-4843-b947-68cec8447a17.mov

Teacher

- Quiz Analysis

 <img width="600" alt="Screenshot 2022-12-07 at 12 22 11 AM" src="https://user-images.githubusercontent.com/51089028/206104089-f22b8cf4-3fdf-41f8-94b6-bc16f1b0d2b6.png">



ADMIN PORTAL 
  - LOGIN
  <img width="600" alt="Screenshot 2022-12-07 at 11 50 44 AM" src="https://user-images.githubusercontent.com/51089028/206103715-841fcdbf-28e8-4ee4-af61-035d3f8525c3.png">

  - ADMINISTRATION
  <img width="600" alt="Screenshot 2022-12-07 at 11 51 11 AM" src="https://user-images.githubusercontent.com/51089028/206103859-e4778544-234e-4bfa-b66f-c61fc864ba1a.png">

  - ADMIN PAGE- QUIZ
  <img width="600" alt="Screenshot 2022-12-07 at 11 51 31 AM" src="https://user-images.githubusercontent.com/51089028/206103925-0e579402-6874-4115-88ba-75e86d8db67b.png">

  - ADMIN PAGE- STUDENT
<img width="600" alt="Screenshot 2022-12-07 at 11 52 01 AM" src="https://user-images.githubusercontent.com/51089028/206104014-1f934566-b75b-44c4-9a61-6c7a5350d978.png">

## Run Locally

1. Clone the project
```bash
git clone https://github.com/paraschhugani/Adani_Web_Comp.git
```
2. Go to the project directory
```bash
cd Adani_Web_Comp
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

6. Finally run the project
```bash
python manage.py runserver
```
Now the project should be running on http://127.0.0.1:8000/





