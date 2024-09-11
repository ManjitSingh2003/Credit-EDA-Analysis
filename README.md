# Loan Default Risk Analysis using Exploratory Data Analysis (EDA)

## Overview
This repository is part of an academic project aimed at applying Exploratory Data Analysis (EDA) to understand patterns in loan applications and their associated risks. The primary goal is to help a consumer finance company minimize loan defaults by identifying key risk factors influencing loan repayment behavior.

## Project Objective
In this project, we aim to:
- Understand consumer attributes and loan characteristics that influence the likelihood of default.
- Analyze the given dataset using EDA techniques to provide insights into which factors are strong indicators of loan repayment difficulties.
- Develop risk analytics to support the company's decision-making process regarding loan approvals and rejections.
  
This analysis will assist the company in minimizing the financial loss due to defaulted loans while ensuring that creditworthy customers are not unfairly denied.

## Problem Statement
Loan-providing companies face a major challenge in determining whether to approve or reject a loan application due to incomplete or insufficient credit history. The goal of this analysis is to identify patterns that can predict a client's likelihood to default on loan payments and to offer insights that can inform decisions on:
- Approving or rejecting loan applications
- Adjusting loan amounts or interest rates based on the applicant's risk level

We aim to analyze a dataset containing loan applications, previous applications, and their outcomes to extract meaningful insights using univariate, bivariate, and correlation analysis.

## Dataset
The dataset used for this analysis is too large to be hosted directly in this repository. You can download the dataset from the following Google Drive link:

[**Dataset Download Link**](https://drive.google.com/drive/folders/16RQztUqCfJOlbooHqYlJrp6Q7iL65uZB)

The project uses three main datasets:
1. **application_data.csv** – Information about clients at the time of their loan application.
2. **previous_application.csv** – Information on previous loan applications by the clients.
3. **columns_description.csv** – Data dictionary describing the variables used in the datasets.

The analysis focuses on finding patterns in these datasets to identify variables that indicate a higher risk of default.

## Project Structure
This repository contains the following files:
- **Credit_EDA_Assignment.ipynb**: The main Jupyter notebook containing the EDA analysis, code, and plots.
- **Credit_EDA_Assignment_PPT.pdf**: A presentation summarizing the business problem, approach, findings, and recommendations.

## Key Steps in the Analysis
1. **Data Exploration**: 
   - Used `pandas` functions to explore the structure and attributes of the dataset (e.g., shape, missing values, variable types).
   
2. **Data Cleaning and Preprocessing**:
   - Handled missing values, dropped irrelevant columns, and processed variables for further analysis.
   - Detected and analyzed outliers using statistical methods.
   
3. **Data Imbalance**:
   - Investigated data imbalance by analyzing the distribution of the target variable (clients with payment difficulties vs. those without).
   
4. **EDA (Exploratory Data Analysis)**:
   - Applied univariate, bivariate, and segmented univariate analysis to identify patterns.
   - Used correlation analysis to find the top 10 correlations for clients with payment difficulties and those without.
   - Visualized findings using various plots (scatter plots, heatmaps, etc.) to illustrate the relationships between variables.

## Key Findings
- **Income Level**: Defaulters typically have lower income compared to non-defaulters.
- **Loan Purpose**: Certain loan purposes, such as "Repairs," face higher rejection and default rates.
- **Housing Type**: Applicants living in co-op apartments exhibited higher tendencies to default.
- **Credit Limits**: Higher credit limits were associated with lower default risk, highlighting the importance of responsible financial management.
  
These findings provide valuable insights into how consumer behavior and loan attributes affect repayment, allowing the company to refine its risk assessment process.

## Visualizations
The project includes several visualizations to aid understanding of the dataset:
- **Boxplots** and **scatter plots** to analyze outliers and distributions.
- **Heatmaps** to show correlations between continuous variables.
- **Bar charts** to depict the distribution of loan applications and defaults based on consumer attributes.

## Requirements
This project is developed using Python and the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install the necessary libraries using the following command:
```
pip install pandas numpy matplotlib seaborn
```

## Conclusion
Through this project, EDA techniques were employed to uncover key patterns and trends in loan applications, helping the company make informed decisions about loan approvals and mitigate default risks. The results of this analysis can help in adjusting loan policies and interest rates for risky applicants, ensuring both profitability and fairness in lending.

## Usage
To reproduce the analysis:
1. Clone this repository.
2. Open the `Credit_EDA_Assignment.ipynb` file in Jupyter Notebook.
3. Run the cells sequentially to execute the analysis.

## License
This project is an academic exercise and is not intended for commercial use.
