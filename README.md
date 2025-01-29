Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It employs a dataset of transactions and addresses class imbalance while building and evaluating models to achieve high accuracy and precision in fraud detection.

Table of Contents

Introduction

Dataset

Project Workflow

Requirements

How to Run

Results

Conclusion

Introduction

Credit card fraud is a critical issue in the financial industry, causing substantial financial losses. This project aims to develop a machine learning model that can effectively classify transactions as fraudulent or non-fraudulent, even in the presence of a significant class imbalance.

Dataset

The dataset used in this project contains anonymized transaction details:

Features: Numerical values (PCA-transformed), Amount, Time.

Target: Class (0: Non-fraudulent, 1: Fraudulent).

Key Statistics:

Highly imbalanced: Fraudulent transactions make up a very small percentage of the data.

Preprocessed: PCA transformation ensures anonymity of sensitive information.

Project Workflow

Data Exploration:

Understand data structure, distribution, and key statistics.

Visualize class distribution and check for skewness.

Data Preparation:

Handle missing and duplicate values.

Scale numerical features (e.g., transaction amount).

Perform stratified train-test split.

Model Building:

Train initial models on imbalanced data.

Address class imbalance using techniques like SMOTE or undersampling.

Experiment with various models (e.g., Logistic Regression, Random Forest).

Tune hyperparameters for optimal performance.

Model Evaluation:

Use metrics like Precision, Recall, F1-Score, and AUC-ROC.

Compare performance across different models and data balancing techniques.

Requirements

Libraries

Python 3.8+

pandas

numpy

matplotlib

seaborn

scikit-learn

imbalanced-learn

Install dependencies using:

pip install -r requirements.txt

How to Run

Clone the repository:

git clone <repository_url>

Navigate to the project directory:

cd Credit-Card-Fraud-Detection

Run the Jupyter notebook:

jupyter notebook Credit-Card-Fraud-Detection_Capstone_Ganesh_Babu_G.ipynb

Follow the notebook cells to execute the project.

Results

Models were evaluated using imbalanced and balanced datasets.

Best-performing model achieved high recall and precision, minimizing false negatives.

Key metric comparison was visualized to aid selection of the best model.

Conclusion

This project successfully demonstrated the use of machine learning for fraud detection. By addressing class imbalance and tuning hyperparameters, the models achieved reliable performance suitable for real-world application.

Feel free to reach out for any questions or suggestions regarding the project.
