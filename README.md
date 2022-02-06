# Project-Data-Science
Compilation of my data science projects

## PROJECT 01: REGULARIZATION
In this project, I use Engineering_graduate_salary.csv data from kaggle to predict salary of engineering graduate in India. I try to use Lasso Regression Model for feature selection and to find out wether the feature selection will improve my model performance or not. I also try to tuning the hyperparameter, scaling, and polynomial features, and then compare all of those scenario to find the best model that has smallest RMSE and smallest standard deviation (most stable). In the end, I choose the best scenario for the final model.


## PROJECT 03: FEATURE SELECTION
For some purpose, like interpretability, computational speed, reduce overfitting, etc., data scientists do feature selection in their project. There are so many technique in feature selection. In this notebook, I will use some feature selection method.
1. Filter method: is used in preprocessing step.
  - Missing Value Percentage
  - Low Variance
  - Duplicate

2. Wrapper method: add/drop 1 feature one-by-one and then use the best performance in prediction
  - Forward method
  - Backward method
  - Exhaustive method

I mentioned their advantage and disadvantage as well.
