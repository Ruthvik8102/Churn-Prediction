# Churn Prediction Project

**Overview**  
A data-driven machine learning project to predict customer churn using a publicly available dataset and a Jupyter Notebook (`churnnn.ipynb`).  
The model is trained on real-world customer data (`customer_churn.csv`) to identify patterns leading to churn.

---

##  Dataset

- **Filename**: `customer_churn.csv`  
- **Description**: (Add details—number of rows, features, and notable columns, e.g., `customerID`, `tenure`, `MonthlyCharges`, `Churn`)  
- **Source**: (If applicable; otherwise note it's a local sample dataset)

- Total records: **1,407** (999 non-churn; 408 churn)  
- Features: (Please specify here—e.g., customer demographics, monthly usage, tenure, etc.)

##  Model Evaluation Results

| Class        | Precision | Recall | F1-Score | Support |
|--------------|:---------:|:------:|:--------:|--------:|
| Non-churn (0) | 83%       | 87%    | 85%      | 999     |
| Churn (1)    | 65%       | 58%    | 61%      | 408     |

- **Overall Accuracy**: 79%  
- **Macro-average**: Precision 74%, Recall 72%, F1-Score 73%  
- **Weighted-average**: Precision 78%, Recall 79%, F1-Score 78%

> **Interpretation**: The model performs solidly for non-churn cases (F1-score of 85%), but identifying churn cases remains moderate (F1-score of 61%), indicating room for improvement.

##  Project Structure
