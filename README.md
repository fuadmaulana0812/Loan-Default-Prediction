# Loan Default Prediction

This project explores two approaches to predicting loan default and borrower credit risk. Each use case includes its own notebook and README with details of the analysis and modeling.

## Use cases

### [Credit Risk](Credit%20Risk)

This use case predicts whether a borrower is likely to be good or bad based on historical loan data. The workflow cleans and prepares the data, handles missing values and class imbalance with class weights, then trains a three-layer neural network in TensorFlow. The README reports 0.98 accuracy on the evaluation results.

- [Open the Credit Risk notebook](Credit%20Risk/Credit_Risk_Modeling.ipynb)
- [Read the use case details](Credit%20Risk/README.md)

### [Credit Loan Prediction](Credit%20Loan)

This use case predicts default using credit-line and payment-history features. It imputes missing values, addresses class imbalance with resampling, and standardizes the data. Five classifiers are compared; Random Forest performs best in the initial comparison. The reported final test score is 0.83.

- [Open the Credit Loan notebook](Credit%20Loan/Credit_Loan_Prediction.ipynb)
- [Read the use case details](Credit%20Loan/README.md)

## Project contents

| Folder | Focus | Notebook |
| --- | --- | --- |
| [Credit Risk](Credit%20Risk/) | Borrower risk classification with a neural network | [Credit_Risk_Modeling.ipynb](Credit%20Risk/Credit_Risk_Modeling.ipynb) |
| [Credit Loan](Credit%20Loan/) | Default prediction using classical machine learning models | [Credit_Loan_Prediction.ipynb](Credit%20Loan/Credit_Loan_Prediction.ipynb) |

See each use case README for its dataset notes, preprocessing steps, model comparisons, and evaluation details.
