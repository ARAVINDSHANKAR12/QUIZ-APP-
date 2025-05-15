# 🧠 Django Quiz Application

A web-based quiz application built with Django that allows users to test their knowledge in various Computer Science subjects. The platform delivers real-time evaluations, stores user performance, and provides detailed feedback for learning enhancement.

---

## 🚀 Project Overview

This quiz system enables users to select quizzes from multiple Computer Science subjects, answer questions, and receive immediate results. Built using Django for the backend and HTML/CSS/JavaScript (with AJAX and jQuery) for the frontend, the application is responsive and interactive.

---

## 🎯 Features

- 📚 **Multiple Subjects** – Users can choose quizzes from different topics in Computer Science.
- ✅ **Real-time Evaluation** – Instantly checks answers and computes final scores.
- 📊 **Detailed Feedback** – Displays correct and incorrect answers after submission.
- 🔐 **User Authentication** (optional) – Allows for login and tracking of user history.
- 💾 **Data Persistence** – Uses SQLite3 to store user responses and scores.

---

## 🛠️ Tech Stack

### 👨‍💻 Backend:
- **Python 3.x**
- **Django Web Framework**
- **SQLite3** (default Django database)

### 🎨 Frontend:
- **HTML5**, **CSS3**
- **JavaScript**, **AJAX**, **jQuery**

---

## 📂 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/django-quiz-app.git
cd django-quiz-app

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver

