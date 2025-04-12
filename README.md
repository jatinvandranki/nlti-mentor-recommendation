# nlti-mentor-recommendation
Submission for NLTI Internship AI/ML Task
# NLTI Internship Assignment – Task 1

## 📌 Task: Personalized Mentor Recommendation System

This project is a basic machine learning-based recommendation system designed to help law aspirants preparing for CLAT find mentors who match their learning preferences and goals.

### 🧠 Features Considered:
- Preferred Subject
- Target College
- Preparation Level
- Learning Style

### 🛠️ Tools & Techniques Used:
- Python (with Pandas and Scikit-learn)
- Content-based Filtering using Cosine Similarity
- Randomly generated mock data for testing

### ✅ What the System Does:
Based on an aspirant’s profile, the system suggests the top 3 mentors who closely match their background and preferences.

---

## 📈 How It Works (Step-by-Step):

1. We start by generating mock data for both aspirants and mentors using Python.
2. Each categorical feature (like subject preference or learning style) is converted into a numerical format using OneHotEncoding.
3. We then calculate similarity scores between aspirants and mentors using cosine similarity.
4. Finally, the top 3 mentors with the highest similarity score are recommended to the user.

---

## 📁 Files You’ll Find in This Project:
- `mentor_recommender.ipynb`: The main notebook where everything happens
- `aspirants_mock_data.csv`: Mock data for aspirants
- `mentors_mock_data.csv`: Mock data for mentors
- `requirements.txt`: Libraries you need to run the notebook

---

## 🚀 Ideas for Improvement:
This is a basic version, but here’s how it could evolve:
- Let users rate mentor sessions and use that feedback to improve recommendations
- Move from content-based filtering to more advanced models like collaborative filtering or even NLP-based systems

---

## 🙌 About Me:
Hi, I’m Jatin — a Computer Science student passionate about AI/ML and eager to create real-world solutions. This project was done as part of my application for the NLTI internship.

