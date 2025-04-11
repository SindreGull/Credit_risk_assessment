# Credit_risk_assessment using Logistic Regression and XGBoost

This project explores how machine learning can be used to assess credit risk by predicting whether a loan applicant is likely to default. Using a real-world dataset of more than $28,000$ loans, we built and compared two models:

- Logistic Regression with Lasso Regularization: For interpretability and variable selection.
- XGBoost: For high predictive accuracy.

Specifically, in the project, we:

- Cleaned and preprocessed a Kaggle credit dataset with $28,634$ records.
- Visualized key trends like age, income, loan intent, and grade across default outcomes.  
- Handled imbalanced classification using AUC and F1-score as evaluation metrics.
- Trained & tuned both models using $5$-fold cross-validation.
- Compared performance, interpretability, and complexity for the two models.


## Tools & technologies used

- R 
- Packages: tidyverse, glmnet, xgboost, ggplot2
- RMarkdown  
- Confusion matrices, ROC curves, F1-score, AUC


## Key skills and learnings

- Black box vs linear model: How to balance model performance versus explainability.
- The importance of AUC and F1 in imbalanced binary classification.
- Real-world tradeoffs in model choice for regulated industries.
- How Lasso helps prevent overfitting and does feature selection.

Through the analysis, we learned that:
XGBoost achieved higher precision/recall and overall predictive power, while Lasso gave a simpler, more interpretable model with fewer features.

## Files in this repository

- CR_Code.rmd contains the full RMarkdown notebook and R-code with preprocessing, modeling and resulting plots.
- Credit_risk_report.pdf is the final report dexcribing some theory, methodology, results, and interpretation of them.
- credit_risk_dataset.csv is the cleaned dataset of $28,634$ records used for training and testing.
- README.md is this file.

