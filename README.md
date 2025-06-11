# Explainable Loan Approval for Non-Credit Users using Alternative Data

This project addresses the problem of financial exclusion by enabling fair loan approvals for users who lack traditional credit history. Instead of relying on credit scores, we utilize alternative data such as mobile usage, UPI transaction activity, and electricity bill payments to assess creditworthiness.

The model is built using a Random Forest classifier trained on the UCI Credit Approval dataset, which has been extended with realistic alternative behavioral features. To ensure transparency, we apply SHAP (SHapley Additive Explanations) to provide clear, interpretable justifications for each loan decision.

## Features

- Real-world dataset (UCI Credit Approval)
- Added realistic behavioral features:
  - Mobile data usage (GB)
  - UPI transaction count
  - Electricity bill amount
- Data cleaning and preprocessing
- Machine learning model (Random Forest)
- Explainable AI using SHAP
- Ready-to-use and GitHub-deployable project

## Project Structure

```
explainable-loan-approval/
├── data/
│   └── credit_data_clean.csv
├── notebooks/
│   └── loan.ipynb
├── README.md
├── requirements.txt
```

## Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- SHAP
- Jupyter Notebook

## How to Use

1. Clone the repository
2. Install required packages using:
   pip install -r requirements.txt
3. Open the notebook from the `notebooks/` folder:
   loan.ipynb
4. Run all cells to train the model and view SHAP visualizations

## Outcome

- Predicts loan approval (`Approved` or `Rejected`)
- Provides SHAP summary plots for transparency
- Supports financial inclusion with explainable decisions

## Author

**Reshma Begam**  
AI & Data Science Enthusiast  
