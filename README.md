# Data Cleaning & Reporting Automation

## Project Overview

This project demonstrates an automated data cleaning and reporting workflow using Python and Power BI. The objective is to transform raw data into clean, analysis-ready datasets and generate meaningful reports and visualizations for decision-making.

The project uses the Titanic dataset and covers data preprocessing, missing value treatment, duplicate removal, data standardization, report generation, and dashboard development.

---

## Objectives

* Automate data cleaning processes
* Handle missing values and inconsistent data
* Remove duplicate records
* Generate automated reports
* Create interactive Power BI dashboards
* Improve reporting efficiency and data quality

---

## Dataset

**Dataset:** Titanic Passenger Dataset

Features include:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

---

## Data Cleaning Process

### Missing Value Handling

* Age → Replaced with Median
* Fare → Replaced with Median
* Cabin → Replaced with "Unknown"
* Embarked → Replaced with Most Frequent Value

### Duplicate Handling

* Duplicate records identified and removed

### Data Standardization

* Converted Gender values to lowercase
* Standardized Embarked values
* Removed unnecessary formatting inconsistencies

---

## Tools and Technologies

### Python

* Pandas
* NumPy
* Matplotlib
* OpenPyXL

### Business Intelligence

* Power BI Desktop

### Reporting

* Excel Reports
* Power BI Dashboards

---

## Project Workflow

Raw Dataset

↓

Data Cleaning & Validation

↓

Missing Value Treatment

↓

Duplicate Removal

↓

Data Standardization

↓

Clean Dataset Generation

↓

Excel Reports

↓

Power BI Dashboard

---

## Generated Reports

### Data Quality Report

Includes:

* Missing values by column
* Data cleaning summary
* Data validation information

### KPI Summary Report

Includes:

* Total Passengers
* Total Survivors
* Survival Rate
* Average Age
* Average Fare

---

## Dashboard Pages

### 1. Executive Dashboard

* Total Passengers
* Total Survivors
* Survival Rate
* Average Age
* Average Fare
* Passenger Class Distribution
* Gender Distribution

### 2. Data Quality Report

* Missing Values Summary
* Records Cleaned
* Data Validation Results

### 3. Passenger Analysis

* Age Distribution
* Gender Analysis
* Passenger Class Distribution
* Embarkation Analysis

### 4. Survival Analysis

* Survival by Gender
* Survival by Passenger Class
* Survival by Embarkation Port
* Fare Analysis

---


## Project Structure

```text
Data-Cleaning-Reporting-Automation/
│
├── tested.csv
├── cleaned_titanic.csv
│
├── data_cleaning_reporting_automation.ipynb
│
├── Titanic_Dashboard.pbix
│
├── summary_report.xlsx
├── data_quality_report.xlsx
│
├── survival_distribution.png
├── age_distribution.png
├── gender_distribution.png
├── class_distribution.png
│
├── requirements.txt
└── README.md
```


---

## Key Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Data Validation
* Data Quality Assessment
* Data Visualization
* Dashboard Development
* Power BI
* Reporting Automation
* Business Intelligence
* Python Programming

---

## Expected Outcome

This project demonstrates how automated data cleaning and reporting workflows improve data quality, reduce manual effort, and enhance reporting efficiency through Python automation and Power BI dashboards.
