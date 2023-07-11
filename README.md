# README - Analysis of NY Restaurant Inspection Data

This code performs data cleaning and statistical analysis on a dataset of NY restaurant inspections. It utilizes the pandas library for data manipulation and matplotlib for data visualization.

## Prerequisites
- pandas
- matplotlib

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

## Findings
- The average score of the inspected restaurants is [mean value].
- The distribution of scores follows a [skewness] skewness, indicating [distribution type].
- The [BORO] has the highest number of inspections with [count], followed by [BORO] with [count].

## Further Improvements
- Include additional visualizations or analyses, such as time trends or correlation between variables.
- Explore the relationship between the "SCORE" and other columns to identify potential factors influencing inspection results.

For any questions or further information, please email [mwassdennoh7@gmail.com].

