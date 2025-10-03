# Breast Cancer Prediction Model

## Overview
This project is a machine learning application that predicts whether a tumor is benign or malignant based on medical features. The goal is to support early diagnosis and help reduce delays in treatment by providing quick, data-driven predictions.

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn (Logistic Regression)  
- Matplotlib, Seaborn (visualization)  

## Dataset
The dataset contains tumor characteristics such as radius, texture, perimeter, area, smoothness, compactness, and concavity.  
The target variable is **Diagnosis**:  
- `M` = Malignant  
- `B` = Benign  

## Process
1. **Data Cleaning and Preprocessing**  
   - Removed irrelevant columns  
   - Encoded the target variable (M = 1, B = 0)  
   - Normalized features for consistency  

2. **Model Training**  
   - Trained a Logistic Regression classifier  
   - Split dataset into training and testing sets  

3. **Evaluation**  
   - Generated a classification report and confusion matrix  
   - Measured performance on the test set  

## Results
- Achieved **96% accuracy** on the test dataset  
- Precision, Recall, and F1-score were high for both classes  
- Model successfully distinguished between benign and malignant tumors  

## Screenshots
(Add screenshots of confusion matrix, classification report, or plots here)

## How to Run Locally
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/breast-cancer-model.git
   cd breast-cancer-model
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook:
   jupyter notebook "Breast Cancer Model.ipynb"
