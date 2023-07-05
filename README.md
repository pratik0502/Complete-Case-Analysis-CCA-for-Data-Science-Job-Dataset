# Complete-Case-Analysis-CCA-for-Data-Science-Job-Dataset

# Read Me:
This project focuses on performing Complete Case Analysis (CCA) on a dataset called "data_science_job.csv" to handle missing data. CCA involves dropping columns with less than 5% missing values and removing rows with missing values for the remaining columns. The goal is to analyze the impact of missing data on various variables and assess the outcome of the analysis.

# Conclusion:
1. Percentage of Missing Data: The code calculates the percentage of missing data in each column using the `isnull().mean()` function. Columns with less than 5% missing values are identified and dropped from the dataset.
2. CCA Implementation: The remaining columns with missing values are stored in the 'col' variable. Rows with missing values in these columns are dropped using the `dropna()` function, resulting in a new dataset called 'new_df'.
3. Data Retention: The code calculates the percentage of data retained after applying CCA by dividing the length of 'new_df' by the length of the original dataset. In this case, approximately 89% of the data is retained.
4. Analysis of Variables: Histograms and distribution plots are created to compare the original dataset ('df') with the CCA dataset ('new_df') for variables such as 'city_development_index', 'experience', and 'training_hours'. These visualizations provide insights into the impact of CCA on the distribution of these variables.
5. Outcome Analysis: The code analyzes the impact of CCA on categorical variables, specifically 'enrolled_university' and 'education_level'. The proportions of each category before and after CCA are compared, highlighting the changes in percentages.

# Outcome:
The CCA process helps handle missing data in the 'data_science_job.csv' dataset. By dropping columns with less than 5% missing values and removing corresponding rows for the remaining columns, approximately 89% of the data is retained. Visualizations of selected variables demonstrate the effect of CCA on the distribution. Additionally, changes in proportions of categorical variables are analyzed, showcasing the impact of CCA on these variables. The outcome of this project provides valuable insights into the handling of missing data and the resulting impact on the dataset.
