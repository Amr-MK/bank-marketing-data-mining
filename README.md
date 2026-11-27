# bank-marketing-data-mining
Bank Marketing Data Mining: Customer behavior analysis, term deposit subscription prediction, classification, clustering, and association rule mining using Python.
# Bank Marketing – Data Mining Project

## Project Overview

This project analyzes customer behavior using data mining and machine learning techniques to understand and predict whether a bank customer will subscribe to a term deposit.

The project uses the Bank Marketing dataset from the UCI Machine Learning Repository.

## Research Question

Can customer characteristics, previous campaign interactions, and economic indicators help identify customers who are more likely to subscribe to a term deposit?

## Dataset

**Source:** UCI Machine Learning Repository – Bank Marketing

- Dataset: `bank-additional-full.csv`
- Records: 41,188
- Original attributes: 21
- Target variable: `y`
- Target values: `yes` and `no`

The dataset contains customer demographics, financial information, campaign contact history, and macroeconomic indicators.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- MLxtend
- SciPy

## Data Mining Techniques

### 1. Exploratory Data Analysis (EDA)
- Statistical summaries
- Data distributions
- Missing and unknown value analysis
- Duplicate detection
- Outlier investigation
- Correlation analysis
- Customer behavior visualization

### 2. Data Preprocessing
- Duplicate removal
- Missing-value handling
- Categorical feature encoding
- Numerical feature scaling
- Feature engineering
- Prevention of data leakage

### 3. Classification
- Decision Tree
- Artificial Neural Network (MLPClassifier)

Evaluation includes:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

### 4. Clustering
- K-Means
- Elbow Method
- Silhouette Analysis
- Principal Component Analysis (PCA)
- Customer segmentation and profiling

### 5. Association Rule Mining
- Apriori Algorithm
- Frequent Itemsets
- Support
- Confidence
- Lift

## Project Structure

```text
bank-marketing-data-mining/
│
├── Data_Mining_Project.py
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
│
├── data/
│   └── bank-additional-full.csv
│
└── outputs/
    ├── figures/
    ├── tables/
    └── project_summary.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Amr-MK/bank-marketing-data-mining.git
```

Navigate to the project directory:

```bash
cd bank-marketing-data-mining
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Execution

Run the complete project:

```bash
python Data_Mining_Project.py
```

The script generates figures, result tables, and a project summary in the `outputs/` directory.

## Expected Outputs

- Exploratory data analysis visualizations
- Data quality and preprocessing reports
- Classification model comparison
- Decision Tree feature importance
- Confusion matrices
- K-Means cluster profiles
- PCA visualization
- Apriori frequent itemsets and association rules
- Integrated project summary

## Important Methodological Considerations

- `duration` is excluded from pre-contact classification to prevent target leakage.
- `y` is excluded from K-Means model fitting.
- Classification preprocessing is fitted within training pipelines.
- The same stratified train/test split is used for both classifiers.
- Association rules indicate relationships, not causation.

## References

Moro, S., Cortez, P., & Rita, P. (2014). A data-driven approach to predict the success of bank telemarketing. *Decision Support Systems, 62*, 22–31.

UCI Machine Learning Repository. Bank Marketing Dataset.

https://doi.org/10.24432/C5K306

## Dataset License and Attribution

The dataset is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).

The dataset is credited to Sérgio Moro, Paulo Rita, and Paulo Cortez.

## Author

Your Name

Data Mining Project
