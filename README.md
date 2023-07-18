# Analysis of NY Restaurant Inspection Data

This code performs data cleaning and statistical analysis on a dataset of NY restaurant inspections. It utilizes the pandas library for data manipulation and matplotlib for data visualization.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Findings](#findings)
- [Further Improvements](#further-improvements)

## Prerequisites
- pandas
- matplotlib
- seaborn
- numpy

## Usage
1. Download the dataset from [https://drive.google.com/file/d/12mIexXTY7FzY_UFLswhpXpZmqQJe7mWG/view?usp=drive_link] and save it as "NY_restaurant_inspection.csv".
2. Ensure the dataset is placed in the same directory as the code file.
3. Run the code in a Python environment.

## Code Overview
1. The code reads the dataset into a pandas DataFrame and performs initial data cleaning.
2. It checks for missing values and duplicates, dropping irrelevant columns.
3. Missing values in specific columns are handled, and duplicate rows are removed.
4. Data types of certain columns are converted for appropriate analysis.
5. Leading and trailing whitespaces are removed from string columns.
6. The cleaned dataset structure is displayed.
7. Statistical analysis is performed on selected columns, including mean, median, range, standard deviation, skewness, variance, mode, and kurtosis.
8. A histogram of the "SCORE" column is plotted using matplotlib.
9. A clustered bar plot of the counts by "BORO" is generated.
10. The README file provides an overview of the code, instructions, and notable findings.

## Findings(analysis(1).ipynb)
The average score of the inspected restaurants is 15.32.
The distribution of scores follows a positive skewness, indicating that the majority of restaurants have scores lower than the average. This suggests that most restaurants tend to receive relatively good inspection scores.
The Bronx (BORO) has the highest number of inspections with 10,500, followed by Brooklyn with 9,800, Manhattan with 8,700, Queens with 7,900, and Staten Island with 2,500.

## Results(NY_restaurant_analysis.ipynb)

The analysis provides valuable insights into NYC restaurant inspections, such as:

- The top 10 cuisine types in NYC restaurants.
- The distribution of restaurant grades.
- The correlation between numerical columns like 'SCORE' and 'ZIPCODE'.
- The skewness and kurtosis of the 'SCORE' column, which can provide insights into the distribution's shape.

## Further Improvements
- Include additional visualizations or analyses, such as time trends or correlation between variables.
- Explore the relationship between the "SCORE" and other columns to identify potential factors influencing inspection results.

For any questions or further information, please email [mwassdennoh7@gmail.com].
