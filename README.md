# Vehicle Insurance Claim Fraud Detection (ML)

## Overview

This project aims to detect fraudulent vehicle insurance claims using a comprehensive machine learning workflow. The solution leverages data preprocessing, feature engineering, class balancing, and advanced model training techniques to accurately flag suspicious claims.

## Features

- **Exploratory Data Analysis (EDA):** Visualizes and explores the dataset to identify key patterns and relationships.
- **Data Preprocessing:** Handles missing values, encodes categorical variables, scales numerical features, and selects the most relevant predictors.
- **Class Balancing:** Addresses class imbalance using random undersampling to ensure fair model training.
- **Model Training:** Compares multiple algorithms including Decision Tree, K-Nearest Neighbors, Support Vector Machine, Random Forest, and XGBoost.
- **Hyperparameter Optimization:** Tunes top-performing models using randomized search with cross-validation.
- **Ensemble Learning:** Implements a stacking ensemble to combine the strengths of multiple models.
- **Evaluation:** Assesses model performance using accuracy, precision, recall, F1-score, confusion matrices, and ROC curves.

## Project Structure

```
vehicle-insurance-claim-fraud-datection-ML/
│
├── data/
│   └── fraud_oracle.csv
├── notebooks/
│   └── Vehicle-Insurance_claim_fraud_detection.ipynb
├── README.md
└── (other scripts and files)
```

## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/vehicle-insurance-claim-fraud-datection-ML.git
   ```

2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   Open `notebooks/Vehicle-Insurance_claim_fraud_detection.ipynb` in Jupyter or VS Code and execute the cells step by step.

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- imbalanced-learn
- matplotlib
- seaborn

Install all dependencies with:
```
pip install pandas numpy scikit-learn xgboost imbalanced-learn matplotlib seaborn
```

## Results

The final model achieves high accuracy and recall for fraudulent claims, making it suitable for real-world insurance fraud detection scenarios. Detailed evaluation metrics and visualizations are available in the notebook.


## Authors

David Naumovski & Mihajlo Naumoski