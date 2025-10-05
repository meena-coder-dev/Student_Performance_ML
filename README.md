🎓 Student Performance Prediction

This project predicts a student’s final exam score based on their study hours, attendance percentage, and previous academic scores. It uses real-world data and a simple machine learning model to help understand how different factors influence academic performance.

📊 Project Overview

Many students struggle to understand how their daily habits affect their results. This project builds a predictive model that estimates a student’s final score using key academic factors.
It’s a beginner-friendly data science project built with Python and scikit-learn.

🚀 Features

📁 Load and analyze student performance data from a CSV file

📈 Train a Linear Regression model to predict final scores

🧪 Evaluate the model using Mean Absolute Error and R² Score

🔍 Predict new student scores by inputting custom data

🛠️ Technologies Used

Python 3.x

Pandas – for data handling

scikit-learn – for building and evaluating ML models

Jupyter Notebook – for interactive coding and visualization

📂 Project Structure
Student-Performance-ML/
│
├── dataset.csv                  # Sample student data  
├── student_performance.ipynb    # Jupyter Notebook with ML model  
└── README.md                    # Project documentation

📌 How to Run

Clone the repository:

git clone https://github.com/your-username/Student-Performance-ML.git


Open the notebook:

jupyter notebook student_performance.ipynb


Run all cells in order to load the dataset, train the model, and make predictions.

🧠 Example Prediction
# Predict final score for a new student
new_student = [[6, 85, 78]]  # [study_hours, attendance, previous_scores]
predicted_score = model.predict(new_student)
print("Predicted Final Score:", predicted_score[0])

💡 Future Improvements

Add more features like assignment scores or extracurricular activity impact

Use advanced models like Random Forest for better accuracy

Build a small web app interface for user-friendly predictions

✨ Author: Kuncham Meenakshi
📚 B.Sc. Maths, Statistics & Data Science
🚀 Passionate about AI, Python, and solving real-world problems with data
