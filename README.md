The original source for this data is the UCI Data Repository,but this is an edited version of the dataset with some null values.

	Each wine sample(row) has the following characteristics(columns)-
	1. Fixed acidity
	2. Volatile acidity
	3. Citric acid
	4. Residual sugar
	5. Chlorides
	6. Free sulfur dioxide
	7. Total sulfur dioxide
	8. Density
	9. pH
  10. Sulphates
  11. Alcohol
  12 Quality 

Some properties of the dataset are:

	# there are 4896 rows and 12 columns
	# mostly all features have object data type
	# all columns have some null entries,total = 120
	# column quality has some non numeric entries such as low,high
	# All wines are not unique, there are only 4013 unique wines
	# scale of different attributes is not equal,for example scale of volatile acidity is 0.08-1.1 whereas 
	  for total sulphur dioxide it is 9 - 440
	
Below is the list of works that have been as a part fo this project:

	1. Predicted the quality of wine, given the input features using Linear regression, k-nearest neighbour, 
	   and decision tree model
	2. Visualising the data using frequency histograms, scatter plots and heat map
	3. Cross validated the result and optimised the model parameters
