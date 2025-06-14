# Medicine Recommendation System 💊

A **Symptom-Based Disease Prediction and Medical Recommendation Web App** built using **Flask, Machine Learning, and Bootstrap**.

This project allows users to input symptoms (via text or voice) and receive accurate disease predictions along with personalized medical advice such as precautions, medications, diet plans, and workout recommendations.

---

## 🚀 Features

- 🔍 **Symptom-Based Disease Prediction** using a trained Support Vector Classifier (SVC) model.
- 🗣️ **Voice Input Integration** for easy symptom entry.
- 💡 **Personalized Recommendations** including medications, diets, workouts, and precautions.
- 📚 **Informative Blog** explaining the project and how the system works.
- 📞 **Contact and Developer Pages** for user support and project credits.
- 🎯 **User-Friendly Interface** powered by Bootstrap 5.

---

## 🛠️ Technologies Used

- Python
- Flask
- Machine Learning (scikit-learn)
- Pandas & NumPy
- Bootstrap 5 (Frontend)
- HTML, CSS, JavaScript

---

## 📂 Project Structure

```plaintext
Medicine-Recommendation-System/
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── blog.html
│   ├── contact.html
│   └── developer.html
│
├── static/
│   └── (images, CSS, JS files if any)
│
├── datasets/
│   ├── Training.csv
│   ├── symtoms_df.csv
│   ├── description.csv
│   ├── precautions_df.csv
│   ├── medications.csv
│   ├── diets.csv
│   └── workout_df.csv
│
├── models/
│   └── svc.pkl
│
├── main.py
├── requirements.txt
├── Medicine Recommendation System.ipynb
└── README.md
