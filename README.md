# Project Information

# Health Intelligence Framework

# Research Paper: A Multi-Modal AI-Based Health Intelligence Framework for Integrated Disease Risk Assessment and Lifestyle Analysis

Team Members:
2210992162: Rishi Raghav Singh
2210992176: Rohan Singh

#📌 Project Type: Research Project

This project was developed as part of a research and implementation-based healthcare AI system using Machine Learning, FastAPI, and Streamlit.

The team worked on:
- Machine Learning model development
- Backend API integration
- Streamlit frontend design
- Data preprocessing
- Report and research documentation
  
## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. This project helps in **early risk assessment** by using trained Machine Learning models to predict whether a person is likely to have heart disease based on clinical and lifestyle-related parameters.

The application provides:

- 🔹 FastAPI backend for ML model inference
- 🔹 Interactive Streamlit frontend
- 🔹 Multiple trained Machine Learning models
- 🔹 Real-time prediction system
- 🔹 Lifestyle-based health analysis
- 🔹 Clean and modular project structure

This project is suitable for:
- Academic projects
- Research work
- Internship portfolios
- Machine Learning showcases
- Healthcare AI demonstrations

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Language | Python 3.11 |
| Backend | FastAPI, Uvicorn |
| Frontend | Streamlit |
| ML Libraries | Scikit-learn |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Database | SQLite |
| Model Storage | Joblib, Pickle |
| Version Control | Git & GitHub |

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

The models were trained and evaluated using Scikit-learn with preprocessing techniques such as:

- Feature Scaling
- Label Encoding
- One-Hot Encoding
- Data Cleaning

---

## 📂 Project Structure

```bash
PROJECT
│
├── .venv/
│
├── pages/
│   ├── 2_Fitness.py
│   ├── 3_Attributes_Restrictions.py
│   ├── 4_Feedback.py
│   └── 5_Admin.py
│
├── reports/
│   └── heart_report_20250703_232032.pdf
│
├── .env
├── 1_Heart.py
├── app.py
├── main.py
├── requirements.txt
│
├── HDPrj.ipynb
├── heart1.csv
├── patients_data.db
│
├── fitness_model.joblib
├── logistic_model.pkl
├── random_forest_model.pkl
├── svm_model.pkl
├── scaler.pkl
├── model_columns.pkl
│
├── le_alcohol.joblib
├── le_diet.joblib
├── le_smoking.joblib
│
└── risk_chart.png

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/rishiraghav-dev/heart-disease-prediction.git
cd heart-disease-prediction

2️⃣ Create Virtual Environment
py -3.11 -m venv .venv

Activate Environment
Windows
.venv\Scripts\activate

3️⃣ Install Dependencies
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt

🚀 Run the Project
▶️ Start FastAPI Backend
python -m uvicorn main:app --reload

▶️ Start Streamlit Frontend
streamlit run 1_Heart.py

📈 Prediction Workflow
User Input
   ↓
Data Preprocessing
   ↓
Feature Scaling & Encoding
   ↓
ML Model Prediction
   ↓
Risk Probability Calculation
   ↓
Result Display on Streamlit UI

📌 API Endpoint Example
POST Request
POST /predict

📚 Research & Inspiration
This project is inspired by ongoing research in AI-powered healthcare systems and cardiovascular risk prediction.

👨‍💻 Author
Rishi Raghav Singh
Python Developer | Machine Learning Enthusiast | FastAPI | Streamlit

🙏 Acknowledgements
Scikit-learn Documentation
FastAPI Documentation
Streamlit Community
UCI Machine Learning Repository
Open-source ML Community

⭐ Support
If you like this project:
⭐ Star the repository
🍴 Fork the project
📢 Share it with others

📄 License
This project is licensed under the MIT License.
MIT License © 2026 Rishi Raghav Singh
