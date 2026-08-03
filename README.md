# Sales Data Cleaning & Exploratory Data Analysis (EDA)

> **Transforming messy business data into a clean, reliable, and analysis-ready dataset using Python, NumPy, and Pandas.**

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)]()
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange.svg)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)]()

---

# Table of Contents

- [Project Overview](#project-overview)
- [The Problem](#the-problem)
- [Project Objectives](#project-objectives)
- [Project Workflow](#project-workflow)
- [Dataset Description](#dataset-description)
- [Data Quality Issues Introduced](#data-quality-issues-introduced)
- [Technologies Used](#technologies-used)
- [Materials Required](#materials-required)
- [Python Libraries Used](#python-libraries-used)
- [Project Structure](#project-structure)
- [Installation Guide](#installation-guide)
- [Running the Project](#running-the-project)
- [Data Cleaning Process](#data-cleaning-process)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Project Outcomes](#project-outcomes)
- [Skills Demonstrated](#skills-demonstrated)
- [Possible Improvements](#possible-improvements)
- [Author](#author)
- [License](#license)

---

# Project Overview

Data is one of the most valuable assets for every organization. However, real-world datasets are rarely clean. Before any meaningful analysis or machine learning can be performed, data must be inspected, cleaned, transformed, and validated.

This project demonstrates a complete end-to-end data cleaning and exploratory data analysis workflow using **Python**, **NumPy**, and **Pandas**.

Starting from a deliberately messy sales dataset, this project applies industry-standard preprocessing techniques to produce a reliable dataset suitable for business analysis and future machine learning applications.

The notebook explains every step in detail, making it suitable for beginners, students, and recruiters interested in understanding practical data cleaning techniques.

---

# The Problem

Imagine receiving sales data collected from different branches across multiple regions.

Unfortunately, the dataset contains several issues:

- Missing values
- Duplicate records
- Different date formats
- Currency symbols mixed with numbers
- Extra spaces
- Incorrect capitalization
- Misspelled categories
- Invalid numerical values
- Outliers
- Inconsistent customer information

If such data is analyzed without proper cleaning, it can lead to:

- Incorrect business decisions
- Misleading visualizations
- Poor machine learning performance
- Inaccurate reports
- Financial losses

The goal of this project is to transform this messy dataset into a clean, consistent, and trustworthy source of information.

---

# Project Objectives

The objectives of this project are to:

- Import a messy sales dataset
- Inspect the quality of the data
- Identify data quality issues
- Handle missing values
- Remove duplicate records
- Standardize inconsistent text
- Convert incorrect data types
- Handle outliers appropriately
- Create useful derived features
- Perform exploratory data analysis (EDA)
- Export a clean dataset for future use

---

# Project Workflow

```
          Raw Sales Dataset
                  │
                  ▼
         Data Inspection
                  │
                  ▼
      Missing Value Analysis
                  │
                  ▼
      Duplicate Detection
                  │
                  ▼
     Data Type Conversion
                  │
                  ▼
 Standardization & Cleaning
                  │
                  ▼
     Outlier Identification
                  │
                  ▼
 Feature Engineering
                  │
                  ▼
 Exploratory Data Analysis
                  │
                  ▼
     Clean Final Dataset
```

---

# Dataset Description

The dataset contains simulated sales transactions with multiple business variables.

| Column | Description |
|---------|-------------|
| Order ID | Unique order identifier |
| Order Date | Date of purchase |
| Customer Name | Customer who made the purchase |
| Product | Product sold |
| Category | Product category |
| Quantity | Number of units sold |
| Unit Price | Price per item |
| Total Sales | Revenue generated |
| Region | Sales region |
| Payment Method | Payment option used |

---

# Data Quality Issues Introduced

To simulate real-world business data, several intentional data quality problems were included.

These include:

- Missing values
- Duplicate rows
- Blank cells
- Mixed uppercase and lowercase text
- Leading and trailing spaces
- Currency symbols inside numeric columns
- Negative values
- Invalid quantities
- Different date formats
- Misspelled categories
- Inconsistent region names
- Outliers
- Incorrect data types

These issues provide an opportunity to practice professional data cleaning techniques.

---

# Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib

---

# Materials Required

Before running this project, ensure you have:

- Python 3.10 or later
- Jupyter Notebook or JupyterLab
- VS Code (optional)
- Git
- GitHub Account
- CSV dataset included in this repository

---

# Python Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

Install them using:

```bash
pip install numpy pandas matplotlib notebook
```

---

# Project Structure

```
sales-data-cleaning-eda/

│
├── data/
│   ├── messy_sales_dataset.csv
│   └── cleaned_sales_dataset.csv
│
├── notebooks/
│   └── Sales_Data_Cleaning.ipynb
│
├── README.md
│
├── requirements.txt
│
└── LICENSE
```

---

# Installation Guide

Clone the repository:

```bash
git clone https://github.com/yourusername/sales-data-cleaning-eda.git
```

Navigate into the project directory:

```bash
cd sales-data-cleaning-eda
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Sales_Data_Cleaning.ipynb
```

---

# Running the Project

The notebook is organized into logical sections.

## 1. Data Loading

- Import dataset
- Display first records
- Inspect dimensions

---

## 2. Data Inspection

- Check missing values
- Check duplicate rows
- Inspect data types
- Summary statistics

---

## 3. Data Cleaning

The following cleaning operations were performed:

### Missing Values

- Detection
- Imputation where appropriate
- Removal when necessary

### Duplicate Records

- Identification
- Removal

### Text Cleaning

- Remove unnecessary spaces
- Correct capitalization
- Standardize categories

### Numeric Cleaning

- Remove currency symbols
- Convert text to numbers
- Handle invalid values

### Date Cleaning

- Parse multiple date formats
- Convert to datetime objects

### Outlier Analysis

- Detect unusual observations
- Evaluate their impact
- Decide whether to retain or remove them

---

# Exploratory Data Analysis

After cleaning, the project investigates key business questions, including:

- Which products generated the highest revenue?
- Which region achieved the most sales?
- What is the monthly sales trend?
- Which payment method is most frequently used?
- What is the average order value?
- Which product category performs best?
- How are sales distributed across regions?
- Are there unusual purchasing patterns?

Visualizations include:

- Histograms
- Bar Charts
- Pie Charts
- Line Charts
- Box Plots

---

# Project Outcomes

At the end of this project, we successfully produced:

- A fully cleaned dataset
- Standardized variables
- Reliable numerical values
- Consistent categorical data
- Proper datetime formatting
- Business-ready visualizations
- Reproducible data cleaning workflow
- Analysis-ready dataset

---

# Skills Demonstrated

This project demonstrates practical experience in:

- Python Programming
- NumPy
- Pandas
- Data Cleaning
- Data Wrangling
- Data Validation
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Business Analytics
- Statistical Thinking
- Problem Solving

---

# Why This Project Matters

Data scientists spend **70–80% of their time cleaning and preparing data** before performing analysis or building predictive models. This project reflects that real-world workflow by emphasizing the importance of data quality as the foundation of reliable insights.

Rather than jumping directly into charts or machine learning, this repository demonstrates a systematic approach to transforming messy data into trustworthy information. The same techniques used here are applicable to business intelligence, analytics, reporting, and predictive modeling projects.

---

# Possible Improvements

Future enhancements could include:

- Interactive Power BI dashboard
- SQL database integration
- Automated data validation scripts
- Machine learning sales forecasting
- Streamlit web application
- Interactive Plotly visualizations
- Unit testing for data validation
- Automated ETL pipeline

---

# Author

**Benjamin Twizihirwe**

Bachelor of Statistics  
University of Rwanda

Aspiring Data Scientist | Data Analyst | Python Enthusiast

GitHub: *Add your GitHub profile here*

LinkedIn: *Add your LinkedIn profile here*

---

# Acknowledgements

This project was developed as part of a practical learning journey in data cleaning, preprocessing, and exploratory data analysis using Python.

Special thanks to the open-source Python community for developing powerful libraries such as **NumPy**, **Pandas**, and **Matplotlib**, which make modern data analysis accessible to everyone.

---

# License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for educational and personal purposes.

---

## If you found this project useful...

If this repository helped you learn something new, consider giving it a ⭐ on GitHub.

Your support motivates the development of more open-source data science projects.
