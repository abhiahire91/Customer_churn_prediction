🏦 SmartBank: Customer Churn Prediction & Retention Analytics

📌 Overview

This project focuses on predicting customer churn in the banking sector using machine learning techniques.
The goal is to identify customers who are likely to leave the bank, enabling proactive retention strategies.

---

🎯 Objective

- Predict customer churn
- Analyze key churn factors
- Build a reliable ML classification model

---

🚀 Key Features

- Data Cleaning & Preprocessing
- One-Hot Encoding (Categorical Data)
- Feature Scaling using StandardScaler
- Handling class imbalance using balanced weights
- Random Forest Classifier model
- Evaluation using multiple performance metrics

---

🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

⚙️ Model Details

- Algorithm: Random Forest Classifier
- Estimators: 200
- Max Depth: 10
- Min Samples Split: 5
- Class Weight: Balanced

---

📊 Model Performance

- Accuracy: 83.90%
- ROC AUC Score: 0.8635

📌 Classification Report

Class 0 (No Churn):
Precision: 0.91 | Recall: 0.89 | F1-score: 0.90

Class 1 (Churn):
Precision: 0.59 | Recall: 0.66 | F1-score: 0.62

📌 Insight: Model performs strong for non-churn customers but needs improvement in identifying churn customers.

---

📉 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve & AUC

---

📈 Key Insights

- Age is the most important factor
- Customers with more products churn less
- Higher balance influences churn behavior
- Active members are less likely to churn
- Germany customers show higher churn tendency

---

🔝 Top Features

- Age
- Products Number
- Balance
- Estimated Salary
- Credit Score
- Active Member
- Country (Germany)
- Tenure
- Gender
- Country (Spain)

---

▶️ How to Run

1. Clone the repository
   git clone https://github.com/your-username/your-repo-name.git

2. Open in Google Colab / Jupyter

3. Install dependencies
   pip install pandas numpy matplotlib seaborn scikit-learn

4. Run all cells

---

📸 Output

- Confusion Matrix
- ROC Curve
- Feature Importance Graph

 ---

📁 Dataset

- Bank Customer Churn Dataset

📌 Future Improvements

- Improve churn recall using SMOTE
- Try XGBoost / LightGBM
- Hyperparameter tuning
- Deploy using Streamlit

  ---

💡 Business Impact

- Helps reduce customer churn
- Improves retention strategies
- Increases revenue and customer lifetime value

