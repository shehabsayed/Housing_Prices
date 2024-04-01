# Housing_Prices

•	Data Import and Exploration:

    •	Relevant packages like pandas, numpy, plotly, scipy, etc., are imported.
    
    •	The training dataset is imported using pandas.
    
•	Data Exploration and Visualization:

    • Summary statistics are computed for numerical and categorical features separately.
    
    •	Null values in the dataset are identified and displayed.
    
    •	Percentage of missing values for each feature is calculated and displayed.
    
    •	Rows with missing values are explored and displayed.
    
    •	Distribution of dwelling types and their relation to sale prices is visualized.
    
    •	Impact of zoning on sale prices is visualized.
    
    •	Effect of street and alley access types on sale prices is visualized.
    
    •	Average sale prices by property shape and contour are visualized.
    
    •	Property age is calculated and its correlation with sale price is determined.
    
    •	Correlation between living area and sale price is calculated.
    
    •	Sale price trends over the years are visualized using a box plot.
    
•	Data Preprocessing:

    •	Irrelevant columns like 'Id', 'MiscFeature', 'PoolQC', 'Alley', and 'Fence' are dropped.
    
    •	Missing values in specific columns are filled with appropriate values.
    
•	Feature Engineering:

    •	New features like 'PropertyAge' are created.
    
•	Model Building:

    •	Data is split into training and testing sets.
    
    •	Pipelines for different regression models (Linear, Ridge, Lasso) are defined.
    
    •	Hyperparameters are tuned using GridSearchCV to find the best model.
    
    •	The best model is selected based on performance metrics (RMSE and R-squared) on the test set.
    
•	Prediction and Submission:

    •	The best model is used to predict sale prices for the test dataset.
    
    • Results are saved to a CSV file for submission.

