# Credit Risk Assessment Model

This project implements a machine learning-based credit risk assessment model that helps evaluate loan applications. The application provides a user-friendly interface built with Streamlit for calculating credit risk scores and making lending decisions.

## Features

- Credit risk prediction based on multiple factors
- Credit score calculation (300-900 range)
- Risk rating classification (Poor, Average, Good, Excellent)
- Interactive web interface
- Real-time calculations

## Input Parameters

- Age
- Income
- Loan Amount
- Loan Tenure
- Average Days Past Due (DPD)
- Delinquency Ratio
- Credit Utilization Ratio
- Number of Open Accounts
- Residence Type (Owned/Rented/Mortgage)
- Loan Purpose (Education/Home/Auto/Personal)
- Loan Type (Secured/Unsecured)

## Project Structure

```
├── app/
│   ├── artifacts/
│   │   └── model_data.joblib    # Trained model and preprocessing components
│   ├── main.py                  # Streamlit interface
│   └── prediction_helper.py     # Prediction logic and utilities
├── dataset/                     # Training data
├── requirements.txt             # Project dependencies
└── README.md                    # Project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/pspandana/Credit-Risk.git
   cd Credit-Risk
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app/main.py
   ```

## Technology Stack

- Python
- Streamlit
- scikit-learn
- pandas
- numpy
- joblib

## Model Details

The credit risk assessment model uses Logistic Regression to predict the probability of default. The prediction is then transformed into a credit score (300-900) and a risk rating category.

## Live Demo

The application is deployed on Streamlit Cloud and can be accessed [here](https://credit-risk-pspandana.streamlit.app).

## License

This project is licensed under the MIT License - see the LICENSE file for details.
