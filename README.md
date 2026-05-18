# 📊 Customer Churn Prediction Using Voting Ensemble Machine Learning

## 🚀 Project Overview

This project predicts customer churn using Ensemble Machine Learning techniques.

A Voting Ensemble Classifier is used to combine multiple machine learning algorithms to improve prediction accuracy and model robustness.

The system helps businesses identify customers who are likely to leave their services, enabling proactive retention strategies.

---

# 🧠 Machine Learning Models Used

The project combines the following models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Voting Ensemble Classifier

The final prediction is generated using **Soft Voting Ensemble Learning**.

---

# 🎯 Business Problem

Customer churn is one of the biggest challenges for telecom and subscription-based companies.

Predicting churn helps businesses:
- Reduce customer loss
- Improve retention
- Increase revenue
- Build targeted marketing campaigns

---

# 🏗 Project Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Feature Encoding
      ↓
Train-Test Split
      ↓
Individual Model Training
      ↓
Voting Ensemble
      ↓
Model Evaluation
      ↓
Gradio Deployment
```

---

# 📂 Project Structure

```text
customer-churn-voting-ensemble/
│
├── data/
│   └── churn.csv
│
├── models/
│   └── voting_model.pkl
│
├── images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
│
├── train_model.py
├── requirements.txt
└── README.md
```

---

# ⚙ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data analysis |
| NumPy | Numerical operations |
| Scikit-learn | Machine learning |
| Matplotlib | Visualization |
| Seaborn | Data visualization |
| Gradio | Deployment UI |
| Joblib | Model saving |

---

# 📊 Features Used

- Gender
- Senior Citizen
- Tenure
- Internet Service
- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Partner
- Dependents

---

# 🤖 Voting Ensemble Learning

This project uses a Voting Ensemble approach where predictions from multiple machine learning models are combined.

### Why Ensemble Learning?
- Improves accuracy
- Reduces overfitting
- Creates robust predictions
- Combines strengths of multiple models

### Soft Voting Formula

The final prediction is based on averaged probabilities:

\[
\hat{y} = \frac{y_1 + y_2 + y_3 + y_4}{4}
\]

---

# 📈 Model Evaluation

The following evaluation metrics are used:

- Accuracy Score
- Confusion Matrix
- ROC Curve
- AUC Score
- Feature Importance

---

# 📉 Confusion Matrix

The confusion matrix helps evaluate:
- True Positives
- True Negatives
- False Positives
- False Negatives

---

# 📈 ROC Curve

ROC Curve measures the classifier’s performance across different thresholds.

Higher AUC indicates better classification performance.

---

# 🔍 Feature Importance

Feature importance analysis identifies which customer attributes contribute most to churn prediction.

Important features include:
- Tenure
- Monthly Charges
- Contract Type
- Internet Service

---

# 🖥 Gradio Web Application

The project includes a real-time Gradio interface for churn prediction.

Users can:
- Input customer information
- Predict churn instantly
- Interact with the ML model through a web UI

---

# ▶ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/customer-churn-voting-ensemble.git
```

---

# 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Run Model Training

```bash
python train_model.py
```

---

# ▶ Run Gradio Application

```bash
python app.py
```

---

# 🌐 Open Application

After running the app:

```text
http://127.0.0.1:7860
```

---

# 📊 Example Prediction

| Input | Value |
|---|---|
| Tenure | 2 |
| Monthly Charges | 90 |
| Total Charges | 180 |
| Senior Citizen | 0 |

### Prediction

```text
Customer Will Churn
```

---

# 📸 Project Screenshots

## Confusion Matrix
(Add screenshot here)

## ROC Curve
(Add screenshot here)

## Gradio Interface
(Add screenshot here)

---

# 🌟 Future Improvements

- XGBoost integration
- Hyperparameter tuning
- SHAP Explainable AI
- Streamlit deployment
- Docker containerization
- FastAPI integration
- Cloud deployment

---

# 📚 Learning Outcomes

This project demonstrates:
- Ensemble Learning
- Classification Algorithms
- Model Evaluation
- Explainable AI Concepts
- Real-Time ML Deployment
- Business Analytics

---

# 👨‍💻 Author

Your Name

--- Sagar kamble

# 📌 Conclusion

This project demonstrates how Ensemble Machine Learning can improve customer churn prediction performance through the combination of multiple models.

The integration of Gradio provides an interactive deployment experience suitable for real-world business applications.
