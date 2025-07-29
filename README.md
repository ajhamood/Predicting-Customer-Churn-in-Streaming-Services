## Customer Churn Prediction Analysis

DSA 6000 practicum project that models and interprets subscriber churn for two streaming platforms – Netflix and a Hulu‑like service – to uncover the factors that most influence cancellations and to suggest retention tactics.

## Files

- **Customer Churn Prediction Analysis.pdf** – full write‑up
- **Customer Churn Prediction Analysis Code.ipynb** – annotated Jupyter notebook (Python)

## Data

Publicly available aggregates from the Kaggle Telco‑Customer‑Churn dataset and Gigasheet’s Netflix sample were used.

## Approach

- Standardised both datasets, performed one‑hot encoding for categorical fields, then split 80 / 20 for training and test.

- Trained interpretable \*\*logistic‑regression\*\* models to quantify the marginal effect of each feature on churn.

- Evaluated with accuracy, precision, recall, F1 and confusion matrices; analysed coefficients to rank feature importance.

## Key Findings

- Netflix: tenure (negative) and monthly fee (positive) were the dominant churn predictors; the model achieved perfect accuracy on the test set.

- Hulu‑like: class imbalance limited performance (accuracy ≈ 0.67); tenure remained the strongest signal while contract type and payment method had minimal impact.

- Longer‑tenured subscribers across both services show markedly lower churn probability, underscoring the value of loyalty incentives.

## Tools

Python 3, pandas, scikit‑learn, Jupyter Notebook for analysis; matplotlib for visualisations.
