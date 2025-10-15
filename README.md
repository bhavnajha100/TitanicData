Titanic Data Analysis & Survival Prediction

Overview

A project for exploratory data analysis (EDA) and machine learning prediction on the Titanic dataset.
It visualizes patterns affecting survival and builds a predictive model.

Dataset

The project uses the Titanic dataset from Seaborn. Key features:

survived: 0 = No, 1 = Yes

pclass: Passenger class (1, 2, 3)

sex: Gender

age: Age

sibsp: Siblings/Spouses aboard

parch: Parents/Children aboard

fare: Ticket fare

Project Structure
titanic-analysis/
│
├── titanic_analysis.ipynb    # Notebook with EDA & prediction
├── cleaned_data.csv          # Optional cleaned dataset
├── README.md                 # Project description

Key Features

Data Cleaning: Handle missing values in age and embarked.

Exploratory Analysis: Histograms, scatter plots, countplots, correlation heatmaps.

Prediction Model: Random Forest Classifier predicting survival.

Feature Importance: Identify which features affect survival most.

Quick Start

Clone the repo:

git clone https://github.com/your-username/titanic-analysis.git
cd titanic-analysis


Open titanic_analysis.ipynb in Colab or Jupyter Notebook.

Run all cells to reproduce analysis, plots, and predictions.

Requirements
pip install pandas numpy matplotlib seaborn scikit-learn

Insights

Female passengers had higher survival rates.

Passengers in 1st class were more likely to survive.

Fare and age moderately correlated with survival.

Family size had minimal effect on survival.

Author

Bhavna Jha
