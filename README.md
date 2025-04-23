<!-- Version 1.1 | Author: deng.wei | Date: 2025-4-23 -->
# Machine Learning Analysis for Early Detection of Heart Failure

## Project Overview

This project focuses on the **prediction of heart disease** using various machine learning models.  
The primary goal is to evaluate different models and determine the best-performing one for clinical decision support.

---

## Models Implemented

- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **Logistic Regression**
- **Decision Tree**
- **Naive Bayes**
- **Neural Network (MLP)**
- **Stochastic Gradient Descent (SGD)**

---

## Exploratory Data Analysis (EDA)

Key steps in EDA:
- **Visualizing distributions** of numerical features (e.g., Age, Cholesterol).
- **Checking for missing values** and their distribution.
- **Correlation analysis** to identify relationships between features.

---

## Instructions for Running the Code

1. **Install Required Libraries**  
   To run the project, you will need the following Python libraries:
   - `pandas`
   - `scikit-learn`
   - `matplotlib`
   - `IPython`

---

2. **Preprocessing the Data**  

The data will be automatically preprocessed. This includes:

- **Handling outliers** in the `RestingBP` and `Cholesterol` columns by replacing zero values with the respective median values.
- **Encoding categorical features** like `Sex`, `ChestPainType`, `RestingECG`, `ExerciseAngina`, and `ST_Slope`.
- **Standardizing numerical features** such as `Age`, `RestingBP`, `Cholesterol`, `MaxHR`, and `Oldpeak` using `StandardScaler`.

---

3. **Model Training and Evaluation**  

The models will be trained using the preprocessed data. The training set will be used to fit the models, and the performance will be evaluated using the test set.  
The performance metrics include:

- **Accuracy**: Proportion of correct predictions.
- **Precision**: Proportion of positive predictions that are correct.
- **Recall**: Proportion of actual positive cases that are identified correctly.
- **F1 Score**: Harmonic mean of precision and recall.

---

4. **Model Comparison**

After training, the models' performances will be compared based on the evaluation metrics. The best-performing model will be highlighted.

---

5. **Conclusion**

This project demonstrates the process of predicting heart disease using machine learning models. The primary goal is to select the most reliable model for use in clinical decision-making.

---

6. **Running Instructions**

1. **Install Dependencies**: Ensure you have Python and the required libraries installed.
2. **Download the Dataset**: Ensure the dataset `heart.csv` is in the correct directory.
3. **Run the Code**: Execute the provided Python scripts to train the models and evaluate their performance.
4. **View Results**: Review the printed evaluation metrics and model comparison.
