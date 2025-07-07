# Marketing Campaign Analysis Project

## Project Overview

This group project involves the analysis of a marketing campaign dataset to uncover insights about customer demographics, spending behaviors, and response patterns. The goal was to utilize data mining techniques to identify customer segments and factors influencing campaign effectiveness.

## Objectives

* Perform exploratory data analysis (EDA) to understand customer profiles.
* Identify customer segments based on purchasing behaviors.
* Determine key attributes influencing customer responses to marketing campaigns.
* Recommend strategies to enhance marketing effectiveness.

## Data

The dataset used was the "Marketing Campaign" dataset, which includes customer demographics, purchase history, and responses to marketing promotions. It was obtained from Kaggle and comprises 2240 entries with 33 attributes.

## Data Cleaning and Preparation

* Missing values were identified and addressed by either imputing with median values or removing entries.
* Categorical variables (e.g., marital status, education) were encoded using one-hot encoding.
* Outliers in income and purchasing amounts were detected and managed to prevent skewed analyses.

## Exploratory Data Analysis

* Statistical analysis and visualization were performed using Python libraries such as pandas, matplotlib, and seaborn.
* Analysis included distributions of customer demographics, income levels, and purchasing behaviors.
* Correlation analysis was conducted to identify relationships between variables.

## Key Findings

* Income strongly influences purchasing habits; higher income groups showed increased expenditure on premium products.
* Families with children exhibited distinct purchasing behaviors, favoring essential goods over luxury items.
* Educational background significantly impacted response rates to campaigns, with higher-educated customers responding more positively.

## Conclusions

* Targeted marketing towards high-income and highly educated customer segments can improve campaign success rates.
* Tailoring promotions based on family composition can optimize customer engagement and sales.

## How to Run the Code

1. Ensure Python is installed.
2. Download the notebook and dataset.
3. Execute the notebook cells sequentially.

## Dependencies

* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* Jupyter Notebook

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

## Future Work

* Implement advanced clustering algorithms (e.g., K-means, hierarchical clustering) for more nuanced customer segmentation.
* Incorporate additional external datasets (e.g., social media engagement metrics) to enrich analysis and insights.
