# Capstone
This is my capstone project for IBM data science certificate

In this project, our goals are to understand the factors that contribute to the successes and failures of SPACEX rocket launches. We know that the primary factor in cost is if the first stage of the rocket will land.

After performing EDA with SQL and scatterplots I split the historical launch outcome data into training and testing sets. Then evaluated the sets on multiple machine learning models (SVM, Decision Tree, KNN, Logistic Regression)  to determine the best method of prediction. 

Our results present SVM as the model with the highest accuracy for prediction. Further conclusions are,
  FT boosters have the highest success rate for Falcon 9
  Orbits in LEO have more failures that other orbits in general
  The most successful launches have been from the KSC LC 339A launch site

Lab1:Data Collection
  Using pandas libraries to read the file, importing useful libraries into a notebook, loading files into a DF

Lab2: Web Scraping
  Using BeautifulSoup to extract data off the internet and use or into workable dataframes

Lab3: Data Wrangling
  Understand the types of values in the tables we have read to the database, dealing with missing values, dummy variables, and new columns for easier evaluation

Lab4: EDA with SQL
  Gaining insights about the data using SQL

Lab5: EDA & Viz
  Plotting data for further understanding of the important data, using catplots, barplots and scatter plots

Lab6: Folium Maps
	Mapping SPACEX locations with Folium, visualizing successful and failed launches from each launch location, locating nearest city, highway, coastline to launch locations

Lab7: Dashboards
	Using scatterplots, pie charts, sliding bars and drop downs. Pie chart shows successes of each launch station. Scatterplot with slider bar shows variable payload mass used for all booster versions.

Lab8: Machine Learning Predictions
  After spliting the launch outcome data into training and testing data I evelauate which machine learning model has the best accuracy for predicting future launch outcomes.
