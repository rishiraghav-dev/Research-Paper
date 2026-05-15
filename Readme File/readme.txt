A Multi-Modal AI-Based Health Intelligence Framework for Integrated Disease Risk Assessment and Lifestyle Analysis
📌 Overview

This project uses machine learning techniques to predict the likelihood of heart disease based on patient medical information.
The system compares multiple machine learning models and provides predictions through an interactive web application built using FastAPI and Streamlit.

The goal of the project is to assist in early heart disease risk assessment using clinical health parameters.

🎯 Objectives
* Analyze and preprocess patient health data
* Train and compare multiple ML models
* Predict heart disease risk accurately
* Build a user-friendly web application
* Generate visual prediction reports
* Store and manage patient records

📊 Dataset
* Heart Disease Dataset
* Dataset contains medical attributes such as:
* Age
* Sex
* Blood Pressure
* Cholesterol
* Chest Pain Type
* Heart Rate
* Smoking Habit
* Alcohol Consumption
* Diet & Fitness Information

* Dataset file used:
- heart1.csv

🤖 Models Used
* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest Classifier

📈 Evaluation Metrics
* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

🛠️ Tech Stack
* Python
* FastAPI
* Streamlit
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* SQLite3
* Joblib

📂 Project Structure

heart-disease-prediction-main/
│
├── pages/
│   ├── 2_Fitness.py
│   ├── 3_Attributes_Restrictions.py
│   ├── 4_Feedback.py
│   └── 5_Admin.py
│
├── reports/
│
├── 1_Heart.py
├── app.py
├── main.py
├── HDPrj.ipynb
├── heart1.csv
├── patients_data.db
│
├── logistic_model.pkl
├── random_forest_model.pkl
├── svm_model.pkl
├── scaler.pkl
├── model_columns.pkl
│
├── fitness_model.joblib
├── le_alcohol.joblib
├── le_diet.joblib
├── le_smoking.joblib
│
└── README.md

▶️ How to Run
1. Clone the repository
2. Open project folder - cd heart-disease-prediction
3. Create virtual environment - py -3.11 -m venv .venv
4. Activate virtual environment - .venv\Scripts\activate
5. Install dependencies - pip install -r requirements.txt
6. Start FastAPI Backend - python -m uvicorn main:app --reload

*Backend will run on -  http://127.0.0.1:8000

7. Start Streamlit Frontend - streamlit run 1_Heart.py
 		
		http://localhost:8501


👨‍💻 Developer

* Rishi Raghav Singh(2210992162)
* Rohan Singh(2210992176)

🏫 Course Details

* Subject: IOHE(Industry Oriented Hands on Experience)
* Department: Computer Science Engineering
* University: Chitkara University
* Batch: 2022

📅 Academic Year

* 2025–2026

✅ Conclusion

This project demonstrates how machine learning models can effectively predict heart disease risk using medical data.
The system combines machine learning, FastAPI, and Streamlit to create a complete real-world healthcare prediction application.

🔮 Future Scope
* Add Deep Learning models
* Deploy application on cloud platforms
* Add user authentication system
* Improve UI/UX design
* Add live health monitoring support

⭐ Acknowledgment
* Scikit-learn Documentation
* FastAPI Documentation
* Streamlit Community
* Open-source Machine Learning Resources