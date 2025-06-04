# Prodigy_Task_3
# Bank Marketing Prediction Using Decision Tree

## Project Overview
This project uses a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on the Bank Marketing dataset (`bank-full.csv`). The dataset includes demographic, social, and behavioral attributes collected from direct marketing campaigns.

## Dataset
- Filename: `bank-full.csv`
- Source: UCI Machine Learning Repository (Bank Marketing Dataset)
- Format: CSV, semicolon (`;`) separated
- Features: age, job, marital status, education, default, balance, housing loan, personal loan, contact, day, month, duration, campaign, pdays, previous, poutcome, and target variable `y` (yes/no for subscription)

## Key Steps

1. **Data Loading**  
   Load the dataset with `pandas`, handling semicolon-separated values.

2. **Data Preprocessing**  
   - Check for missing values (none found).  
   - Encode categorical variables into numeric labels using `LabelEncoder`.

3. **Data Splitting**  
   Split data into training and testing sets (80%-20%).

4. **Model Training**  
   Train a Decision Tree Classifier with max depth = 5 to avoid overfitting.

5. **Model Evaluation**  
   Evaluate model accuracy and generate a classification report.  
   Visualize the confusion matrix to assess true/false positives and negatives.

6. **Visualization**  
   Display the structure of the trained decision tree with feature names and class labels.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Install libraries via:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
