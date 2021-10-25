# Musa_Midterm

Finally made the README which will be our working list to measure our progress. 

Tasks to complete
- [X] Made the Readme
- [X] Data cleaning
  - [X] Organize Landscape Data
  - [X] Organize Library Data
  - [X] Organize Grocery Data
  - [X] Organize Education institution data  
- [X] Feature engineering
  - [X] Simplify Zip code and School district assignment 
  - [X] Area analysis Zip Code
  - [X] Area analysis School District
- [X] Regression
  - [X] Select variables
  - [X] Test model(s) with those vars
  - [X] Moran's I
  - [X] MAE / MAPE
- [X] Regression Interpretation -
  - [X] Do we need to return to feature engineering?
  
  
  
- [ ] Report
  - [X] Intro
  - [ ] Data
	- [X] Brief overview of data collection
	- [ ] Table of summary statistics w/ variable descriptions, sorted by category (internal, amenities/public services, spatial structure)
	- [X] Correlation matrix
	- [X] 4 home price correlation scatter plots - looking for interesting open data
		- [X] Internal characteristics
		- [X] Education nn's
		- [X] Amenities nn's
		- [X] Public services nn's
	- [X] 1 map of home prices (dependent variable)
	- [X] 3 maps of the 3 most interesting independent variables
		- [X] Zip code
		- [X] White / Black / Asian Quartiles
	- [X] Any other charts/maps of interest
  - [ ] Methods
	- [ ] Discussion of modeling methods for a lay-person
  - [ ] Results
	- [X] Split toPredict == 0 into training and test datasets
	- [X] Polished table of the summary for the model for the training set
	- [ ] RESULTS OF CROSS-VALIDATION TESTS 
		- [ ] Mean and Standard deviation MAE - use 100 folds and plot cross-validation MAE as a histogram
	- [X] Plot of predicted prices as a function of observed prices
	- [X] Map of residuals for test set
		- [X] Moran's I of test model
		- [X] Plot of spatial lag in errors
	- [X] Map of predicted values for all homes
	- [X] Map of MAPE by neighborhood for test set
	- [X] Scatterplot of MAPE (per neighborhood) as a function of mean price by neighborhood
	- [X] Test generalizability on two groups (i.e. race/income)
  - [ ] Discussion
	- [X] Effective?
	- [X] More interesting variables?
	- [X] How much variation could be explained?
	- [X] What were the more important features?
	- [X] Causes of error in predictions
	- [X] Account for spatial variation in prices?
	- [X] Where does model predict well? poorly? Why?
  - [X] Conclusion
	- [X] Recommend to Zillow?
	- [X] Improvements?