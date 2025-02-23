# Churn Predict

## Overview
**Churn Predict** is a Machine Learning-based tool designed to analyze customer behavior and predict the likelihood of customer churn. By leveraging data preprocessing, feature selection, and model training, businesses can gain actionable insights to reduce churn and enhance customer retention.

## Features
- **Data Preprocessing** – Cleans and prepares raw data for analysis.
- **Feature Selection** – Identifies key factors influencing churn.
- **Model Training** – Uses Logistic Regression, Random Forest, and XGBoost.
- **Evaluation Metrics** – Assesses model performance using accuracy and ROC-AUC.
- **Actionable Insights** – Helps businesses make informed decisions to reduce churn.

## Tech Stack
- **Programming Language**: Python
- **Libraries Used**:
  - Pandas (Data manipulation)
  - NumPy (Numerical computations)
  - Scikit-Learn (Machine learning models)
  - XGBoost (Gradient boosting algorithm)
  - Matplotlib & Seaborn (Data visualization)

## Dataset
The project uses the **Telco Customer Churn Dataset** (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) which contains customer demographic, account, and service details to determine churn patterns.

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/churn-predict.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd churn-predict
   ```
3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Customer_Churn_Prediction_using_ML.ipynb
   ```

## Usage
1. Load the dataset and perform data preprocessing.
2. Apply feature selection techniques to improve model performance.
3. Train models (Logistic Regression, Random Forest, XGBoost) on the dataset.
4. Evaluate performance using accuracy and ROC-AUC.
5. Interpret results and generate insights to reduce customer churn.

## Project Scope
**Churn Predict** helps businesses identify potential churners early, allowing them to take proactive measures such as personalized offers, loyalty programs, and customer engagement strategies to improve retention.

## Future Enhancements
- Implement deep learning models for improved accuracy.
- Integrate real-time churn prediction using APIs.
- Develop a web-based dashboard for visualization.


