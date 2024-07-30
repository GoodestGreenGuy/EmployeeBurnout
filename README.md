# Mental Fatigue Analysis Project
## Overview
This project aims to analyze the impact of burn rate and resource allocation on mental fatigue among employees. By conducting a hypothesis test and building a regression model, we seek to understand the significant predictors of mental fatigue and provide actionable insights that can be valuable for military stakeholders.

### Project Structure
notebooks: Contains Jupyter notebooks used for data analysis and visualization.
src: Contains Python scripts for data processing and modeling.
data: Contains the dataset used for the analysis.
img: Contains images and plots generated during the analysis.
README: Project overview and documentation.
Dataset

The dataset used in this project includes the following columns:

Employee ID: Unique identifier for each employee.

Date of Joining: Date when the employee joined the company.

Gender: Gender of the employee.

Company Type: Type of company (Service/Product).

WFH Setup Available: Whether a Work From Home setup is available.

Designation: Employee's designation within the company.

Resource Allocation: Amount of resources allocated to the employee.

Mental Fatigue Score: Employee's mental fatigue score.

Burn Rate: Employee's burn rate.

### Project Steps
1. Data Wrangling
Loaded the dataset and inspected the initial structure.
Cleaned the data by removing rows with missing values.
Extracted relevant columns for analysis.
2. Exploratory Data Analysis
Generated correlation plots to understand the relationships between mental fatigue and other variables.
Visualized the distribution of mental fatigue scores across different company types and designations.
3. Hypothesis Test
Null Hypothesis (H0): There is no impact of burn rate and resource allocation on mental fatigue.
Alternate Hypothesis (H1): Burn rate and resource allocation significantly impact mental fatigue.
Test Selection: Multiple regression analysis was chosen to determine the predictors of mental fatigue.
Significance Level (alpha): 0.05
4. Regression Analysis
Built a multiple linear regression model to predict mental fatigue based on burn rate and resource allocation.
Checked model assumptions (linearity, homoscedasticity, independence, and normality).
Interpreted the model coefficients and evaluated the significance of predictors.
5. Results
Both resource allocation and burn rate were found to significantly impact mental fatigue.
The model explained approximately 78% of the variability in mental fatigue scores (R-squared: 0.7810).
No significant multicollinearity issues were detected (VIF factors below 10).
6. Value to Military Stakeholders
Insights from this analysis can help military stakeholders manage resources and personnel more effectively.
Understanding the factors contributing to mental fatigue can inform strategies to reduce burnout and improve operational efficiency.

## Files and Directories
### notebooks:

data_analysis.ipynb: Notebook containing data wrangling and exploratory data analysis.

hypothesis_test_and_regression.ipynb: Notebook containing hypothesis test and regression analysis.

### src:

data_processing.py: Script for data cleaning and preprocessing.

regression_model.py: Script for building and evaluating the regression model.

### data:

train.csv: Dataset used for the analysis.

### img:

Various plots generated during the analysis.

# Conclusion
This project demonstrates the significant impact of burn rate and resource allocation on mental fatigue. By providing insights into the factors contributing to mental fatigue, the findings can help military stakeholders make informed decisions to manage resources and personnel effectively.