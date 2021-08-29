# Project-Data-Science
Compilation of my data science projects

# PROJECT 01: REGULARIZATION
In this project, I use Engineering_graduate_salary.csv data from kaggle to predict salary of engineering graduate in India. I try to use Lasso Regression Model for feature selection and to find out wether the feature selection will improve my model performance or not. I also try to tuning the hyperparameter, scaling, and polynomial features, and then compare all of those scenario to find the best model that has smallest RMSE and smallest standard deviation (most stable). In the end, I choose the best scenario for the final model.

This is what i did in this project:

0. Load dataset 

1. Preprocessing
> ![preprocessing](https://user-images.githubusercontent.com/74049658/131243464-6a8f93c6-5f2a-4ba8-afac-d150dac31602.PNG)

2. Data splitting

3. Choose model as benchmark (Ridge)
> ![benchmark](https://user-images.githubusercontent.com/74049658/131243376-64ab0502-6c32-407c-9f78-9e501747ed5b.PNG)

4. Feature selection with Lasso (Feature selection didn't improve model performance)

> Important Fetures
> 
> ![fetures_imp](https://user-images.githubusercontent.com/74049658/131243537-a9469472-9a4a-4cdc-a451-4e7b2b1876a5.PNG)

> Not-important Fetures
> 
> ![fetures_not_imp](https://user-images.githubusercontent.com/74049658/131243544-a1ae7d45-e3d2-4f7f-9475-9e68a2b0fd46.PNG)

> Result
> 
> ![result_model_imp](https://user-images.githubusercontent.com/74049658/131243430-9d769013-5ff1-4afc-8e5c-4ba5ae026f42.PNG)

5. Hyperparameter tuning
> ![hyper_tuning](https://user-images.githubusercontent.com/74049658/131243491-1741fe9f-a965-43de-be57-abc82d30229b.PNG)

6. Scaling (with Robust Scaler)

7. Polynomial features (Polynomial features didn't improve model performance) 

8. Best model for this dataset is 
> ![all_scenario](https://user-images.githubusercontent.com/74049658/131243501-73eb9b67-07c3-4963-9559-e8562855cb7f.PNG)

>- Ridge  
>- With all features
>- With penalty: alpha = 148.64
>- Scaled with Robust Scaler
