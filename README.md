# Simple-Linear-Regression-Marketing-Project

## Project Overview

This project applies Simple Linear Regression to analyze the relationship between marketing expenditures and sales. The objective is to identify the advertising channel that has the strongest impact on Sales and provide a data-driven recommendation for marketing budget allocation.

The analysis includes data cleaning, exploratory data analysis (EDA), correlation analysis, regression modeling, diagnostic testing, and business interpretation of results.

## Dataset Description

The dataset contains the following variables:

* **TV** – TV advertising expenditure
* **Radio** – Radio advertising expenditure
* **Social_Media** – Social media advertising expenditure
* **Sales** – Sales generated

## Project Objectives

* Load and clean the marketing dataset
* Perform exploratory data analysis
* Identify the advertising channel most strongly correlated with Sales
* Build a Simple Linear Regression model using Statsmodels
* Evaluate regression assumptions using diagnostic plots
* Interpret model performance metrics
* Provide a marketing ROI recommendation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Jupyter Notebook

## Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

## Running the Project

1. Clone or download the repository.
2. Place the dataset file in the project directory.
3. Open the Jupyter Notebook.
4. Run all cells from top to bottom.

## Key Findings

* TV advertising showed the strongest correlation with Sales.
* TV advertising was selected as the independent variable for the regression model.
* The regression model achieved an R-squared value of approximately 0.999.
* Diagnostic plots indicated that the assumptions of linearity, normality, and homoscedasticity were reasonably satisfied.
* TV advertising demonstrated the strongest measurable impact on Sales.

## Business Recommendation

Based on the analysis, TV advertising should receive priority when allocating marketing resources, as it demonstrated the strongest relationship with Sales and the highest potential return on marketing investment.

## Repository Structure

```text
Simple-Linear-Regression-Marketing-Project/
│
├── regression_analysis.ipynb
├── README.md
└── marketing_dataset.csv
```

## Author

Data analysis project completed using Python and Statsmodels for Simple Linear Regression modeling.
