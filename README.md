# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis helps in understanding the dataset by finding patterns, relationships, trends, and anomalies through statistical summaries and visualizations.

---

## Tools and Libraries Used

* Python
* Jupyter Notebook
* Pandas
* Matplotlib
* Seaborn

---

## Dataset

* Dataset Name: Titanic Dataset
* File Used: `titanic.csv`

---

## Project Steps

### 1. Imported Required Libraries

Imported the necessary Python libraries:

* Pandas
* Matplotlib
* Seaborn

### 2. Loaded the Dataset

Loaded the Titanic dataset into a Pandas DataFrame using `read_csv()`.

### 3. Explored the Dataset

Performed basic data exploration using:

* `head()`
* `info()`
* `describe()`
* `isnull().sum()`
* `duplicated().sum()`
* `value_counts()`

### 4. Data Visualization

Created different visualizations to understand the dataset:

* Histogram
* Boxplot
* Count Plot
* Scatter Plot
* Correlation Heatmap
* Pair Plot

### 5. Observations

Observed patterns and relationships from each visualization and summarized the findings.

---

## Key Findings

* The dataset contains 891 passenger records.
* Some columns such as **Age**, **Cabin**, and **Embarked** contain missing values.
* Most passengers were between 20 and 40 years of age.
* Male passengers were more than female passengers.
* More passengers did not survive than survived.
* Female passengers had a higher survival rate than male passengers.
* The **Age** column contains some outliers.
* The **Fare** column shows a wide variation among passengers.
* The correlation heatmap indicates weak to moderate relationships between numerical variables.
* Pair plots help visualize relationships among important numerical features.

---

## Files Included

* `task5.ipynb` – Jupyter Notebook containing the complete EDA.
* `titanic.csv` – Dataset used for analysis.
* `report.pdf` – PDF report of the completed notebook.
* `README.md` – Project documentation.

---

## Conclusion

This project demonstrates the basic steps involved in Exploratory Data Analysis using Python. By analyzing the Titanic dataset, important insights were discovered using statistical methods and visualizations. The project helped in understanding data distributions, identifying missing values and outliers, exploring relationships between variables, and summarizing meaningful findings from the dataset.
