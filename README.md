# Rossmann Drugstore Sales Forecasting
<hr>

## Framework

### Week 3: Initial Analysis on data science project
 - Understanding the task to forecast sales
 - Problem Statement and Objective
 - Initial observation on data set
<hr>

### Week 4 and 5 : Data Cleaning and Wrangling
 - Data preprocessing *(Hui Shawn, Lim)*
     - Filter top 20% stores
     - Merging data sets
     - Converting datatypes (Categorical variables to dummy variables)
- Imputation *(Chun Kei, Chow)* <br><br>
  Fill in missing values by:
     - Simple mean, median imputation
     - kNN imputation
     - Forest imputation
     - Linear regression imputation <br>
     
  **kNN imputation** is used and proceed with cleaned data frame with variable **rm_imputed**
  
<hr>

#### Week 6: Exploratory Data Analysis
- Initial data analysis *(Sunaina, Rayaraprol)*
    - Descriptive statistic
    - Graphs plotting (histogram,boxplot, etc)

- Time series analysis *(Hui Shawn, Lim)*
    - Analysis with rolling mean
    - Finding trendline across 3 years sales

<hr>

#### Week 7 : Features Selection
-	Multivariable Linear Regression *(Zhen Xue, Gue)*
    - Pearson Correlalation heatmap
    - Coefficient importance
    - Normalisation

-	Regularisation and Features Selection *(Zhen Xue, Gue)*
    - Lasso and Ridge regression
<br>

**Features selected:** <br>
features: StoreType, Assortment, CompetitionDistance, Promo2, PromoInterval,	DayOfWeek, Customers <br>
target  : Sales

<hr>

#### Week 8 and 9 : Predictive modelling and Machine Learning ALgorithms
- Single modelling *(Hui Shawn, Lim)*
    - Decision Tree Regressor

- Ensemble Learning *(Chun Kei, Chow)*
    - building metrics and loss function (RMSE, MAE, MPSE) to evaluate model performance
    - Cross validation and hyperparamter tuning (using `RandomizedSearchCV`) for every model:
        - Random Forest Regressor
        - Bagging (Bootstrap aggregation)
        - Boosting (Adaptive Boosting/AdaBoost, Gradient Boosting, Extreme Gradient Bossting/XGBoost)
        - Stacking model
     
  **Short conclusion:**
  - After all model building and evaluation, the **Stacking model** where  `RandomForestRegressor` stacked with `XGBRegressor` and `GradientBoostRegressor` performed the best.
 




