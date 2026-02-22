# 💳 Financial Fraud Detection using Random Forest (SMOTE)

## 📌 Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning techniques.  
The dataset is highly imbalanced, with fraudulent transactions forming a very small percentage of the total data.  
To address this, SMOTE (Synthetic Minority Oversampling Technique) was applied to balance the training dataset.

The final selected model is a **Random Forest Classifier**, chosen based on performance comparison with multiple algorithms.

---

## 🎯 Objective
- Detect fraudulent transactions
- Handle class imbalance effectively
- Minimize false negatives (missed fraud cases)
- Compare multiple classification models
- Select the best-performing model

---

## 📊 Dataset Description
The dataset contains 11,142 transaction records with the following key features:

- step (transaction time step)
- type (transaction type)
- amount (transaction amount)
- oldbalanceOrg, newbalanceOrig
- oldbalanceDest, newbalanceDest
- isFraud (Target Variable)

Fraud cases represent less than 2% of total transactions, making this a highly imbalanced classification problem.

---

## ⚙️ Models Implemented
- Logistic Regression
- Decision Tree
- XGBoost Classifier
- Random Forest Classifier (Final Model)

---

## 🧠 Handling Class Imbalance
SMOTE was applied **only on the training data after train-test split** to avoid data leakage and ensure proper model generalization.

---

## 📈 Final Model Performance (Random Forest)

- **Accuracy:** 99%
- **Precision:** 96%
- **Recall:** 97%
- **F1-Score:** 98%

### Why Recall is Important?
In fraud detection, False Negatives (missed fraud cases) can lead to severe financial losses.  
Therefore, achieving high Recall was prioritized over just Accuracy.

---

## 📊 Evaluation Metrics Used
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib
- Seaborn

---

## 📂 Project Structure
```
financial-fraud-detection-ml/
│
├── notebooks/ # Jupyter notebooks
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

## 🚀 Key Highlights
✔ Real-world fraud detection use case  
✔ Imbalanced dataset handling  
✔ Multiple model comparison  
✔ Business-oriented evaluation focus  
✔ Random Forest final model selection  

---

## 📌 Conclusion
The Random Forest classifier demonstrated superior performance in detecting fraudulent transactions while maintaining a strong balance between Precision and Recall.  
This project showcases practical implementation of machine learning techniques in financial fraud detection.

---

### 👨‍💻 Author
Sunil Kumar Reddy
