# Customer Churn Prediction

Predicting customer churn using Decision Tree classification in R. This project applies a complete ML workflow — data cleaning, feature engineering, model training, and evaluation — on a telecom churn dataset.

## Overview

Churn prediction is critical for subscription-based businesses. This analysis uses decision trees (via `rpart`) to classify customers likely to leave, providing interpretable rules for retention strategies.

## Techniques Used

- Data cleaning and feature selection
- Factor encoding of categorical variables
- Train/test split (80/20)
- Decision Tree classification with `rpart`
- Model evaluation with ROC curves and confusion matrix
- Visualization with `rpart.plot`

## Dataset

- **File:** `churn.csv`
- **Domain:** Telecom customer data
- **Target:** Churn (binary classification)
- **Features:** State, area code, international plan, voice mail plan, call usage statistics

## Tech Stack

| Tool | Purpose |
|------|---------|
| R | Core language |
| rpart | Decision Tree modeling |
| rpart.plot | Tree visualization |
| caret | Model evaluation |
| pROC | ROC curve analysis |
| party | Additional tree methods |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bhanuprasadthota/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. Open R or RStudio and install required packages:
   ```r
   install.packages(c(DAAG, party, rpart, rpart.plot, mlbench, pROC, caret))
   ```

3. Open and knit `Churn Prediction Model .Rmd` in RStudio.

## Key Findings

- Built an interpretable decision tree identifying key churn drivers
- Evaluated model performance using ROC-AUC and confusion matrix
- Identified high-risk customer segments based on call patterns and plan type

## License

MIT License — see [LICENSE](LICENSE) for details.
