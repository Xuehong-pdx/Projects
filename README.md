These is a collection of sample projects using Python or SQL to analyze different types of data to gain insights.  The main Python libraries used are Pandas, Numpy, Matplotlib and Scikit-learn.

# Python-Projects

-	In the <b>“Price prediction using multiple ML algorithms”</b>, I used a housing sale dataset to compare the performance of several ML algorithms.  
    I first prepared the data set by removing null values, redundant features based on correlation and similarity analysis, transformed the categorical variables.  

    Next, I compared the performance of several machine learning models, including linear regression, knn, random forest and decision trees using Scikit-learn.  
    
     For each model, I performed feature selection based on metrics determined by cross-validations.  I also optimized hyperparameters for knn, random forest and decision tree models using grid-search algorithm.  Finally, I used a test data set to compare the performance of the models to select the best model.  
     
-	In the <b>“Time series analysis”</b>, I first performed exploratory data analysis using data visualization on a data set that contains 4 months of web visit counts aggregated every 15 min.  

    I used both Statsmodel and Fourier Transform (Scipy) to decompose and learn about the cyclic nature of the data.
  
    Facebook’s Prophet was used to forecast activities a week ahead.  
  
    Both statsmodel and fbprophet were able to estimate the daily and weekly cyclic nature of the data.  Both also detected a drop in acitivity in the month of July, consistent           vacation times.


# SQL-Projects

    In <b>'Sales performance analysis-SQL-Python'</b>, I downloaded a database containing sales data from 'AdventureWorks' using Microsoft server.  Final analysis was performed    using Pandas to answer various business questions.  Sample reports based on these analysis are included.
