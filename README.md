# ✈️ TravelMate

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-3.1-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

<h3 align="center">
🌍 Plan Smarter • Travel Better • Explore More
</h3>

<p align="center">
TravelMate is a full-stack travel planning web application developed using Django. It enables users to register, log in securely, explore destinations, browse hotels and villas, and manage travel plans through a clean, responsive, and user-friendly interface.
</p>

---

# 🌐 Live Demo

🔗 https://travelmate-tnvp.onrender.com

---

# 📚 Table of Contents

- Features
- Tech Stack
- Technical Highlights
- Project Preview
- Architecture
- Application Workflow
- Project Structure
- Installation
- Future Enhancements
- Learning Outcomes
- About the Developer
- License

---

# 📌 Features

- 🔐 User Registration & Login
- 🔒 Django Session Authentication
- 🏨 Browse Hotels & Villas
- 🌍 Explore Tourist Destinations
- ✈️ Plan and Manage Trips
- 📋 Personalized User Dashboard
- 📱 Responsive User Interface
- ⚡ CRUD Operations using Django ORM
- 🗄️ SQLite Database Integration
- 🎯 Clean Navigation & User Experience

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Backend | Python, Django |
| Frontend | HTML5, CSS3, JavaScript |
| Database | SQLite3 |
| ORM | Django ORM |
| Version Control | Git & GitHub |

---

# 🚀 Technical Highlights

- Django Authentication System
- Session Management
- CRUD Operations
- Django ORM
- URL Routing
- Template Rendering
- Static File Management
- Responsive Web Design
- MVC (MVT) Architecture
- SQLite Database Integration

---

# 📸 Project Preview

## 🏠 Home Page

<p align="center">
<img src="screenshots/home-dashboard.png" width="900">
</p>

---

## 🔐 Authentication

| Sign Up | Login |
|----------|--------|
| <img src="screenshots/signup.png"> | <img src="screenshots/login.png"> |

---

## 🌍 Destinations

<p align="center">
<img src="screenshots/destinations.png" width="900">
</p>

---

## 🏨 Hotels & Villas

<p align="center">
<img src="screenshots/hotels.png" width="900">
</p>

---

## 📋 Dashboard

<p align="center">
<img src="screenshots/dashboard-1.png" width="280">
<img src="screenshots/dashboard-2.png" width="280">
<img src="screenshots/dashboard-3.png" width="280">
</p>

---

# 🏗️ Architecture

```text
User
   │
   ▼
Browser
   │
   ▼
HTML • CSS • JavaScript
   │
   ▼
Django URL Dispatcher
   │
   ▼
Views
   │
   ▼
Django ORM
   │
   ▼
SQLite Database
```

---

# 🔄 Application Workflow

```text
Register
      │
      ▼
User Details Stored
      │
      ▼
Login
      │
      ▼
Django Authentication
      │
      ▼
Session Created
      │
      ▼
Access Dashboard
      │
      ▼
Browse Destinations
      │
      ▼
Manage Travel Plans
      │
      ▼
Logout
```

---

# 📂 Project Structure

```text
TravelMate/
│
├── accounts/
├── static/
├── templates/
├── travel/
├── tripplanner/
├── .gitignore
├── manage.py
├── README.md
└── requirements.txt
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/AkshaykumarSanti/TravelMate.git
```

Move into the project directory

```bash
cd TravelMate
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment (Windows)

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

Create admin user (optional)

```bash
python manage.py createsuperuser
```

Run server

```bash
python manage.py runserver
```

Open

```text
http://127.0.0.1:8000/
```

---

# 🚀 Future Enhancements

- Google Maps Integration
- Weather API
- Online Booking
- Payment Gateway
- Email Notifications
- Wishlist
- Reviews & Ratings
- Progressive Web App (PWA)

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Django Project Architecture
- Django Authentication
- Session Management
- CRUD Operations
- Django ORM
- URL Routing
- Template Inheritance
- Static File Management
- SQLite Database
- Responsive Frontend Development
- Git & GitHub Version Control

---

# 👨‍💻 About the Developer

## Akshaykumar Santi

🎓 Bachelor of Engineering (Computer Science & Engineering)

🎯 CGPA: **9.15**

💻 Aspiring Software Developer passionate about Python, Django, SQL, and Full-Stack Web Development.

### Technical Skills

- Python
- Django
- SQL
- HTML5
- CSS3
- JavaScript
- Git
- GitHub

Currently improving Data Structures & Algorithms while building real-world full-stack projects.


---

<p align="center">

⭐ If you found this project useful, consider giving it a Star.

Made with ❤️ using Python, Django & JavaScript.

</p>
