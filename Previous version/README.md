# ads1002-project

### Topic 3: Forecasting sales - Analysis of Rossmann Drugstore Sales

(from vid) Main task: After exploratory data analysis, create machine learning models to predict sales for up to four weeks in advance
- linear regression
- then maybe, random forest classifiers
<br><br>misc. notes:
- no need use test.csv (??) merge store details csv + train csv
- involves handling time series data (week 5 content)

<hr>

#### Week 4 notes
-	Standardize the codes (more cohesive) - use method chaining etc.
-	Min. one push per week

#### Week 5 notes
- created 2 separate notebooks: one is draft (messy), one is official (neat)

#### Week 6 notes
### we only use store.csv and train.csv (MERGE them)
- merge + clean data (imputation) by end of this week
- features: StoreType, Assortment, CompetitionDistance, Promo2, PromoInterval,	DayOfWeek, Customers || target: Sales

#### Week 7 notes
- main RQ: Predicting sales for four weeks and then interpreting results.
- sub RQ: Creating a simple model that can represent the relationship between sales and variables. (what factors affect sales? how do they affect sales?)

#### Week 10 notes
- ml algorithm 1. regression tree (single decision tree regression) -hs
- ml algorithm 2. random forest -max
- (later on, in report) analysis + if best model used is xxx, explain why choose xxx
