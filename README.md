# ML
# Customer Churn Prediction using Machine Learning

A Machine Learning project that predicts whether a customer is likely to churn based on customer behavior, subscription details, and service usage. The model is built using **Python**, **Scikit-learn**, **Pandas**, and **Random Forest Classifier**.

---

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to stop using their services. By analyzing customer demographics, usage patterns, and subscription information, this project builds a classification model to predict customer churn.

---

## 📂 Dataset

**Dataset:** `customer_churn_dataset-testing-master.csv`

### Features

| Feature | Description |
|---------|-------------|
| CustomerID | Unique customer identifier |
| Age | Customer age |
| Gender | Customer gender |
| Tenure | Number of months with the company |
| Usage Frequency | Frequency of service usage |
| Support Calls | Number of customer support calls |
| Payment Delay | Payment delay in days |
| Subscription Type | Type of subscription |
| Contract Length | Contract duration |
| Total Spend | Total amount spent |
| Last Interaction | Days since last interaction |
| Churn | Target variable (0 = No Churn, 1 = Churn) |

**Dataset Size**
- Total Records: **64,374**
- Features: **12**
- Missing Values: **None**

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset inspection
- Missing value checking
- Statistical summary
- Churn distribution visualization
- Data preprocessing

Example visualization:
- Customer Churn Distribution

---

## ⚙ Data Preprocessing

The following preprocessing steps were performed:

- Converted `Total Spend` to numeric format
- Filled missing values using median
- Label Encoding for categorical variables
- Feature scaling using `StandardScaler`
- Train-Test Split (80%-20%)

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Random Forest Classifier

### Workflow

1. Load Dataset
2. Explore Data
3. Data Cleaning
4. Encode Categorical Features
5. Split Dataset
6. Standardize Features
7. Train Random Forest Model
8. Predict Customer Churn
9. Evaluate Model

---

## 📈 Model Performance

**Accuracy Score**

```
Model Accuracy: 1.00
```

> **Note:** An accuracy of **100%** is unusually high and may indicate that the dataset is very easy to classify or there may be data leakage. Additional evaluation using unseen datasets and metrics like Precision, Recall, F1-Score, and ROC-AUC is recommended.

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Untitled2.ipynb
├── customer_churn_dataset-testing-master.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Move into the project directory:

```bash
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook Untitled2.ipynb
```

or open it in **Google Colab**.

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
```

Install them using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Confusion Matrix
- ROC Curve
- Precision, Recall & F1-Score
- Deploy the model using Flask or Streamlit

---

## 👨‍💻 Author

**MOHAMED AL ZAMEER**

- AI Developer
- Web Developer
- Basketball Coach

---
