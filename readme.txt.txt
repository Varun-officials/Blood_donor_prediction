# 🩸 Blood Donor Prediction

This project predicts whether a person is likely to donate blood again, based on historical donation data. The goal is to assist blood banks and healthcare organizations in identifying potential future donors.

## 📊 Problem Statement

Predict whether a blood donor will donate again based on features like:
- Recency (months since last donation)
- Frequency (number of past donations)
- Monetary (total blood donated)
- Time (months since first donation)

## 🧠 Machine Learning Approach

- Data Preprocessing & Cleaning
- Feature Engineering
- Model Training (Logistic Regression, Decision Tree, etc.)
- Evaluation using Accuracy, Precision, Recall, F1-Score
- Deployment (Streamlit or Flask)

## 📁 Project Structure

blood_donor_prediction/
│
├── data/                   # Dataset and CSV files
├── models/                 # Trained models
├── src/                    # Source code
│   ├── preprocessing.py    # Data preprocessing functions
│   └── model.py            # Training and prediction logic
├── app/                    # Streamlit or Flask app
├── requirements.txt        # Project dependencies
└── README.md               # Project overview

## 🚀 How to Run

1. Clone the repository

   git clone https://github.com/your-username/Blood_donor_prediction.git
   cd Blood_donor_prediction

2. Install dependencies

   pip install -r requirements.txt

3. Run the application

   streamlit run app/main.py

## 📈 Sample Results

| Model               | Accuracy | F1 Score |
|-------------------  |----------|----------|
| Logistic Regression | 88%      | 0.87     |
| Decision Tree       | 86%      | 0.85     |

## 💡 Future Work

- Improve performance with advanced models (XGBoost, Random Forest)
- Hyperparameter tuning
- Deploy to cloud (Render, Heroku, etc.)


Created by **Varun**  
Feel free to connect: https://github.com/Varun-officials
