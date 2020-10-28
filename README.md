###### Capstone_two

# Used Car Market Value Prediction
###### By: Mitchell LaBauve

<img src="./img/used_cars.jpeg" alt="used cars pic">


Problem Statement:
Trucktrax will predict the market value of a used vehicle before its opening in November 2020 by analyzing current market data from craigslist.

Context
Trucktrax is a soon to open used car lot that focuses on moving inventory frequently rather than buying and holding. In order to do this, the market value of each vehicle to sell will need to be rooted in current data so that the business model of buying and selling vehicles frequently will stand the test of the market. 

Success Criteria
The criteria for success will be to predict the selling price of any vehicle based on the make, model, year, region and condition. 

Scope
The scope of this project includes Craigslist listed used vehicles in the United States. 

Constraints
Constraints to be aware of are the limited data for every type of vehicle, make, model and so on available at one time resulting in a lack of relevant market data to properly train our model. 

Stakeholders
The stakeholders for this project are the management of Trucktrax, John Smith and Jane Doe. 

The Data
The data source will be from Kaggle’s Craigslist scraper found here (https://www.kaggle.com/austinreese/craigslist-carstrucks-data)
The csv file associated with the data provides 25 columns and 423857 unique values. Some of the columns of interest will be the model, manufacturer, condition and state to name a few. Each instance of data has a unique id and urls referencing its source. For now we will focus on numerical and categorical data for the prediction, but later, NLP may be useful for a more defined and specific prediction.

Final Products
The results of the project will be a model that correctly predicts the market value of each vehicle, a 1-2 page report explaining the findings and why they are significant, and a slide deck presentation to summarize those findings. 

Next Steps Overview
Now that the problem has been defined in a measurable result and supplemental data has been shared, the next step will be to get the data.

Once this data is cleaned for null values and organized appropriately, we will explore the data for descriptive stats, trends and correlations. 

Next, we need some metrics to determine what type of machine learning, if any, will provide the most accurate and reliable result. Some options are MSE, MAE, R2. 
Then once the metrics are identified, the model needs to be selected. Some possibilities are random forest, linear regression, logistic regression, decision tree and then a mix of these models through ensembling. To keep it simple, we will test linear regression and random forest without ensembling for now. But, if there proves to be insufficient data, then we may utilize ensembling to create a more accurate model. Ensembling is a technique including boosting, bagging and stacking that attempts to minimize bias and variance from one single model. 

Overall, the goals in simpler terms are to tidy the data into one field per column and one entity per row with out null values, and to train and compare a linear regression model and a random forest model. 

Let’s get started!
