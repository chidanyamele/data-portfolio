# Longitudinal Demographic Analysis of Minnesota Counties

## Project Overview

This project performs a longitudinal analysis of demographic, educational, economic, and housing trends in the ten most populous counties in Minnesota between 2009 and 2024. The goal is to understand how these factors have changed over time and how they relate to the well-being of the counties.

## Objectives

*   Track the well-being of each county using key metrics such as income levels, educational attainment, homeownership, and population change.
*   Identify correlations and disparities between counties and across time.
*   Use historical data to support the prediction of life outcomes.

## Data

The data for this project was collected from the official US Census Bureau website and is organized into four separate tables: Demographic, Education, Economic, and Housing.

Each dataset includes the following common columns:
*   **County:** Name of the county.
*   **Year:** The year the data was collected.

Specific columns for each dataset:

*   **Demographics:**
    *   **Population:** Total population of the county.
    *   **ImmigrantPop:** Percentage of the population that is foreign-born (immigrant).
    *   **NextHighestPopGrp:** The racial or ethnic group with the next-highest population percentage in the county after the White-only population.
    *   **NextHighestPop:** The percentage of the population belonging to the NextHighestPopGrp.

*   **Education:**
    *   **HighSchoolGraduationRate:** Percentage of the population aged 25 and over with a high school diploma or equivalent.
    *   **BachelorsOrHigher:** Percentage of the population aged 25 and over with a bachelor's degree or higher.

*   **Economic:**
    *   **MedianHouseholdIncome:** Median income for households in the county.
    *   **PovertyRate:** Percentage of the population living below the poverty line.

*   **Housing:**
    *   **HomeownershipRate:** Percentage of owner-occupied housing units.
    *   **MedianHousingValue:** Median value of owner-occupied housing units.

## Data Cleaning and Preparation

The project involves loading the individual CSV files into pandas DataFrames and merging them to create combined datasets for analysis. This includes merging the economic and education data, and the economic and housing data. Column names are also stripped of leading/trailing whitespace.

## Exploratory Data Analysis

The analysis includes visualizations to explore the relationships between different metrics:

*   **Higher Education Attainment vs. Median Household Income:** Investigating the correlation between the percentage of the population with a bachelor's degree or higher and the median household income.
*   **High School Graduate vs. Median Household Income:** Analyzing the relationship between the high school graduation rate and median household income.
*   **Homeownership Rate vs. Median Household Income:** Examining the connection between the homeownership rate and median household income.
*   **Immigrant & Racial/Ethnic Group Trends:** Visualizing changes in the percentage of the immigrant population and the percentage of the next highest racial/ethnic group over time for each county.

## Key Findings

*   Educational attainment beyond high school is strongly correlated with income growth.
*   Urban and suburban counties showed larger gains in income and education compared to more rural counties.
*   Immigrant populations and the next highest racial/ethnic groups generally increased across most counties, indicating growing diversity.

## Conclusions

*   Investing in higher education is a critical factor for improving economic well-being and potentially predicting positive life outcomes.
*   Homeownership is an indicator of stability but doesn't appear to drive income growth as significantly as higher education.
*   Increasing diversity highlights the need to consider how demographic shifts intersect with educational and economic trends in future analyses.
*   Disparities between urban/suburban and rural counties suggest the need for targeted interventions to ensure equitable opportunities.

## How to Run the Code

1.  Clone or download the repository.
2.  Ensure you have the necessary libraries installed (`pandas`, `plotly`, `matplotlib`, `seaborn`, `kaleido`). You can install them using pip: bash pip install -U pandas plotly matplotlib seaborn kaleido
3.  Place the data files (`demographics.csv`, `education.csv`, `economy.csv`, `housing.csv`) in a location accessible by your notebook. If using Google Colab, you can mount your Google Drive and update the file paths accordingly.
4.  Run the Python code cells in the provided Jupyter Notebook or Colab notebook sequentially.

## Dependencies

*   `pandas`
*   `plotly`
*   `plotly.io`
*   `matplotlib`
*   `seaborn`
*   `kaleido` (for exporting plotly figures)

## Future Work

*   Incorporate additional data sources for a more comprehensive analysis.
*   Explore the intersection of demographic shifts with educational and economic trends in more detail.
*   Investigate the impact of specific local or state policies on these trends.

