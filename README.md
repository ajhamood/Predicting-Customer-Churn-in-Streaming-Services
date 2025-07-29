\# Customer Churn Prediction Analysis



DSA 6000 practicum project that models and interprets subscriber churn for two streaming platforms – Netflix and a Hulu‑like service – to uncover the factors that most influence cancellations and to suggest retention tactics.\&#x20;



\## Files



\* \*\*Customer Churn Prediction Analysis.pdf\*\* – full write‑up

\* \*\*Customer Churn Prediction Analysis Code.ipynb\*\* – annotated Jupyter notebook (Python)



\## Data \& Privacy



Publicly available aggregates from the Kaggle Telco‑Customer‑Churn dataset and Gigasheet’s Netflix sample were used. Raw records containing personal identifiers or proprietary viewing history are \*\*not\*\* included in this repository; only derived features and summary outputs appear in the report.\&#x20;



\## Approach



\* Standardised both datasets, performed one‑hot encoding for categorical fields, then split 80 / 20 for training and test.\&#x20;

\* Trained interpretable \*\*logistic‑regression\*\* models to quantify the marginal effect of each feature on churn.\&#x20;

\* Evaluated with accuracy, precision, recall, F1 and confusion matrices; analysed coefficients to rank feature importance.\&#x20;



\## Key Findings (high level)



\* \*\*Netflix:\*\* tenure (negative) and monthly fee (positive) were the dominant churn predictors; the model achieved perfect accuracy on the test set.\&#x20;

\* \*\*Hulu‑like:\*\* class imbalance limited performance (accuracy ≈ 0.67); tenure remained the strongest signal while contract type and payment method had minimal impact.\&#x20;

\* Longer‑tenured subscribers across both services show markedly lower churn probability, underscoring the value of loyalty incentives.\&#x20;



\## Tools



Python 3, pandas, scikit‑learn, Jupyter Notebook for analysis; matplotlib for visualisations.



