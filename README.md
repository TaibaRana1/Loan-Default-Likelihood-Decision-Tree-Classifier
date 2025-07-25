# Loan-Default-Likelihood-Decision-Tree-Classifier
This project predicts the likelihood of a loan applicant defaulting using a Decision Tree Classifier. Developed collaboratively by a team of three, the project follows a complete machine learning pipeline — from data preprocessing to model evaluation and interpretation.

## Dataset
We used the application_train.csv file from the Home Credit Default Risk dataset, publicly available on Kaggle.

## Project Workflow
 1. Data Understanding & Preprocessing
 2. Loaded and explored the dataset
 3. Handled missing values appropriately
 4. Encoded categorical features using Label Encoding and One-Hot Encoding
 5. Performed type conversions and cleaned inconsistencies

## 2. Feature Engineering
* Dropped irrelevant or redundant columns
* Treated outliers and skewed distributions
* Scaled/normalized numerical features (where applicable)

## 3. Model Training
Split data into training, validation, and test sets
Trained a Decision Tree Classifier using scikit-learn
Optimized hyperparameters using GridSearchCV

## 4. Model Evaluation
Evaluated model performance using:
* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC (AUC = 0.71)
* Plotted:
* Confusion Matrix
* ROC Curve
* Visualized the decision tree using plot_tree()


## 5. Optimization & Interpretation
* Applied pruning (max depth limit) to combat overfitting
* Visualized feature importance
* Compared performance with a Random Forest Classifier


