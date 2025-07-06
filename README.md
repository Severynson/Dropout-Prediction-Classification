## 🎓📉 Student Dropout Prediction Project

This project uses machine learning to predict student dropout risk based on a rich set of demographic, academic, and socioeconomic features. Built using Python and Jupyter Notebooks, it aims to support educational institutions in identifying at-risk students early and providing timely interventions to improve academic retention.

### 📌 Project Motivation

Who among us hasn’t faced challenges during university? Academic struggles are rarely just about “laziness.” More often, they reflect deeper issues — difficulties balancing studies with work, emotional stress, financial hardship, or even existential doubt. Students may begin to slip not because they don’t care, but because life is overwhelming.

This project is built on the belief that if we can recognize the early signs of academic risk, we can intervene with compassion and purpose — offering timely emotional support, financial aid, or simply the right encouragement. In some cases, something as small as offering a scholarship tied to a realistic improvement goal could be the turning point that keeps a student on their path to graduation.

### 📊 Features Used

The model draws on a comprehensive dataset containing over 35 features that include:

##### Demographic Information

    • Marital Status
    • Nationality
    • Age at Enrollment
    • Gender

##### Family Background

    • Father’s and Mother’s Education Level
    • Father’s and Mother’s Occupation

##### Academic Background

    • Admission Grade
    • Application Mode & Order
    • Daytime or Evening Attendance
    • Previous Qualification & Grade

##### Socioeconomic Status

    • Displaced
    • Debtor
    • Tuition Fees Status
    • Scholarship Holder
    • International Student

##### Academic Performance

• Curricular Units Enrolled, Approved, and Grades (for 1st & 2nd semesters)
• Units Without Evaluation

##### Macroeconomic Context

• Unemployment Rate
• Inflation Rate
• Gross Domestic Product (GDP)

These features are chosen to capture a full picture of each student’s environment and academic path, enabling precise and explainable classification.

### 🧠 Target Variable

The model is trained to predict the column Target (Dropout) — a binary classification indicating whether the student dropped out or continued successfully.

### ⚙️ Technologies Used

    •	Python
    •	Pandas, NumPy
    •	Scikit-learn
    •	Matplotlib

### 🚀 How to Use

    1.	Clone the repository, open the project's folder
    2.	Install the requirements:
        pip install -r requirements.txt
    3.	Open the notebook with your favorite IDE:
        jupyter notebook dropout_prediction.ipynb
    4.	Follow the notebook steps to:
        •	Load and explore the dataset
        •	Preprocess and visualize the data
        •	Train and evaluate a regression model
        •	Make predictions using your own design inputs

### 📁 Dataset

    •	Name: Predict Students Dropout and Academic Success
    •	Source: UCI Machine Learning Repository
    •	Link: https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success
    •	License: Open
    •	Instances: 4,000+
    •	Attributes: 35 input features + 1 target class (Dropout)

The dataset includes real-world student information from a Portuguese higher education institution. It is ideal for educational data mining and predictive modeling research.
