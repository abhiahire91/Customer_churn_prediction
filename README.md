<h1 align="center">🏦 SmartBank: Customer Churn Prediction & Retention Analytics</h1>
<p align="center"><b>Machine Learning Project for Predicting Customer Churn</b></p>

<hr>

<h2>📌 Overview</h2>
<p>
This project focuses on predicting customer churn in the banking sector using machine learning techniques.
The goal is to identify customers who are likely to leave the bank and enable proactive retention strategies.
</p>

<hr>

<h2>🎯 Objective</h2>
<p>
Predict customer churn, analyze key churn factors, and build a reliable classification model
to support data-driven business decisions.
</p>

<hr>

<h2>🚀 Key Features</h2>
<ul>
  <li>Data Cleaning & Preprocessing</li>
  <li>One-Hot Encoding for categorical variables</li>
  <li>Feature Scaling using StandardScaler</li>
  <li>Handling class imbalance using balanced weights</li>
  <li>Random Forest Classifier model</li>
  <li>Evaluation using multiple performance metrics</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><b>Python</b></li>
  <li><b>Pandas, NumPy</b></li>
  <li><b>Matplotlib, Seaborn</b></li>
  <li><b>Scikit-learn</b></li>
  <li><b>Google Colab</b></li>
</ul>

<hr>

<h2>⚙️ Model Details</h2>
<p>
<b>Algorithm:</b> Random Forest Classifier <br>
<b>Estimators:</b> 200 <br>
<b>Max Depth:</b> 10 <br>
<b>Min Samples Split:</b> 5 <br>
<b>Class Weight:</b> Balanced
</p>

<hr>

<h2>📊 Model Performance</h2>
<p>
<b>Accuracy:</b> 83.90% <br>
<b>ROC AUC Score:</b> 0.8635
</p>

<hr>

<h2>📌 Classification Report</h2>
<p>
<b>Class 0 (No Churn):</b> Precision: 0.91 | Recall: 0.89 | F1-score: 0.90 <br><br>
<b>Class 1 (Churn):</b> Precision: 0.59 | Recall: 0.66 | F1-score: 0.62
</p>

<p style="color:#C0392B;">
<b>Insight:</b> Model performs strongly for non-churn customers but needs improvement in detecting churn customers.
</p>

<hr>

<h2>📉 Evaluation Metrics</h2>
<ul>
  <li>Accuracy Score</li>
  <li>Confusion Matrix</li>
  <li>Precision, Recall, F1-score</li>
  <li>ROC Curve & AUC</li>
</ul>

<hr>

<h2>📈 Key Insights</h2>
<ul>
  <li>Age is the most influential factor</li>
  <li>Customers with more products churn less</li>
  <li>Higher balance impacts churn behavior</li>
  <li>Active members are less likely to churn</li>
  <li>Germany customers show higher churn tendency</li>
</ul>

<hr>

<h2>🔝 Top Features</h2>
<ul>
  <li>Age</li>
  <li>Number of Products</li>
  <li>Balance</li>
  <li>Estimated Salary</li>
  <li>Credit Score</li>
  <li>Active Member</li>
  <li>Country (Germany, Spain)</li>
  <li>Tenure</li>
  <li>Gender</li>
</ul>

<hr>

<h2>▶️ How to Run</h2>
<pre>
git clone https://github.com/your-username/your-repo-name.git

Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn

Run the notebook in Google Colab / Jupyter
</pre>

<hr>

<h2>📸 Output</h2>
<ul>
  <li>Confusion Matrix</li>
  <li>ROC Curve</li>
  <li>Feature Importance Graph</li>
</ul>

<hr>

<h2>📁 Dataset</h2>
<p>Bank Customer Churn Dataset</p>

<hr>

<h2>📌 Future Improvements</h2>
<ul>
  <li>Improve churn recall using SMOTE</li>
  <li>Try XGBoost / LightGBM</li>
  <li>Hyperparameter tuning</li>
  <li>Deploy using Streamlit</li>
</ul>

<hr>

<h2>💡 Business Impact</h2>
<p>
Helps reduce customer churn, improves retention strategies,
and increases customer lifetime value and revenue.
</p>

<hr>

<h2 align="center">👨‍💻 Author</h2>
<p align="center">
<b>Abhishek Ahire</b><br>
Aspiring Data Scientist | Machine Learning Enthusiast
</p>

<hr>

<p align="center">⭐ If you found this project useful, consider giving it a star!</p>
