# Task1_Titanic
🚢 Titanic Data Preprocessing – Task 1

🎯 Objective
The goal of this task is to preprocess the Titanic dataset by handling missing values, encoding categorical variables, scaling numerical features, detecting outliers, and preparing the data for machine learning models

📁 Folder Structure
Task1_Titanic_Preprocessing/

│── data/
│   ├── train.csv
│   └── cleaned_titanic.csv

│── notebooks/
│   └── Task-01.ipynb

│── requirements.txt


🔄 Preprocessing Flow / Approach

-Loaded dataset and performed exploratory data analysis (EDA)
-Handled missing values:
    -Age → filled with median
    -Embarked → filled with mode
    -Fare → filled with median 
-Encoded categorical variables:
    -Sex → binary encoding
    -Embarked → one-hot encoding
-Scaled numerical features using StandardScaler:
    -Age
    -Fare
-Visualized outliers using boxplots
-Saved the cleaned dataset to cleaned_titanic.csv

📦 Requirements

pip install -r requirements.txt

Contents of requirements.txt:
    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn

▶️ How to Run

Clone the repository:
git clone https://github.com/janapriya21/Task1_Titanic.git
cd Task1_Titanic

Install dependencies:
pip install -r requirements.txt

Open the notebook:
jupyter notebook Task-01.ipynb
Run all cells to reproduce preprocessing steps

📌 Dataset

The dataset can be downloaded from Kaggle:
👉 Titanic Dataset – Kaggle

📖 Internship Q&A (Theory)

1. Types of Missing Data
MCAR: Missing Completely at Random
MAR: Missing at Random
MNAR: Missing Not at Random

2. Handling Categorical Variables
Label Encoding (for ordinal features).
One-Hot Encoding (for nominal features).

3. Normalization vs Standardization
Normalization → Rescales to [0,1].
Standardization → Mean = 0, Std = 1.

4. Outlier Detection
Boxplots, Z-score, IQR method.

5. Why Preprocessing is Important
Improves data quality.
Reduces bias.
Enhances model accuracy.

6. One-Hot vs Label Encoding
One-Hot → separate columns, no ordinal bias.
Label → assigns integers, may falsely imply order.

7. Handling Class Imbalance
Oversampling/Undersampling.
SMOTE.
Class weights.

8. Can Preprocessing Affect Accuracy?
Yes — proper handling of missing values, scaling, and encoding can significantly improve model performance.

📚 Key Learnings / Outcomes

-Techniques for handling missing data using imputation
 -Encoding strategies for categorical features
-Importance of scaling numerical values before modeling
-Visualizing and interpreting outliers
-Structuring a preprocessing pipeline for reproducibility
