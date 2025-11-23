# 🎓 Interactive Online Learning & Exam System

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.2.3-green?logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/Database-SQLite-orange?logo=sqlite&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-4.5.2-purple?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%2312100E?logo=github&logoColor=white)


Welcome to Interactive Online Learning & Exam System – a playful, hands-on project built with Django! 🐍💻

This project is designed as a web-based course management and assessment platform where learners can enroll in courses, take lessons, attempt quizzes/exams, and track their scores.

## 📝 About This Project

Welcome to Interactive Online Learning & Exam System! This project is part of the IBM Django Application Development with SQL & Databases course in the IBM Full Stack Software Professional Certificate Program.

Designed for fun and functionality, this application allows learners to:

- Enroll in courses with a single click 📝

- Browse lessons and course content in a clean, responsive interface 📚

- Take multiple-choice exams with multiple correct answers ✔️

- See instant results with detailed feedback, scores, and a pass/fail summary 🎉/💀

---------------------------

## ✨ Features

- **User Authentication:** Login, Logout, and Registration

- **Instructor/Admin Management:** Add/edit courses, lessons, and questions

- **Interactive Exams:** Multiple-choice, multi-select quizzes

- **Submission Evaluation:** Automatic scoring and pass/fail notifications

- **Bootstrap 4 UI:** Clean, responsive, and mobile-friendly design


----------------------

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/online-learning-exam.git
cd online-learning-exam
```

Create a virtual environment:

```bash
python3 -m venv djangoenv
source djangoenv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Make migrations and migrate:

```bash
python manage.py makemigrations
python manage.py migrate
```

Create superuser for admin:

```bash
python manage.py createsuperuser
```

Run the development server:

```bash
python manage.py runserver
```


Open your browser at http:```//127.0.0.1:8000/``` and start exploring! 🚀

--------------------

## 🏗 Project Structure

```
onlinecourse/
│
├── models.py         # Course, Lesson, Instructor, Learner, Question, Choice, Submission
├── views.py          # Enroll, Submit Exam, Show Results
├── admin.py          # Admin interface customizations
├── urls.py           # Routes
└── templates/onlinecourse/
      ├── course_details_bootstrap.html
      ├── exam_result_bootstrap.html
      └── ... other templates
```

------------------------------------

## 👨‍💻 Author

### Umme Sanjeda

GitHub: [https://github.com/usan-here](https://github.com/usan-here)


## 🧩 Contributing
We love collaboration! 🤝
- Feel free to fork the repository and experiment with new features
- Share your improvements via Pull Requests
- Respect the existing structure and add meaningful commits


## 📄 License

This project is licensed under the Apache License 2.0 – see the LICENSE
 file for details.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
