# Marketing Campaign Analysis Project

## Project Overview

This project analyzed a marketing campaign dataset to uncover insights into customer demographics, spending behaviors, and response patterns. Conducted as a group project for a data mining course, the analysis aimed to identify distinct customer segments and key factors influencing campaign effectiveness.

## Objectives

* Conduct exploratory data analysis (EDA) to understand customer profiles.
* Identify customer segments based on purchasing behaviors.
* Determine key attributes influencing customer responses to marketing campaigns.
* Provide actionable insights for enhancing marketing effectiveness.

## Data

The dataset used was the "Customer Personality Analysis" dataset from Kaggle, containing customer demographics, purchase history, and responses to marketing promotions. It comprises 2,240 records and 29 columns and was designed to help businesses tailor products to different customer segments based on the attributes: People, Product, Promotion, Place.

## Data Cleaning and Preparation

* Identified and addressed missing values through median imputation or removal of affected records.
* Categorical variables (e.g., marital status, education) were transformed using one-hot encoding.
* Outliers in income and purchase data were managed to ensure data integrity.
* I specifically handled the data preparation phase, including removing unnecessary data, performing one-hot encoding for categorical variables, and creating the distance matrix using Euclidean distance for agglomerative clustering.

## Exploratory Data Analysis

* Performed statistical analysis and visualizations using pandas, matplotlib, seaborn, and other Python libraries.
* Examined distributions of customer demographics, income levels, and purchasing behaviors.
* Conducted correlation analyses to explore relationships between variables.

## Key Findings

* Higher-income customers spent more, especially on premium products, and responded positively to marketing campaigns.
* Families with children demonstrated distinct purchasing behaviors focused on essentials rather than luxury items.
* Higher educational backgrounds were associated with higher campaign response rates.

## Conclusions

* Targeting high-income and highly educated customer segments can significantly enhance marketing success.
* Tailored promotions based on family composition can improve customer engagement and sales effectiveness.

## How to Run the Code

1. Ensure Python is installed.
2. Download the notebook and dataset.
3. Execute the notebook cells sequentially in a Jupyter Notebook environment.

## Dependencies

* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy
* Jupyter Notebook

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy notebook
```

## Future Work

* Implement advanced clustering algorithms (e.g., K-means, hierarchical clustering) for more detailed customer segmentation.
* Integrate additional datasets, such as social media engagement metrics, to enrich analysis and provide deeper insights.
