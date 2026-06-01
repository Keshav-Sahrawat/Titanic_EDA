# Titanic Exploratory Data Analysis (EDA) Project

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival. The dataset was cleaned, analyzed, and visualized using Python data analysis libraries.

---

## Objective

The main objectives of this project are:

- Understand the structure of the Titanic dataset
- Identify and handle missing values
- Perform data cleaning and preprocessing
- Analyze survival patterns among passengers
- Visualize important relationships in the dataset
- Generate insights from the data

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Information

The dataset contains passenger information from the Titanic disaster, including:

- Passenger ID
- Passenger Class
- Name
- Gender
- Age
- Ticket Information
- Fare
- Cabin Information
- Embarkation Port
- Survival Status

Dataset Source:
Titanic Dataset (Kaggle)

---

## Data Cleaning Steps

The following preprocessing steps were performed:

### Missing Value Handling

- Filled missing values in the **Age** column using the median value.
- Filled missing values in the **Embarked** column using the most frequent value (mode).

### Column Removal

- Removed the **Cabin** column because it contained a large number of missing values.

### Data Preparation

- Created a cleaned dataset for further analysis.
- Encoded categorical variables for correlation analysis.

---

## Exploratory Data Analysis Performed

### Survival Analysis

- Overall passenger survival distribution

### Gender Analysis

- Survival comparison between male and female passengers

### Passenger Class Analysis

- Survival comparison across different passenger classes

### Age Distribution

- Distribution of passenger ages

### Fare Distribution

- Distribution of ticket fares

### Correlation Analysis

- Heatmap showing relationships between numerical features

---

## Key Findings

### Gender Impact

Female passengers had significantly higher survival rates compared to male passengers.

### Passenger Class Impact

Passengers traveling in higher classes had better survival chances.

### Age Distribution

Most passengers belonged to the young and middle-age groups.

### Missing Data

Missing values were successfully handled without affecting analysis quality.

---

## Project Structure

```
Titanic_Preprocessing/
│
├── Titanic_EDA.ipynb
│
├── raw_data/
│   └── titanic_raw_data.csv
│
├── cleaned_data/
│   └── titanic_cleaned.csv
│
├── screenshots/
│
└── README.md
```

---

## Output

The project produces:

- Cleaned Titanic Dataset
- Data Visualizations
- Survival Analysis Insights
- Correlation Heatmap
- EDA Report

---

## Conclusion

The analysis demonstrates that passenger survival was strongly influenced by factors such as gender and passenger class. Through data cleaning and visualization, meaningful insights were extracted from the Titanic dataset, making it a valuable introductory project in data analysis and machine learning workflows.

---

## Author

Keshav  
B.Tech Artificial Intelligence Student  
Learning Machine Learning, Data Analytics, and Backend Development through real-world projects.