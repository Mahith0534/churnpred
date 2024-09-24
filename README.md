# Customer Churn Prediction

This project aims to predict customer churn using historical customer data. The model is trained to identify patterns that may lead a customer to leave the service.

## Project Overview

The model is built using a Random Forest Classifier. It has been trained on historical customer data, which includes information such as:

- Tenure with the company
- Monthly Charges
- Total Charges
- Type of Contract (Month-to-month, One year, Two years)
- Internet Service (DSL, Fiber optic, None)
- Payment Method

Once trained, the model can predict whether a new customer is likely to churn based on these features.

## Getting Started

### Prerequisites

To run this project, you'll need:

- Python 3.x
- Pandas, Scikit-learn, Numpy
- Joblib (for saving/loading models)

You can install the required packages by running:

```bash
pip install -r requirements.txt
