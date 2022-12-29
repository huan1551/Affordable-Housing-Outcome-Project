# Affordable Housing Outcome Project
## Project Overview
The main goals of analysis are (1) to understand which variables contribute the most to the
failure of affordable housing projects, (2) to construct a predictive model which will help the
major of San Francisco to predict the probability of failure of future projects aiming to provide
affordable housing.
## Data
* The datasets contain information regarding different projects which aim to provide affordable
housing in the city of San Francisco.
* The variables contained in these datasets are described in the file data_description.xlsx
available on Canvas at the same link above.
* The response variable to predict is Failing.

## Analysis
Four Classification Models: Logistic regression, KNN, Decision Tree, and Random Forest

Metrics: Rrror Rates and AUC

### First Iteration
* If any of the variables is continuous and contains missing values,
imputed using the median of that variable.
* If any of the variables is categorical and contains missing values,
excluded the observations with missingness from the analysis.

### Second Iteration
* Used the original dataset, if any of the categorical predictors in the dataset contains
missing values, created a new category missing and assign such category to the missing
observations. 
* Imputed all the missings on the quantitative variables in the dataset using iterative regression (logistic regression). Missings on the continuous variables were imputed using classical linear regression. 
* Repeated all the analyses above.
