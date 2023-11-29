# Public_Health_Nutrition_Analysis

Data Preparation for Public Health Nutrition Analysis

## Description

This project aims to clean and preprocess nutritional data for a public health organization, "Santé publique France." The provided functions handle tasks such as calculating missing data percentages, filtering data for France, cleaning NaN values, removing outliers, and standardizing column titles. The outcome is a streamlined dataset ready for in-depth nutritional analysis.

## Functions

- **`ratio_nan(dataframe)`:** Calculate the percentage of missing data.
- **`filter_france(dataframe)`:** Filter data for France.
- **`nettoyage_nan(dataframe, ratio_max_nan)`:** Clean NaN values and handle duplicates.
- **`suppression_outliers(dataframe)`:** Remove outliers.
- **`traitement_pnns(dataframe)`:** Standardize values in PNNS groups columns.
- **`imputation_nan(dataframe)`:** Impute missing values using the median of PNNS groups.
- **`traitement_final(dataframe)`:** Apply all data cleaning and preprocessing steps.

## Data Analysis

Utilizing Matplotlib and Seaborn, the analysis explores the following aspects:

1. **Correlation Analysis:** Investigate correlations between key nutritional variables to identify potential relationships.

2. **Geographical Distribution:** Visualize the distribution of nutrition data across different regions of France, providing insights into regional health disparities.

3. **Temporal Trends:** Examine how nutritional patterns have evolved over time, highlighting any significant trends or changes.

4. **Demographic Insights:** Explore variations in nutrition based on demographic factors, such as age groups or gender.

5. **Public Health Implications:** Draw conclusions from the analysis that could inform public health strategies and interventions.

## Results

The cleaned dataset provides a solid foundation for nutrition analysis, offering insights into public health trends.

## Acknowledgments

Data sourced from "Santé publique France."

## Author

This project was created by Fouad Maherzi.
