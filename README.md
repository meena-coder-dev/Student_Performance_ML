🎓 Student Performance Prediction

Hi there! I’m Kuncham Meenakshi. This project is my attempt to predict a student’s final exam score based on their study hours, attendance, and previous scores. The goal is simple: understand how everyday habits affect performance, and see if we can predict results using machine learning.

I built this using Python, Pandas, and scikit-learn, and it’s designed to be beginner-friendly for anyone who wants to explore data science with real-world data.

📊 Why I Built This

I noticed many students don’t really know how their study patterns, attendance, and past scores influence their final marks. So I thought: why not try building a predictive model? This project shows how small changes in daily habits can be reflected in the final score.

🚀 What It Does

Loads student data from a CSV file

Analyzes the data to see patterns and relationships

Trains a Linear Regression model to predict final scores

Lets you try custom inputs to predict new student scores

Evaluates the model using simple metrics like R² Score and Mean Absolute Error

🛠️ Tech I Used

Python 3.x – the language I love coding in!

Pandas – for data handling and analysis

scikit-learn – to build the machine learning model

Jupyter Notebook – where all the coding magic happens

📂 How the Project is Organized
Student-Performance-ML/
│
├── dataset.csv                  # Sample student data  
├── student_performance.ipynb    # Jupyter Notebook with ML model  
└── README.md                    # This file, explaining everything

📌 How to Run

Clone this repository to your computer:

git clone https://github.com/meena-coder-dev/Student-Performance-ML.git


Open the notebook:

jupyter notebook student_performance.ipynb


Run the cells one by one to see how the data is loaded, the model is trained, and predictions are made.

🧠 Example

Here’s how you can predict a new student’s final score:

new_student = [[6, 85, 78]]  # [study_hours, attendance, previous_scores]
predicted_score = model.predict(new_student)
print("Predicted Final Score:", predicted_score[0])


Try changing the numbers and see how it affects the prediction — it’s pretty fun!

💡 Future Ideas

Include more features like assignments, projects, or extracurriculars

Try advanced models like Random Forest or Gradient Boosting

Make a simple web app so anyone can enter their info and see predictions

✨ About Me:
I’m Kuncham Meenakshi, a B.Sc. student in Maths, Statistics & Data Science. I love experimenting with Python, AI, and machine learning, and I enjoy turning data into insights that can help people make better decisions.
