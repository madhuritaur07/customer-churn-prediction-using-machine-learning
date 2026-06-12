# customer-churn-prediction-using-machine-learning


## Project Overview

Customer churn refers to the phenomenon where customers stop using a company's products or services. Predicting customer churn is crucial for businesses because retaining existing customers is often more cost-effective than acquiring new ones.

This project implements a supervised machine learning approach to predict customer churn using customer demographic and service-related information. Multiple classification algorithms are trained and evaluated to identify the most effective model for churn prediction.

## Objectives

* Perform data preprocessing and feature engineering.
* Split data into training and testing sets.
* Apply cross-validation for model evaluation.
* Compare multiple machine learning algorithms.
* Evaluate models using standard classification metrics.
* Select the best-performing model for customer churn prediction.

## Dataset

The project uses the Telco Customer Churn dataset, which contains customer information such as:

* Gender
* Senior Citizen Status
* Partner
* Dependents
* Tenure
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Status (Target Variable)

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Machine Learning Models

### 1. Logistic Regression

A statistical classification algorithm used as a baseline model for binary classification.

### 2. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

## Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Converting data types
* Encoding categorical variables
* Feature selection
* Train-test splitting
* Data validation using cross-validation

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

## Results

After comparing the performance of Logistic Regression and Random Forest Classifier, the Random Forest model achieved superior performance across most evaluation metrics and was selected as the final model.

## Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
├── requirements.txt
└── images/
    ├── confusion_matrix.png
    └── roc_curve.png
```

## Installation

Clone the repository:

```bash
git clone https://github.com/madhuritaur07/Customer-Churn-Prediction.git
```

Navigate to the project directory:

```bash
cd Customer-Churn-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run all cells in:

```text
Customer_Churn_Prediction.ipynb
```

## Future Enhancements

* Hyperparameter tuning
* Feature importance analysis
* Model deployment using Flask or FastAPI
* Real-time churn prediction dashboard
* Deep learning-based churn prediction

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn effectively. By comparing multiple classification algorithms and evaluating them using various performance metrics, the project identifies the most suitable model for customer retention analysis.

## Author

Madhuri Taur

## License

This project is intended for educational and academic purposes.
