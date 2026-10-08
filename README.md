• Diabetes Risk Prediction: Machine Learning on Kaggle Data

A machine learning project hat predicts diabetes risk level (Low / Moderate / High) from 
lifestyle and health indicators, using a Kaggle dataset of 15,000+ patient records.

• What it does?
- Loads and explores a real-world health dataset (age, BMI, blood sugar, sleep, stress, family history, and more)
- Cleans and pre processes the data: drops irrelevant columns, one hot encodes categorical 
  • features:
- Splits data into train/test sets
- Builds and compares multiple models:
  1.Decision Tree (depth-limited, for interpretability)
  2.Decision Tree (full depth)
  3.Random Forest (200 estimators)
- Evaluates each model using accuracy and ROC-AUC score
- Exports and inspects decision tree logic in readable text form

• Results:
Model, Accuracy, ROC-AUC,
Decision Tree (max_depth=6)  77.0% , 0.896                  
Decision Tree (full depth)  69.9% (test) 
Random Forest (200 estimators)  78.8% 

• Tech Stack:
Python, Pandas, NumPy, sklearn, Matplotlib, Google Colab

• How to run?
1. Open the `.ipynb` notebook in Google Colab
2. Upload `diabetes_risk.csv` to the Colab session (Files panel → upload)
3. Run all cells top to bottom

• About this project:
Built as part of my Data Analytics & Data Science learning journey through my internship at 
**Skillorbit**, via **The Unlox Academy**, under the mentorship of **Mr. Girish Kumar** :
practicing machine learning fundamentals on real Kaggle data.
