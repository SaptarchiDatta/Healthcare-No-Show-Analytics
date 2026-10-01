# Healthcare Appointment No-Show Analysis — Python EDA

## 📌 Project Overview

This project focuses on exploratory data analysis (EDA) of healthcare appointment data using Python.

The objective is to understand patient appointment patterns and identify factors that are associated with patients attending or missing their scheduled appointments.

The analysis is performed using Python and focuses on:

- Data understanding
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Patient demographics
- Medical conditions
- Appointment attendance
- No-show patterns
- Relationship between different patient and appointment characteristics



## 🎯 Business Problem

Missed healthcare appointments can affect hospital operations, appointment availability, and patient care.

This analysis investigates:

> **What patterns can be observed in patient appointment attendance and no-shows?**

The objective is not to establish causation, but to identify patterns and relationships that may be useful for further healthcare analytics.



## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn



## 📊 Analysis Performed

### 1. Data Understanding

The dataset was explored to understand:

- Number of records
- Number of columns
- Data types
- Basic statistics
- Unique values
- Distribution of important variables

### 2. Data Cleaning

The analysis includes:

- Checking missing values
- Checking duplicate records
- Inspecting column names
- Standardizing column names
- Checking data types
- Identifying potential data-quality issues

### 3. Feature Engineering

Additional analytical features were created from the existing data.

Examples include:

- `Age_Group`
- `WaitingDays`
- `Attended`

These features help convert the raw healthcare data into variables that are easier to analyze.

### 4. Patient Demographic Analysis

The analysis explores appointment patterns across:

- Age groups
- Gender
- Neighbourhood

### 5. Medical Condition Analysis

Patient medical characteristics were examined, including:

- Hypertension
- Diabetes
- Alcoholism
- Handicap

### 6. Appointment Attendance Analysis

The project examines the relationship between appointment attendance and different characteristics of the patients and appointments.

Particular attention is given to:

- No-show status
- Age groups
- Hypertension
- Diabetes
- SMS reminders
- Waiting days
- Gender



## 📈 Key Analytical Questions

The notebook investigates questions such as:

1. What percentage of appointments were attended or missed?
2. Does appointment attendance vary across age groups?
3. Is there an observed difference in attendance between genders?
4. How does attendance vary between patients with and without hypertension?
5. How does attendance vary between patients with and without diabetes?
6. Is there an observed relationship between SMS reminders and appointment attendance?
7. Does the waiting period between scheduling and appointment relate to no-show patterns?
8. Are there differences in appointment attendance across neighbourhoods?



## 🔍 Important Analytical Approach

For comparisons between groups, the analysis uses percentages and rates where appropriate rather than relying only on raw counts.

For example, when comparing age groups:

```text
No-Show Rate =
Number of No-Show Appointments
--------------------------------
Total Appointments in the Group
