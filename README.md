# ACS_Poverty_Clustering

After reading the documentation, the audience (advanced data Science students, aspirational data analyst) will know how to do the following tasks:

* Large dataset 'Data Cleaning' steps 
* Understand how to use Kmeans clustering, Agglomerative clustering in loops for different dataset

Project Background- The purpose of this project is to find the trend of poverty in the zip codes by analyzing various demographic variables through machine learning techniques and identify which zip codes fall ‘under poverty’ criteria.

Case Steps
Following steps are taken to solve this case

1.1 Read the data, preprocess them to select correct variables and variable type. Then do the exploratory data analysis (Univariate and Bi-variate analysis).

1.2 Scale the necessary variables using MinMax scaling, then apply Kmeans and agglomerative clustering. Use Silhoutte score to compare the models. 

1.3 Analyse the clustering result with actual result to see if there's mismatch of zipcodes being labelled as 'underPoverty' by the ML model as compared to actual result. Also see if new zipcodes are being labelled as 'underPoverty' status in subsequent years. 

1.4 Extract the new zipcodes which are labelled as 'underPoverty' in different years and preprocess them for AR mining

1.5 Use apriori rules in R studio to mine combinations of rules that might help in understanding the combination of variables that might help in indicating poverty status. 


Expected Outcome:
To come up with a clustering model thay can helps in labelling zipcodes poverty level and help in what factors are leading to poverty in particular zipcode

Data Understanding
Each dataset for corresponding years has around 2800 rows and 21 columns.

Data preparation
Code Used: Python, R

Python Version: 3.8.8

Python Packages: Pandas, Numpy, Matplotlib, Seaborn, Sklearn, ipywidgets
R Packages: arules, arulesViz
