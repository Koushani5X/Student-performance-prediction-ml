🎓 Student Performance Prediction Using Machine Learning

Minor Project – I | Artificial Intelligence and Machine Learning

A Machine Learning project that analyses student academic performance and predicts final scores and Pass/Fail outcomes using Regression and Classification techniques.

---

🛠️ Technologies Used

"Python"
"Pandas"
"NumPy"
"Scikit-learn"
"Jupyter"

📌 Project Overview

The project focuses on understanding the relationship between students' academic activities and their final performance.

It uses factors such as:

- Weekly self-study hours
- Attendance percentage
- Class participation

Two Machine Learning models are implemented to perform different prediction tasks.

🎯 Objectives

- Analyse student academic performance using Python.
- Predict final student scores.
- Classify students into Pass and Fail categories.
- Explore the relationship between academic activities and performance.
- Evaluate the performance of the implemented models.

📂 Dataset Information

The dataset consists of 1,000,000 student records and six attributes.

Attribute| Description
student_id| Unique student identifier
weekly_self_study_hours| Weekly self-study hours
attendance_percentage| Attendance percentage
class_participation| Class participation score
total_score| Final student score
grade| Academic grade

🤖 Machine Learning Models

1. Linear Regression – Score Prediction

Linear Regression is used to predict students' final scores based on the selected academic features.

Evaluation Metric: Mean Squared Error (MSE)

Observed MSE: 80.9348

2. Logistic Regression – Pass/Fail Classification

Logistic Regression is used to classify students into two categories:

- Pass: Total score ≥ 35
- Fail: Total score < 35

Observed Accuracy: 99.78%

Important: The confusion matrix indicates that the current model predicts all test records as Pass and fails to identify the Fail cases. Therefore, the accuracy is misleading due to class imbalance, and further improvement is required.

📊 Project Workflow

1. Importing required libraries
2. Loading the dataset
3. Data exploration and statistical analysis
4. Visualisation of student grades and scores
5. Splitting data into training and testing sets
6. Implementing Linear Regression
7. Implementing Logistic Regression
8. Evaluating model performance

📁 Repository Structure

student-performance-prediction-ml/
│
├── data/
│   └── student_performance.csv
│
├── notebooks/
│   └── student_performance_prediction.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore

⚙️ Installation and Execution

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/student-performance-prediction-ml.git

2. Open the project folder

cd student-performance-prediction-ml

3. Install dependencies

pip install -r requirements.txt

4. Launch Jupyter Notebook

jupyter notebook

Open the notebook inside the "notebooks" folder and run the cells sequentially.

🔮 Future Improvements

- Handle imbalanced classification data.
- Experiment with additional Machine Learning algorithms.
- Improve model evaluation and prediction performance.
- Develop an interactive student performance prediction interface.

📝 Conclusion

This project demonstrates how Machine Learning techniques can be applied to student academic performance analysis. It explores both regression and classification approaches to understand and predict student outcomes.

---

Project Type: Minor Project – I
Domain: Artificial Intelligence and Machine Learning
Programming Language: Python
