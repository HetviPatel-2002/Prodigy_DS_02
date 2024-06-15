# Titanic Dataset Analysis

## Introduction
This repository contains a detailed analysis of the Titanic dataset from Kaggle. The dataset is used to demonstrate data cleaning and exploratory data analysis (EDA) techniques. The goal is to explore the relationships between variables and identify patterns and trends in the data.

## Dataset Description
The Titanic dataset provides information on the passengers aboard the Titanic, including their survival status, age, class, and other attributes. The dataset is divided into three main files:
- `train.csv`: Contains the training data.
- `test.csv`: Contains the test data.
- `gender_submission.csv`: A sample submission file.

## Files in Repository
- `task2.ipynb`: Jupyter notebook containing the code for data cleaning and EDA.
- `train.csv`: Training dataset.
- `test.csv`: Test dataset.
- `gender_submission.csv`: Sample submission file for Kaggle competition.

## Data Cleaning
The data cleaning process involves handling missing values, correcting data types, and removing unnecessary columns. Key steps include:
- Imputing missing values for age and embarked columns.
- Converting categorical variables into numerical formats using one-hot encoding.
- Dropping irrelevant columns such as `Cabin` due to high percentage of missing values.

## Exploratory Data Analysis (EDA)
EDA is performed to uncover patterns and relationships in the dataset. Key analyses include:
- Survival rate analysis based on different classes, genders, and ages.
- Visualization of passenger demographics using histograms and bar charts.
- Correlation analysis to identify relationships between variables.

## Conclusion
The analysis provides insights into the factors that influenced passenger survival on the Titanic. These insights can be used to build predictive models for survival probability.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/HetviPatel-2002/Prodigy_DS_02.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd Prodigy_DS_02
   ```
3. Open the Jupyter notebook `task2.ipynb` to view and run the data cleaning and EDA code:
   ```bash
   jupyter notebook task2.ipynb
   ```

## Dependencies

 ![Python Logo](https://legacy.python.org/community/logos/python-logo-master-v3-TM-flattened.png)
- **Python**

![Pandas Logo](https://pandas.pydata.org/static/img/pandas_white.svg)
- **Pandas**

![NumPy Logo](https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo.svg)
- **NumPy**

 ![Matplotlib Logo](https://matplotlib.org/_static/images/logo2.svg)
- **Matplotlib**

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests.
