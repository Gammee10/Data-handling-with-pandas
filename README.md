# Titanic Data Analysis & Custom Dataset Project

## Overview
This project is part of a Python Foundations assignment. It focuses on data handling, cleaning, and analysis using pandas.

The project consists of two main parts:
1. Creating a custom dataset using a Python dictionary
2. Analyzing the Titanic dataset to uncover survival patterns

---

## Part 1: Custom Dataset

A dataset was created manually with:
- 5 features (columns)
- 15 records (rows)
- Custom index labels

This demonstrates understanding of:
- DataFrame creation
- Data structure design

---

## Part 2: Titanic Dataset Analysis

### Steps Performed

#### 1. Data Exploration
- Viewed dataset using `.head()`
- Checked structure using `.info()`
- Generated statistics using `.describe()`

#### 2. Data Cleaning
- Filled missing Age values using median
- Filled missing Embarked values using mode
- Dropped Cabin column due to excessive missing data
- Removed duplicate rows

#### 3. Data Analysis
Used groupby operations to analyze:
- Survival rate by gender
- Survival rate by passenger class
- Average age per class
- Survival rate by age group

#### 4. Data Filtering
Extracted:
- Female survivors
- Child survivors
- First-class survivors

---

## Key Insights

- Females had a higher survival rate than males
- Passenger class significantly influenced survival
- Children had better survival chances
- Female passengers in 1st class had the highest survival rate

---

## Tools Used

- Python
- Pandas

---

## How to Run

1. Install pandas:
2. Run the notebook:


---

## Author

This project was completed as part of a data science bootcamp assessment.
