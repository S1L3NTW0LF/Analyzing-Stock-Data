# Capstone
Final project for university that uses machine learning to analyze financial statements and ratios to predict price movement. 

## Context 
The idea behind the project is to help an investment firm get into algorithmic trading. This has been done by designing a jupyter notebook that will guide the process. The jupyter notebook contains functions and pre-written code to assist the investment firm when using the notebook. Also included is a sample dataset that is analyzed and at the end produces a csv file with a list of stocks to invest in and the predicted price movement. 

Gathering, cleaning, EDA is done. 

## Main Analysis 
Sample financial data is run through RandomForestRegressor

1. R squared score is calculated for both training and testing dataset
2. Kfold is run for an average R squared score on the testing dataset
3. Graph is created with (actual values on x axis and predicted values on y axis) 

4. Appropriate columns are scaled by 'Operating Cash Flow' so comparisons are more accurate across stocks
5. Tables showing the percent profit based on investing on top stocks is shown against actual values
6. R squared values are calculated on these tables 

7. A list of stocks is produced 




 

