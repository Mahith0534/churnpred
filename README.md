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
```
### How to Run
1. Clone this Repository
```bash
git clone https://github.com/Mahith0534/churnpred.git
```
2. Navigate to the project folder
```bash
cd churnpred
```
3. Launch the Jupyter Notebook
```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```
4. Run all the cells in the notebook to execute the data processing, model training, and evaluation steps.
## Dataset
The dataset used for this project includes the following features:

- Customer tenure
- Monthly Charges
- Total Charges
- Contract type (Month-to-month, One year, Two years)
- Internet Service type
- Payment Method
- Churn (Target variable: Yes/No)
## Future Improvements
- Fine-tuning the model with more advanced hyperparameters.
- Expanding features to improve prediction accuracy.
- Deploying the model via a Flask API (optional).
