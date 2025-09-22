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

📚 Key Learnings / Outcomes

-Techniques for handling missing data using imputation
 -Encoding strategies for categorical features
-Importance of scaling numerical values before modeling
-Visualizing and interpreting outliers
-Structuring a preprocessing pipeline for reproducibility
