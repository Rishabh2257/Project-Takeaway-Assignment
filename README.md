# Project-Takeaway-Assignment
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Rishabh%20Raj-red)
---
## screenshots
### Homepage
![homepage snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/1.JPG)
### Admin Login
![dashboard snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/2.JPG)
### Admin Dashboard
![invoice snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/4.JPG)
### Admin Approval Panel
![doctor snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/5.JPG)
### Teacher Panel
![doctor snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/3.JPG)
### Teacher Dashboard
![homepage snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/10.JPG)
### Student Dashboard
![dashboard snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/11.JPG)
### Student Courses
![invoice snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/12.JPG)
### Exam Instructions
![doctor snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/14.JPG)
### Questions
![doctor snap](https://github.com/Rishabh2257/Project-Takeaway-Assignment/blob/main/static/screenshots/13.JPG)
---
## Functions
### Admin
- Create Admin account using command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Teacher
- Apply for job in System. Then Login (Approval required by system admin, Then only teacher can login).
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.
> **_NOTE:_**  Basically Admin Will Hire Teachers To Manage Courses and Questions.

### Student
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
---

## HOW TO RUN THIS PROJECT
- Install Python(3.9.6) 
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```
```

