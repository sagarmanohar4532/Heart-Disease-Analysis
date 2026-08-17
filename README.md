Heart Disease Data Analysis

Overview

This project performs exploratory data analysis (EDA), data cleaning, preprocessing, and feature analysis on a heart disease dataset. The goal is to understand patterns in demographic and clinical variables and explore their relationship with the HeartDisease outcome.

Objectives

Explore the structure and quality of the heart disease dataset

Identify missing, duplicate, and invalid values

Analyze distributions of important numerical variables

Examine relationships between categorical/clinical features and heart disease

Prepare the dataset for potential downstream machine learning applications

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Analysis Performed

Exploratory Data Analysis

The notebook examines:

Dataset shape, columns, data types, and descriptive statistics

Duplicate and missing-value checks

Heart disease class distribution

Distributions of Age, RestingBP, Cholesterol, and MaxHR

Relationships between Sex, ChestPainType, FastingBS, and HeartDisease

Cholesterol and age differences across heart disease groups

Correlation between numerical variables

Data Cleaning

The dataset contained zero values in Cholesterol and RestingBP that were treated as invalid measurements.

Replaced zero Cholesterol values with the mean of non-zero observations

Replaced zero RestingBP values with the mean of non-zero observations

Rounded the imputed values to two decimal places

Data Preprocessing

Applied one-hot encoding to categorical variables

Converted encoded features to integer representation

Standardized numerical features using StandardScaler

Scaled Age, RestingBP, Cholesterol, MaxHR, and Oldpeak

Key Visualizations

The notebook includes:

Histograms with KDE

Count plots

Box plots

Violin plots

Correlation heatmaps

These visualizations are used to investigate distributions and relationships between clinical variables and the target outcome.

Project Structure

heart-disease-analysis/
├── README.md
├── notebook/
│   └── Heart_Project.ipynb
├── data/
│   └── heart.csv
└── requirements.txt

How to Run

Clone the repository.

Install the required Python packages.

Place heart.csv in the expected data location.

Open Heart_Project.ipynb in Jupyter Notebook or JupyterLab.

Run the cells sequentially.

Future Improvements

Train and compare classification models

Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC

Perform feature selection

Tune model hyperparameters

Build an interactive dashboard for clinical-data exploration

Author

Sagar Manohar
