# 🤖 AI Interview Preparation System

> An AI-powered Interview Preparation Platform built with **Python**, **Streamlit**, and **Machine Learning** to help students assess their technical skills, identify weak areas, generate interview questions, and track their interview readiness.

---

## 🚀 Overview

The **AI Interview Preparation System** is an interactive web application that assists students and job seekers in preparing for technical interviews.

Users can:

* 👤 Create their profile
* 🧠 Assess technical skills
* 📊 View performance analytics
* 📚 Get personalized learning roadmaps
* 💻 Generate interview questions
* 📈 Track learning progress
* 🎯 Predict interview readiness

---

## ✨ Features

### 🏠 Home Dashboard

* Project overview
* Platform statistics
* Feature highlights

### 👤 Student Profile

* Student information
* Preferred job role
* Branch selection
* Academic year

### 🧠 Skill Assessment

Rate yourself in:

* Arrays
* Linked List
* Stack
* Queue
* DBMS
* Operating System

---

### 📊 Dashboard Analytics

Displays:

* 📈 Average Score
* ⚠ Weak Topics
* 💪 Strong Topics
* 📊 Performance Visualization

---

### 🗺️ AI Learning Roadmap

Automatically recommends a learning roadmap based on weak topics.

Example:

* Arrays
* Linked List
* Stack
* Queue
* DBMS
* Operating System

---

### 💻 Interview Question Generator

Generate interview questions based on:

* Topic
* Difficulty Level

Supported Levels:

* Easy
* Medium
* Hard

(Current version uses a local JSON question bank. Future versions will integrate Google Gemini AI for dynamic question generation.)

---

### 📈 Progress Tracker

Tracks:

* Current Scores
* Target Scores
* Interview Readiness

---

## 🧠 Machine Learning

The project uses a **Decision Tree Classifier** to predict interview readiness based on the student's assessment scores.

Prediction Levels:

* 🔴 Low
* 🟡 Medium
* 🟢 Good
* 🏆 Excellent

---

# 🛠️ Tech Stack

| Category         | Technology   |
| ---------------- | ------------ |
| Language         | Python       |
| Frontend         | Streamlit    |
| Data Processing  | Pandas       |
| Visualization    | Matplotlib   |
| Machine Learning | Scikit-learn |
| Storage          | JSON         |
| IDE              | VS Code      |

---

# 📂 Project Structure

```text
AI-Interview-Preparation-System/
│
├── app.py
├── questions.json
├── requirements.txt
├── README.md
├── .gitignore
└── venv/ (ignored)
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Interview-Preparation-System.git
```

```bash
cd AI-Interview-Preparation-System
```

---

## 2️⃣ Create Virtual Environment

Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

# 📸 Screenshots

You can add screenshots here after deployment.

```
screenshots/
│
├── home.png
├── profile.png
├── dashboard.png
├── roadmap.png
├── questions.png
└── progress.png
```

---

# 📊 Workflow

```
Student
    │
    ▼
Create Profile
    │
    ▼
Skill Assessment
    │
    ▼
Dashboard Analytics
    │
    ▼
Weak Topic Detection
    │
    ▼
AI Learning Roadmap
    │
    ▼
Interview Question Generator
    │
    ▼
Progress Tracker
    │
    ▼
Interview Readiness Prediction
```

---

# 🔮 Future Improvements

* 🤖 Google Gemini AI Integration
* 🎤 AI Voice Mock Interview
* 📄 ATS Resume Analyzer
* 💬 AI Answer Evaluation
* 🧠 Personalized Learning Roadmap
* 🏢 Company-wise Interview Questions
* 📹 Video Interview Simulation
* 📝 Coding Challenge Evaluation
* 🏆 Achievement & Leaderboard
* ☁️ Database Integration
* 🔐 User Authentication
* 📈 Advanced Analytics Dashboard

---

# 📋 Requirements

```
streamlit
pandas
matplotlib
scikit-learn
```

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## **Sagnik Sen**

🎓 IIT Madras BS in Data Science & Applications

### Connect with me

* 💼 LinkedIn: https://www.linkedin.com/in/YOUR_LINKEDIN
* 📧 Email: [your-email@example.com](mailto:your-email@example.com)

---

## ⭐ If you found this project useful, please give it a Star on GitHub!

**Happy Learning! 🚀**
