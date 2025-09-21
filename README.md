# WATER-PRODUCTION-AND-WATER-CONSUMPTION-DATA-CLEANING
# DOSM Water Data Cleaning & KPI Calculation

This project focuses on **data cleaning and KPI calculation** for water-related datasets obtained from the **Department of Statistics Malaysia (DOSM)**.  
The work was performed in **Google Colab** using **pandas** for data manipulation and cleaning.  

---

## Overview

Four DOSM datasets were combined in Excel and imported into Jupyter Notebook for cleaning and preprocessing.  
After cleaning, key performance indicators (KPIs) were calculated:  

- **NRW (Non-Revenue Water)**  
- **LPCD (Liters Per Capita per Day)**  
- **Water Stress Index**  

The cleaned dataset, along with the calculated KPIs, was saved back into a CSV file for further analysis and reporting.  

---

## Data Cleaning Steps

- Checked for missing values  
- Checked and converted data types  
- Filled missing values  
- Checked and removed duplicates  
- Used `.describe()` for summary statistics  

---

## Features

- Combine and preprocess multiple DOSM datasets  
- Handle missing and inconsistent values  
- Calculate water-related KPIs (NRW, LPCD, Water Stress Index)  
- Save the cleaned and enhanced dataset into CSV  

---

## Requirements

- Python 3.10  
- Jupyter Notebook / Google Colab  
- pandas  

Install dependencies:  

```bash
pip install pandas
