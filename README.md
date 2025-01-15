# AI Models Bootcamp Task: Building and Developing AI Models

## Overview

This repository contains the code and resources for the building and developing AI models bootcamp. The task involves analyzing 911 call data from Kaggle, performing exploratory data analysis (EDA), and creating visualizations to gain insights into the dataset. 
## Dataset

The dataset used in this task is from [Kaggle](https://www.kaggle.com/mchirico/montcoalert) 

## Tasks

### 1. Data and Setup
- **Import Libraries**: Import necessary libraries such as `numpy`, `pandas`, `matplotlib`, and `seaborn`.
- **Load Data**: Read the CSV file into a DataFrame.
- **Inspect Data**: Check the basic information and the first few rows of the dataset.

### 2. Basic Questions
- **Top 5 Zipcodes**: Identify the top 5 zipcodes for 911 calls.
- **Top 5 Townships**: Identify the top 5 townships for 911 calls.
- **Unique Title Codes**: Determine the number of unique title codes in the dataset.

### 3. Creating New Features
- **Reason Column**: Create a new column called "Reason" that extracts the reason/department (EMS, Fire, Traffic) from the title column.
- **Most Common Reason**: Identify the most common reason for a 911 call based on the new "Reason" column.
- **Visualization**: Use seaborn to create a countplot of 911 calls by reason.

### 4. Exploratory Data Analysis (EDA)
- **Time Analysis**: Analyze the distribution of 911 calls over time.
- **Geospatial Analysis**: Visualize the geographical distribution of 911 calls using latitude and longitude.
- **Trend Analysis**: Identify trends and patterns in the data, such as the most common types of emergencies and their frequency.


### 5. Visualization and Reporting
- **Create Visualizations**: Generate visualizations to present the findings from the EDA and model evaluation.
- **Generate Report**: Summarize the insights and results in a comprehensive report.
