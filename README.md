# 📊 COVID-19 Global Data Analysis (2026) with 'EDA'-

## 📌 Project Description

This project performs Exploratory Data Analysis (EDA) on global COVID-19 statistics for the year 2026.  
The objective is to analyze country-level data, identify trends, compare absolute and per capita metrics, and extract meaningful insights using statistical and visualization techniques.

This analysis demonstrates data cleaning, feature engineering, correlation analysis, and data visualization skills using Python and Pandas.

---

## 🎯 Project Objectives

- Perform data cleaning and preprocessing
- Handle missing and inconsistent values
- Create meaningful derived features
- Compare countries based on total and per capita metrics
- Identify trends and statistical relationships
- Generate insights through visualization

---

## 🗂 Dataset Overview

- Total Records: 225+
- Total Features: 10+
- Key Columns:
  - Population
  - Total Cases
  - Active Cases
  - Total Deaths
  - Tests Per Million
  - Cases Per Million
  - Deaths Per Million

---

## 🧹 Data Cleaning Steps

- Removed unnecessary columns
- Handled missing values
- Converted data types (float to integer where required)
- Standardized column names
- Reset index
- Created new feature: Case Fatality Rate (CFR)

---

## ⚙️ Feature Engineering

A new feature was created:

CFR (Case Fatality Rate):

CFR = (Total Deaths / Total Cases) * 100

This metric helps evaluate the severity of COVID-19 impact in different countries.

---

## 📊 Exploratory Data Analysis

### 🔹 Descriptive Statistics
- Examined distribution of numerical features
- Identified variations in population and case counts

### 🔹 Top 10 Countries by Total Cases
- Large population countries dominate absolute case counts

### 🔹 Top 10 Countries by Cases Per Million
- Smaller nations show higher per capita impact

### 🔹 Death Rate Analysis
- Significant variation in Case Fatality Rate across countries

### 🔹 Correlation Analysis
- Strong relationship between Total Cases and Total Deaths
- Testing levels influence detected cases

---
covid19-global-dataset/
│
├── images/
│   ├── correlation_heatmap.png
│   ├── top5_total_cases.png
│   └── cases_per_million_histogram.png
│
├── covid19_global_dataset.ipynb
└── README.md

---

## 📈 Visualizations Used

- Bar Plot – Top 5 Countries by Total Cases
- Histogram – Cases Per Million Distribution
- Scatter Plot – Tests vs Total Cases
- Correlation Heatmap

---

## 🧠 Key Insights

- Absolute case numbers are strongly influenced by population size.
- Per capita metrics provide better comparison between countries.
- Testing intensity significantly affects reported case counts.
- Fatality rates vary across regions, indicating healthcare differences.

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🎯 Conclusion

This project highlights global disparities in COVID-19 impact and demonstrates how Exploratory Data Analysis can uncover meaningful patterns in real-world datasets.

The analysis strengthened skills in data cleaning, feature engineering, statistical analysis, and visualization.

---

## 📌 Author

Alikaif Jafri
