# Loan-Status-Prediction-System

Project Overview
This project aims to predict the loan status of an applicant based on various features such as credit history, income, loan amount, etc. The model uses the Support Vector Machine (SVM) classifier algorithm to make predictions based on the provided dataset.

Technologies and Libraries Used
Python
Scikit-learn: For the SVM classifier and other machine learning tools.
Pandas: For data handling and manipulation.
NumPy: For numerical operations.
Matplotlib/Seaborn: For data visualization (if applicable).
Jupyter Notebooks: For development and testing (if applicable).
Data Used
The dataset contains information related to loan applicants, including features like:

Applicant’s credit history
Applicant’s income
Loan amount
Loan term, etc.

How to Run the Code:

1. Clone the repository:
git clone <repository_url>

2. Install the necessary libraries:

pip install -r requirements.txt

3.Run the main Python script:

python source_code.py


Key Files/Modules
source_code.py: Main script for training and predicting the loan status using SVM.
data_preprocessing.py: Script for handling data preprocessing (if separate).
model.pkl: Trained model (if you have saved it for reuse).
requirements.txt: List of dependencies required for the project.

Outputs/Results
After running the code, you should expect the following results:

Prediction Output: Whether the loan status is "Approved" or "Rejected."
Accuracy: The performance of the model, based on evaluation metrics like accuracy, precision, recall, etc.
Confusion Matrix: To evaluate the classification results (if applicable).
