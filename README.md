# Statistical Analysis and Hypothesis Testing

## Project Overview

This project focuses on applying statistical techniques to analyze business sales data and generate meaningful insights. The analysis includes descriptive statistics, data distribution analysis, correlation analysis, hypothesis testing, confidence intervals, regression analysis, and business recommendations.

## Objectives

* Calculate descriptive statistics of sales data.
* Analyze data distribution and test for normality.
* Measure relationships between variables using correlation analysis.
* Perform hypothesis testing using T-Test and ANOVA.
* Calculate 95% confidence intervals and margin of error.
* Build a linear regression model and evaluate performance.
* Generate actionable business recommendations.

## Dataset Information

The dataset contains the following fields:

| Column      | Description             |
| ----------- | ----------------------- |
| Date        | Transaction Date        |
| Product     | Product Name            |
| Quantity    | Quantity Sold           |
| Price       | Unit Price              |
| Customer_ID | Customer Identifier     |
| Region      | Sales Region            |
| Total_Sales | Total Revenue Generated |

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

### Day 1: Descriptive Statistics

Calculated:

* Mean
* Median
* Mode
* Standard Deviation
* Variance

### Day 2: Data Distribution Analysis

Performed:

* Histogram Visualization
* Kernel Density Estimation (KDE)
* Shapiro-Wilk Normality Test

### Day 3: Correlation Analysis

Performed:

* Pearson Correlation
* Correlation Matrix
* Heatmap Visualization

### Day 4: Hypothesis Testing

Conducted:

#### Independent T-Test

Hypotheses:

* H0: East and West region sales are equal.
* H1: East and West region sales are different.

#### One-Way ANOVA

Hypotheses:

* H0: All regions have equal average sales.
* H1: At least one region differs.

### Day 5: Confidence Interval Analysis

Calculated:

* 95% Confidence Interval
* Margin of Error

### Day 6: Regression Analysis

Built:

* Linear Regression Model

Evaluated:

* Intercept
* Coefficients
* R-Squared Score

### Day 7: Business Insights

Generated:

* Top Product Analysis
* Top Region Analysis
* Business Recommendations

## Visualizations Generated

The project automatically generates:

* histogram.png
* correlation_heatmap.png
* confidence_interval.png
* regression_analysis.png
* business_insights.png

## Project Structure

```text
Week7_Statistical_Analysis/
│
├── sales_data.csv
├── statistical_analysis.py
├── statistical_analysis.ipynb
├── README.md
├── requirements.txt
├── hypothesis_tests_results.txt
├── statistical_report.pdf
│
└── visualizations/
    ├── histogram.png
    ├── correlation_heatmap.png
    ├── confidence_interval.png
    ├── regression_analysis.png
    └── business_insights.png
```

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
python statistical_analysis.py
```

## Key Findings

* Sales performance varies across products and regions.
* Quantity sold strongly influences total sales.
* Correlation analysis helps identify key business drivers.
* Statistical testing supports evidence-based decision making.
* Regression analysis demonstrates predictive relationships among variables.

## Business Recommendations

1. Increase marketing efforts for top-performing products.
2. Expand operations in high-performing regions.
3. Strengthen customer retention programs.
4. Improve performance of low-selling products.
5. Implement predictive analytics for future sales forecasting.

## Outcome

A complete statistical analysis pipeline was implemented, providing descriptive insights, hypothesis testing results, predictive modeling, and actionable business recommendations for business growth.

## Author

Dhanada Panda

Computer Science and Engineering

Silicon University
