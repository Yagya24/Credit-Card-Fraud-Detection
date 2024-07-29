# Credit-Card-Fraud-Detection
This project involves developing machine learning models to detect fraudulent credit card transactions using a dataset of 284,807 transactions.

## Dataset
The dataset used contains transactions made by European cardholders in September 2013. It is highly imbalanced, with only 492 fraudulent transactions.
The dataset can either be accessed from here or can be downloaded from the website https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Data Preprocessing
- Handled class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
- Performed feature scaling and normalization.

## Models Implemented
Implemented and compared various machine learning algorithms:
- **Decision Tree:**
  - Accuracy: 99.92%
  - Precision: 86.52%
  - Recall: 92.10%
  - F1-Score: 89.23%
- **Linear SVM:**
  - Training time: 6.2 seconds
  - ROC-AUC score: 0.98
- **SnapML SVM:**
  - Training time: 1.2 seconds
  - ROC-AUC score: 0.99
  - Hinge Loss: 0.03

## Tools & Technologies
- Python
- scikit-learn
- SnapML
- pandas
- NumPy
- Jupyter Notebook

## Installation
1. Clone the repository: `git clone https://github.com/Yagya24/Credit-Card-Fraud-Detection`
2. Navigate to the project directory: `cd Credit-Card-Fraud-Detection`
3. Install the required packages: `pip install -r requirements.txt`

## Usage
Open the `Credit Card Fraud Detection.ipynb` notebook and run the cells to reproduce the analysis.
