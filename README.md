# Aerofit Case Study: Customer Profile & Product Preference Analysis

## Project Overview

This case study analyzes Aerofit's customer dataset to understand
consumer behavior, product preferences, and the factors influencing the
purchase of various treadmill models. The analysis includes demographic
exploration, statistical insights, visualization of trends, and
identification of key variables that impact customer decisions. The goal
is to use data-driven insights to support Aerofit's marketing, product
positioning, and growth strategies.

## Problem Statement

Determine which customer characteristics (age, gender, income level,
etc.) most strongly influence the choice of treadmill model. Based on
the findings, identify which product categories Aerofit should focus on
for improved sales and customer targeting.

## Objective

Using the dataset provided, this case study aims to analyze:

-   The demographic profile of Aerofit customers.
-   Which treadmill model is preferred by different customer groups.
-   How variables such as age, income, and gender influence purchase
    behavior.
-   Patterns or trends that can support customer segmentation and
    targeted marketing.

## Dataset

The dataset used for this case study contains customer information
related to the purchase of Aerofit treadmill models.

### Dataset includes attributes such as:

-   Age
-   Gender
-   Income
-   Education
-   Marital Status
-   Usage
-   Fitness Rating
-   Product Purchased (KP281, KP481, or KP781)

### Dataset Source

The dataset was provided as part of the Aerofit Case Study requirement
in the form of a CSV file.

### Data Preparation

-   Missing values identified and handled appropriately.
-   Categorical variables standardized for consistency.
-   Numerical variables examined for outliers and distribution patterns.

## Methodology

### 1. Data Cleaning

-   Removed or imputed missing values where necessary.
-   Converted categorical features into uniform formats.
-   Verified correct data types for numerical and categorical
    attributes.
-   Checked for duplicates and structural inconsistencies.

### 2. Exploratory Data Analysis (EDA)

Performed detailed EDA to understand patterns in the data, including:

-   Distribution of key variables (age, income, usage, fitness score).
-   Demographic differences among customers purchasing each model.
-   Relationship between treadmill type and customer characteristics.
-   Cross-tabulations and frequency analysis for categorical variables.

### 3. Statistical Analysis

-   Mean, median, and standard deviation analysis for numeric variables.
-   Chi-square tests or ANOVA (if applied) to check associations.
-   Identification of statistically significant variables influencing
    product choice.

### 4. Visualization

Using Matplotlib and Seaborn, multiple visualizations were created to
support analysis:

-   Histograms and distribution plots
-   Count plots for product purchase comparisons
-   Box plots to analyze numeric variable variation
-   Bar charts for categorical segmentation
-   Heatmaps for correlation analysis

## Tools and Libraries Used

-   Python 3
-   Pandas for data cleaning and manipulation
-   NumPy for numerical computation
-   Matplotlib and Seaborn for visualization

## Key Insights

-   A clear relationship was observed between treadmill model preference
    and demographic attributes such as income, age group, and usage
    level.
-   Higher-end models (like KP781) tend to be purchased by customers
    with higher income or fitness usage frequency.
-   Younger customers showed different preferences compared to older
    customers, indicating distinct marketing opportunities.
-   Gender-based and education-based differences in product choices were
    identified.
-   Fitness rating and usage significantly influence the likelihood of
    purchasing specific treadmill models.

## How to Run

1.  Open the Colab notebook using the link provided: Aerofit Case
    Study - Google Colab
2.  Run each cell sequentially from top to bottom.
3.  The notebook automatically loads the dataset and executes all
    analysis and visualization steps.
4.  No manual package installation is required unless specified in the
    notebook.

## Future Work

-   Perform customer segmentation using clustering algorithms to
    identify distinct customer groups.
-   Build predictive models (Logistic Regression, Decision Trees, etc.)
    to predict which treadmill a customer is likely to purchase.
-   Add statistical tests to validate significance between customer
    attributes and product choice.
-   Deploy results into a dashboard for business use.

## Author

Krishna Agarwal 
Data Science Enthusiast
