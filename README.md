# Visual.Pandas.Matplotlib

# Pymaceuticals Data Analysis

## Overview
This project analyzes data from a recent animal study conducted by Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The study involved 249 mice identified with squamous cell carcinoma (SCC) tumors who received various drug regimens. The purpose was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

## Data Preparation
- Merged the `mouse_metadata` and `study_results` DataFrames into a single DataFrame.
- Checked for duplicate mouse IDs and removed any data associated with duplicate time points.

## Summary Statistics
- Generated a DataFrame of summary statistics, including mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

## Bar Charts and Pie Charts
- Created bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using both Pandas DataFrame.plot() and Matplotlib's pyplot methods.
- Generated pie charts displaying the distribution of female versus male mice in the study using both Pandas DataFrame.plot() and Matplotlib's pyplot methods.

## Quartiles, Outliers, and Box Plot
- Calculated the final tumor volume for each mouse across four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Determined potential outliers using the upper and lower bounds of the tumor volumes.
- Created a box plot to visualize the distribution of the final tumor volume for all mice in each treatment group.

## Line Plot and Scatter Plot
- Selected a single mouse treated with Capomulin and generated a line plot of tumor volume versus time point.
- Produced a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

## Correlation and Regression
- Calculated the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
- Plotted the linear regression model on top of the scatter plot.

## Technologies Used
- Python
- Pandas
- Matplotlib

## Instructions
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter Notebook or Python script to reproduce the analysis.

## Files
- `data/Mouse_metadata.csv`: Dataset containing mouse metadata.
- `data/Study_results.csv`: Dataset containing study results.
- `pymaceuticals_analysis.ipynb`: Jupyter Notebook containing the data analysis code.

## Results
The analysis provides insights into the performance of Pymaceuticals' drug of interest, Capomulin, compared to other treatment regimens. Key findings include:
- Summary statistics for each drug regimen.
- Visualization of data distribution using bar charts, pie charts, and box plots.
- Identification of potential outliers in tumor volume data.
- Correlation and regression analysis between mouse weight and tumor volume for the Capomulin regimen.

Please refer to the Jupyter Notebook for detailed code and visualizations.

## Contact
For any questions or inquiries, please contact Luis R. Rivera Jr. at elluis.lr1@gmail.com.
