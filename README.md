# Loan Prediction using Machine Learning

## Overview
This project predicts loan approval status based on applicant details using machine learning. The model is trained using a dataset containing financial and demographic details of applicants. It utilizes logistic regression for classification and employs data preprocessing and visualization techniques to enhance model performance.

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical data, and normalizes numerical features.
- **Data Visualization**: Uses Seaborn and Matplotlib to generate insights into applicant demographics and loan approval trends.
- **Machine Learning Model**: Implements Logistic Regression to predict loan approval.
- **Performance Evaluation**: Computes accuracy to assess model performance.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/joel9591/loan-prediction.git
   cd loan-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   *(Ensure you have Python installed)*

## Usage
1. Run the script:
   ```sh
   python loan_prediction.py
   ```
2. The script loads the dataset, processes it, trains a Logistic Regression model, and prints the prediction results.

## Dataset
The dataset contains applicant details such as gender, marital status, education, employment status, credit history, and loan amount.

## Results
The model predicts loan approval with an accuracy score displayed after training. The output includes:
- Accuracy of the trained model
- Loan approval predictions for test data

## License
This project is open-source and available under the [MIT License](LICENSE).

