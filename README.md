# Churn Prediction Project

**Overview**  
A data-driven machine learning project to predict customer churn using a publicly available dataset and a Jupyter Notebook (`churnnn.ipynb`).  
The model is trained on real-world customer data (`customer_churn.csv`) to identify patterns leading to churn.

---

##  Dataset

- **Filename**: `customer_churn.csv`  
- **Description**: (Add details—number of rows, features, and notable columns, e.g., `customerID`, `tenure`, `MonthlyCharges`, `Churn`)  
- **Source**: (If applicable; otherwise note it's a local sample dataset)

---

##  Project Workflow

1. **Data Exploration & Preprocessing**  
   - Cleaned missing values, encoded categorical variables, handled outliers, etc. (List any specific techniques used.)  
2. **Feature Engineering**  
   - Created features such as month-over-month charge differences, total services subscribed, average tenure, etc.  
3. **Modeling**  
   - Trained and evaluated multiple classifiers like Logistic Regression, Random Forest, XGBoost, etc. (Please replace with what you used.)  
4. **Evaluation Metrics**  
   - Measured model performance using metrics like accuracy, precision, recall, F1-score, ROC-AUC, etc. (Insert actual results.)  
5. **Remarks & Learnings**  
   - Insights gained (e.g., key features influencing churn, improvements after resampling, etc.)  

---

##  Results

- **Best Model**: e.g., Random Forest  
- **Performance**: Achieved approximately *X% accuracy* and *Y ROC-AUC* on test set (replace with your results).  
- **Improvements**: Mentioned techniques (like SMOTE or parameter tuning) improved recall by *Z%*, etc.

---

##  How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/Ruthvik8102/Churn-Prediction.git

# Step 2: Navigate to the project folder
cd Churn-Prediction

# Step 3: Create and activate a virtual environment (optional but recommended)
python3 -m venv env && source env/bin/activate

# Step 4: Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn

# Step 5: Launch the notebook
jupyter notebook churnnn.ipynb
