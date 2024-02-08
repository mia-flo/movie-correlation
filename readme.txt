movie data set (1980 - 2020)

7668 initial entries and 15 columns (5421 entries after cleaning)

modules used:
-pandas
	-cleaned (checked for duplicates, dropped entries that contained null values in any column, changed data types from float to int 	and rating and genre to categorical variables)
	-summary statistics of numerical and categorical features
	-plot histograms of numerical features to get a sense of their distribution
	-correlation matrix
	-unstacked matrix to correlation pairs by their strength
	-groupby to get 20 the top grossing companies and the top 20 companies by number of films

	


-seaborn
	-box plots
	-linear regression (lmplot)
		--budget vs gross has a strong relationship
		--votes vs score, budget vs votes, runtime vs score show more moderate relationships
		--runtime vs gross, year vs gross, score vs gross, year vs votes show a weaker relationship
	-lineplot of how budget and gross have changed over time
		--the gross has greatly increased over time
		--the budget has seen more moderate increase
		--the gross/budget ratio has skyrocketed since the 2000s
		--see a huge downturn coinciding with the pandemic
	-stripplot of movie ratings vs gross
		--the most popular is PG-13 and is also has the biggest range and highest gross
		--PG and R rated movies are approximately 2nd and 3rd
	-stripplot of genre vs gross
		--the most popular genres are action, animation, and adventure
		--biggest range and highest gross are action and animation
		
	

-numpy
	-checked for missing data
-matplotlib


