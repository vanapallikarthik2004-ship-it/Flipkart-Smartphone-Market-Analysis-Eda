# 📱 Flipkart Smartphone EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Flipkart Smartphone dataset to understand smartphone trends, pricing patterns, ratings, specifications, and brand performance available on Flipkart.

The analysis focuses on data exploration, cleaning, preprocessing, and extracting meaningful insights from smartphone data using Python.

---

## Objectives

- Understand the structure and quality of the dataset.
- Identify missing values and data inconsistencies.
- Clean and preprocess the data.
- Analyze smartphone specifications and ratings.
- Explore relationships between brands, prices, storage, RAM, and ratings.
- Generate insights that can help understand market trends.

---

## Dataset Features

The dataset contains smartphone-related information such as:

- Brand
- Model
- Price
- Ratings
- RAM
- Storage
- Processor
- Color
- Battery Capacity
- Front Camera
- Battery Type
- Other smartphone specifications

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## Project Workflow

### Phase 1: Data Exploration & Initial Assessment

#### Data Understanding
- Loaded the dataset
- Viewed sample records
- Checked dataset structure
- Generated summary statistics
- Identified missing values
- Explored categorical variables

#### Data Quality Assessment
- Checked dataset dimensions
- Examined data types
- Investigated missing values
- Identified potential outliers
- Reviewed categorical inconsistencies

---

### Phase 2: Data Cleaning & Manipulation

#### Missing Value Handling
- Identified null values
- Dropped columns with excessive missing data
- Filled numerical missing values using mean
- Filled categorical missing values using mode

#### Duplicate Removal
- Detected duplicate records
- Removed duplicate entries

#### Data Standardization
- Standardized text formatting
- Converted categorical values to consistent format
- Removed unnecessary whitespace

#### Data Type Validation
- Verified data types
- Confirmed numerical and categorical fields

---

### Phase 3: Analysis

#### Non-Visual Bivariate Analysis

##### Categorical vs Categorical
- Brand vs Model analysis
- Crosstab analysis

##### Categorical vs Numerical
- Brand vs Price
- Brand vs Ratings
- Brand vs Storage

##### Numerical vs Numerical
- RAM vs Price
- Storage vs Price
- Battery Capacity vs Ratings

---

## Key Insights

- Certain smartphone brands dominate the dataset.
- Storage and RAM significantly influence smartphone pricing.
- Ratings vary across brands and configurations.
- Data cleaning improved dataset consistency and reliability.
- Removing duplicates and handling missing values enhanced analysis accuracy.

---

## Final Outcome

The dataset was successfully cleaned and prepared for analysis by:

- Handling missing values
- Removing duplicate records
- Standardizing categorical data
- Validating data types
- Performing exploratory analysis

This project demonstrates practical skills in:
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Statistical Summarization
- Data Visualization Preparation

---

## How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/flipkart-smartphone-eda.git
