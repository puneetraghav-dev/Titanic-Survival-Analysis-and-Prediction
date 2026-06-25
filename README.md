# Titanic-Survival-Analysis-and-Prediction
A Python-based machine learning project that performs data preprocessing and exploratory data analysis (EDA) on the Titanic dataset to understand passenger survival rates.

## Project Overview
This repository contains a machine learning workflow focused on exploring and analyzing the classic Titanic dataset. The primary goal of this project is to process raw passenger data, handle missing values, and uncover insights regarding passenger survival through Exploratory Data Analysis (EDA). 

## Dataset
The project utilizes the Titanic passenger dataset (`train.csv`)[cite: 1]. It includes various features such as passenger class, age, sex, and fare, along with the target variable indicating whether the passenger survived.

## Technologies Used
This project is built using Python and relies on the following essential data science libraries[cite: 1]:
* **Data Manipulation:** NumPy, Pandas[cite: 1]
* **Data Visualization:** Matplotlib, Seaborn[cite: 1]
* **Machine Learning:** Scikit-Learn (Logistic Regression, Model Selection, Metrics)[cite: 1]

## Project Workflow
The notebook is divided into the following key phases:

### 1. Data Collection & Processing
* Loaded the dataset into a Pandas DataFrame for inspection[cite: 1].
* Evaluated dataset dimensions (891 rows and 12 columns) and data types[cite: 1].
* Identified missing values across the dataset[cite: 1].

### 2. Handling Missing Values
To prepare the data for future predictive modeling, the following cleaning steps were implemented:
* Dropped the `Cabin` column entirely due to a high volume of missing data[cite: 1].
* Replaced missing values in the `Age` column with the mean age of the passengers[cite: 1].
* Replaced missing values in the `Embarked` column with the statistical mode[cite: 1].

### 3. Exploratory Data Analysis (EDA)
Visualized the data using Seaborn to understand the distribution of features and their relationship with survival rates:
* Analyzed overall survival counts[cite: 1].
* Visualized the gender distribution among passengers (`Sex`)[cite: 1].
* Compared the number of survivors categorized by gender[cite: 1].
* Visualized the distribution of passengers across different ticket classes (`Pclass`)[cite: 1].

## How to Run
1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed along with the required libraries: `pip install numpy pandas matplotlib seaborn scikit-learn`.
3. Place the `train.csv` file in the appropriate directory (e.g., `/content/train.csv` or update the file path in the notebook)[cite: 1].
4. Run the Jupyter Notebook to view the data processing steps and visualizations.
