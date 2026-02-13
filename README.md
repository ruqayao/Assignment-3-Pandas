# Assignment-3-Pandas
# Purpose
The purpose of this project is to load and analyze the Fisher Iris dataset using Python and Pandas. The project demonstrates how to combine multiple datasets and perform statistical analysis to better understand relationships between variables.
# Project Overview
Two datasets were provided:
- Sepal measurements
- Petal measurements

These datasets were combined into one DataFrame using Pandas merge functionality.

The final dataset included:
- Sample ID
- Species
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
# Analysis Performed
The following statistical analyses were performed:
- Correlation between measurement variables
- Mean (average) of each measurement
- Median of each measurement
- Standard deviation of each measurement
- Comparison of species similarity
# Findings
- Petal length and petal width showed strong positive correlation.
- Setosa differs significantly in petal measurements.
- Versicolor and Virginica are most similar based on average measurements.
# Design and Implementation
The project uses:
- Pandas Series for statistical calculations.
- Pandas DataFrames for structured data manipulation.
- GroupBy for species-level comparison.

No classes were required for this implementation because Pandas provides built-in methods for structured data analysis.

# Limitations
- The analysis assumes clean datasets.
- No missing data handling was implemented.
- The project focuses only on descriptive statistics.
