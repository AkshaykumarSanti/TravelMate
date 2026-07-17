# ✈️ TravelMate

<p align="center">
  <img src="https://img.shields.io/badge/Django-5.x-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

<h3 align="center">
🌍 Plan Smarter • Travel Better • Explore More
</h3>

<p align="center">
TravelMate is a responsive full-stack travel planning web application built with Django that enables users to explore destinations, discover hotels & villas, organize itineraries, and manage travel plans through a clean, intuitive, and responsive interface.
</p>

---

# 📚 Table of Contents

* [📌 Features](#-features)
* [🛠️ Tech Stack](#️-tech-stack)
* [📸 Project Preview](#-project-preview)
* [🏗️ Architecture](#️-architecture)
* [📂 Project Structure](#-project-structure)
* [⚙️ Installation](#️-installation)
* [🚀 Future Improvements](#-future-improvements)
* [📚 Learning Outcomes](#-learning-outcomes)
* [👨‍💻 About the Developer](#-about-the-developer)

---

# 📌 Features

* 🔐 Secure User Authentication
* 🧳 Personalized Travel Dashboard
* 🏨 Browse Hotels & Villas
* 🌍 Explore Popular Destinations
* 📅 Plan & Manage Trips
* 📍 Domestic & International Locations
* 🔍 Intuitive Navigation & Clean UI
* 📱 Fully Responsive Design
* ⚡ Efficient Database Operations using Django ORM

---

# 🛠️ Tech Stack

| Category            | Technologies            |
| ------------------- | ----------------------- |
| **Backend**         | Python, Django          |
| **Database**        | SQLite3                 |
| **ORM**             | Django ORM              |
| **Frontend**        | HTML5, CSS3, JavaScript |
| **Version Control** | Git & GitHub            |

---

# 📸 Project Preview

## 🏠 Home Dashboard

<p align="center">
<img src="screenshots/home-dashboard.png" width="900">
</p>

---

## 🔐 Authentication

<table>
<tr>
<td width="50%">
<img src="screenshots/signup.png">
</td>

<td width="50%">
<img src="screenshots/login.png">
</td>
</tr>
</table>

---

## 🌍 Explore Destinations

<p align="center">
<img src="screenshots/destinations.png" width="900">
</p>

---

## 🏨 Hotels & Villas

<p align="center">
<img src="screenshots/hotels.png" width="900">
</p>

---

## ✈️ Ticket Booking Dashboard

<table>
<tr>
<td width="33%">
<img src="screenshots/dashboard-1.png">
</td>

<td width="33%">
<img src="screenshots/dashboard-2.png">
</td>

<td width="33%">
<img src="screenshots/dashboard-3.png">
</td>
</tr>
</table>

---

# 🏗️ Architecture

```text
                 User
                  │
                  ▼
        Web Browser (Client)
                  │
                  ▼
      HTML • CSS • JavaScript
                  │
                  ▼
          Django URL Routing
                  │
                  ▼
          Django Views (Logic)
                  │
                  ▼
            Django ORM
                  │
                  ▼
          SQLite Database
```

### Application Flow

1. Users register or log in securely.
2. Browse destinations, hotels, and villas.
3. Plan and organize travel itineraries.
4. Manage travel details through a personalized dashboard.
5. Django processes requests and retrieves data using the ORM.
6. The updated information is rendered dynamically on the frontend.

---

# 📂 Project Structure

```text
TravelMate/
│
├── TravelMate/
├── planner/
├── templates/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/AkshaykumarSanti/TravelMate.git
```

### Move into Project

```bash
cd TravelMate
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py migrate
```

### Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

---

# 🚀 Future Improvements

* ❤️ Wishlist / Favorites
* 💳 Online Booking Integration
* 🗺️ Google Maps API
* 🌦️ Weather Forecast
* ⭐ Reviews & Ratings
* 📱 Progressive Web App (PWA)
* 📧 Email Notifications

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Django Project Architecture
* Django ORM & Database Design
* Authentication & User Management
* CRUD Operations
* Template Rendering
* Responsive Frontend Development
* Static File Management
* Git & GitHub Workflow
* Building Full-Stack Web Applications

---

# 👨‍💻 About the Developer

### **Akshaykumar Santi**

🎓 Computer Science Graduate (CGPA: **9.15**)

💻 Aspiring Software Developer passionate about building scalable and user-friendly web applications.

🛠️ **Core Skills**

* Python
* Django
* SQL
* HTML5
* CSS3
* JavaScript
* Git & GitHub

🚀 Currently focused on strengthening my Full-Stack Development and Data Structures & Algorithms skills by building real-world projects and solving coding challenges.

⭐ **If you found this project helpful, consider giving it a Star!**

---

<p align="center">

Made with ❤️ using <strong>Python</strong>, <strong>Django</strong> & <strong>JavaScript</strong>

</p>
