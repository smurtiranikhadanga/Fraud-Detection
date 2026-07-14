# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The dataset contains anonymized credit card transaction records, where the goal is to classify each transaction as either **Normal** or **Fraudulent**.

The project covers the complete machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, handling imbalanced data using SMOTE, model training, evaluation, feature importance analysis, anomaly detection, and real-time fraud monitoring simulation.

---

## 🎯 Objective

* Detect fraudulent credit card transactions.
* Analyze transaction data through Exploratory Data Analysis (EDA).
* Handle imbalanced data using SMOTE.
* Train and compare multiple machine learning models.
* Evaluate model performance using different metrics.
* Simulate real-time fraud detection.

---

## 📂 Dataset

**Source:** Kaggle - Credit Card Fraud Detection Dataset

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Joblib

---

## 🤖 Machine Learning Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### Bonus Model

* Isolation Forest (Anomaly Detection)

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

* Dataset Overview
* Missing Values Check
* Duplicate Records Check
* Class Distribution
* Pie Chart of Fraud Distribution
* Correlation Heatmap
* Histograms of Features
* Transaction Amount Distribution
* Transaction Time Distribution
* Boxplots
* Amount vs Class Boxplot
* Pair Plot
* Confusion Matrix
* Feature Importance Plot
* Model Comparison Charts

---

## ⚙️ Feature Engineering

The following preprocessing techniques were applied:

* Scaling the **Amount** column
* Scaling the **Time** column
* Feature Selection
* Train-Test Split
* Handling Class Imbalance using **SMOTE**

---

## 🚨 Anomaly Detection

To strengthen fraud detection, **Isolation Forest** was implemented as an anomaly detection algorithm to identify unusual transaction patterns without relying solely on labeled data.

---

## 📡 Real-Time Monitoring Simulation

A simple real-time monitoring simulation was implemented where incoming transactions are processed one at a time and classified as:

* ✅ Normal Transaction
* 🚨 Fraudulent Transaction

This demonstrates how the trained model can be integrated into a real-time fraud detection pipeline.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Classification Report
* Confusion Matrix

---

## 📁 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── creditcard.csv
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
├── requirements.txt

```

---

## 🚀 Project Workflow

1. Import Libraries
2. Load Dataset
3. Understand Dataset
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Train-Test Split
8. Handle Imbalanced Dataset (SMOTE)
9. Train Machine Learning Models
10. Evaluate Models
11. Compare Model Performance
12. Feature Importance Analysis
13. Anomaly Detection using Isolation Forest
14. Real-Time Monitoring Simulation
15. Custom Fraud Prediction
16. Save Trained Model

---

## 📊 Results

* Successfully detected fraudulent transactions using supervised machine learning.
* Balanced the imbalanced dataset using **SMOTE**.
* Compared Logistic Regression, Decision Tree, and Random Forest classifiers.
* Random Forest achieved the best overall performance.
* Isolation Forest demonstrated anomaly detection capabilities.
* Simulated a real-time fraud detection workflow.
* Saved the trained model for future deployment.

---

## 💡 Future Improvements

* Hyperparameter tuning using GridSearchCV.
* Deep Learning using Artificial Neural Networks (ANN).
* XGBoost and LightGBM implementation.
* Real-time deployment using Flask or FastAPI.
* Streamlit dashboard for live fraud prediction.
* Apache Spark integration for large-scale transaction processing.
* Cloud deployment using AWS or Azure.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

```text
Credit_Card_Fraud_Detection.ipynb
```

### 4. Run All Cells

The notebook will:

* Load the dataset
* Perform data preprocessing
* Train machine learning models
* Evaluate model performance
* Generate visualizations
* Predict fraudulent transactions
* Save the trained model

---

## 📄 License

This project was developed for educational and learning purposes.

---

## 👩‍💻 Author

**Smurti Rani Khadanga**

B.Tech Computer Science & Engineering (AI & ML)

Machine Learning | Data Analytics | Python | Scikit-learn
