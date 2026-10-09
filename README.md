# Credit Scoring Model Using Machine Learning

## 📌 Project Overview
This project uses machine learning to predict whether an individual is likely to default on a loan based on their financial history and personal information.

The model learns from financial data and predicts the `defaulted` target column using classification algorithms.

## 🎯 Project Objectives
- Analyze financial and credit-related data.
- Check for missing values in the dataset.
- Prepare features and the target variable.
- Train machine learning classification models.
- Evaluate model performance using Precision, Recall, F1-Score, and ROC-AUC.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 📂 Dataset Information
The project uses a synthetic credit-scoring dataset containing **1,200 rows and 12 columns**.

The dataset includes the following features:

| Feature | Description |
|---|---|
| `age` | Age of the individual |
| `monthly_income` | Monthly income |
| `existing_debt` | Current debt |
| `loan_amount` | Requested or recorded loan amount |
| `credit_history_years` | Length of credit history |
| `missed_payments_12m` | Missed payments in the last 12 months |
| `late_payments_30d` | Late payments over 30 days |
| `late_payments_90d` | Late payments over 90 days |
| `employment_years` | Years of employment |
| `dependents` | Number of dependents |
| `credit_utilization` | Credit utilization level |
| `defaulted` | Target variable indicating loan default |

## ⚙️ Machine Learning Models

### 1. Logistic Regression
Logistic Regression is used as a classification algorithm to predict whether an individual has defaulted.

### 2. Decision Tree Classifier
The Decision Tree Classifier learns decision rules from financial features to classify loan default outcomes.

## 🔄 Project Workflow
1. Import the required Python libraries.
2. Load the dataset using Pandas.
3. Explore the dataset using `head()` and `shape`.
4. Check missing values using `isnull().sum()`.
5. Separate the independent variables (`X`) and dependent variable (`y`).
6. Split the data into training and testing sets using `train_test_split`.
7. Train the Logistic Regression model.
8. Train the Decision Tree Classifier.
9. Evaluate both models using classification metrics.

## 📊 Model Evaluation Results

The following results were obtained in the notebook:

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Precision | 0.5854 | 0.3830 |
| Recall | 0.2581 | 0.3871 |
| F1-Score | 0.3582 | 0.3850 |
| ROC-AUC | 0.5712 | 0.4963 |

These results show that both models have room for improvement. Logistic Regression achieved higher precision and ROC-AUC, while the Decision Tree achieved slightly higher recall and F1-Score.

## 🚀 How to Run the Project
1. Clone or download this repository.
2. Open the notebook in Google Colab.
3. Upload the credit-scoring dataset or update the dataset path.
4. Install the required libraries if needed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```
5. Run the notebook cells in order.
6. Review the model evaluation results.

## 📚 Learning Outcomes
- Understanding supervised machine learning.
- Learning classification with Logistic Regression and Decision Trees.
- Separating features and target variables.
- Splitting data into training and testing sets.
- Evaluating classification models using multiple metrics.

## 🔗 Project Notebook
[Open the Credit Scoring Model in Google Colab](https://colab.research.google.com/drive/13jznguL-2OnEm0OHrAR1MlR1oDV-NENG?usp=sharing)

## 👨‍💻 Author
Usama

## ⚠️ Disclaimer
This is an educational machine learning project using synthetic data. Its predictions and evaluation results should not be used to make real-world lending decisions.
