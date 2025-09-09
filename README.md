📌 Telco Customer Churn Prediction
📖 Problem

Telecom companies face customer churn (customers leaving the service). The goal is to predict which customers are likely to churn, so the business can take action to retain them.

🛠 Solution

Used the Telco Customer Churn dataset from Kaggle (Blastchar version).

Performed data cleaning & preprocessing:

Removed unnecessary columns (customerID)

Converted TotalCharges to numeric

Encoded categorical features (Label Encoding + One-Hot Encoding)

Scaled numeric features

Built and compared machine learning models:

Logistic Regression (baseline)

Random Forest Classifier (final model)

Evaluated performance using Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix.

Identified top features influencing churn (e.g., Contract type, Monthly Charges, Tenure, Internet Service).

Saved the trained model using joblib for deployment.

🧰 Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

scikit-learn

joblib

📊 Impact

Built a model that predicts customer churn with good accuracy.

Helped identify important factors behind churn (contract type, tenure, monthly charges).

Business can now target at-risk customers with retention offers, reducing revenue loss.

📂 Files in this Repo

Telco_Churn_Prediction.ipynb → Jupyter Notebook (Google Colab ready)

README.md → project explanation
