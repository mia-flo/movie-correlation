movie data set (1980 - 2020)

7668 initial entries and 15 columns (5290 entries after cleaning)

modules used:

*pandas

-cleaned (checked for duplicates, dropped entries that contained null values in any column, changed data types 	from float to int and rating and genre to categorical variables)
-summary statistics of numerical and categorical features
-plot histograms of numerical features to get a sense of their distribution
-correlation matrix
-unstacked matrix to correlation pairs by their strength
-groupby to get 20 the top grossing companies and the top 20 companies by number of films
-used apply to find each actor and each director's efficiency value (total gross/total budget)

*numpy

-checked for missing data
-drop duplicates
-drop entries that have NaN for any value
-get the mean scores for the linear regression model over 10 KFolds


*seaborn

-box plots of budget and gross

-lineplot of how budget and gross have changed over time
=the gross has greatly increased over time
=the budget has seen more moderate increase
=the gross/budget ratio has skyrocketed since the 2000s
=see a huge downturn coinciding with the pandemic

-stripplot of movie ratings vs gross
=the most popular is PG-13 and is also has the biggest range and highest gross
=PG and R rated movies are approximately 2nd and 3rd

-stripplot of genre vs gross
=the most popular genres are action, animation, and adventure
=biggest range and highest gross are action and animation

-heatmap of correlation matrix - most relationships are moderate
=budget vs gross 0.74
=votes vs gross 0.62
=score vs votes 0.47
=budget vs votes 0.44
=runtime vs score 0.41

-linear regression (lmplot) - 95% confidence interval
=budget vs gross r2: 55
=votes vs gross r2: 38
= budget vs votes r2: 19
=runtime vs score r2: 17

		
*matplotlib
=plot predicted gross and actual gross from the test split


*sklearn

-linear-model's LinearRegression to perform a multivariable linear regression to predict movie gross
-preprocessing to normalize data and 
-one-hot-encode categorical variables movie rating and genre
-KFold cross validation (random state = 1, 10 splits, shuffled)
-scored the model using cross_val_score, mean_squared_error, mean_absolute_error, r2_score
 









