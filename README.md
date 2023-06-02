# House Sale Price Prediction 

●  Developed a house sale price prediction model using linear regression and 
   Sequential models in TensorFlow. Attained accuracies of 70% and 85% using the 
   respective models, highlighting their effectiveness.
   
   
●  Identified a correlation between square footage and house prices, providing   
   crucial insights into the housing market.
   
   
● Implemented a data preprocessing pipeline to handle the necessary data 
  transformations and achieved an overall accuracy of 71%. 


## Conclusion:
In this project, I have built prediction models for house price prediction on a house sale price dataset for King County. Two models were trained, namely Linear Regression and Sequential model from TensorFlow. I achieved an accuracy of around 85% on the sequential model and 70% on Linear Regression, showing that the sequential model performs better.

EDA(exploratory data analysis) was perfomed along with data cleaning and preprocessing, which revealed strong correlations, such as square footage with price. I also analyzed that most of the houses were priced lower than $2 million. I dropped non-important columns like 'id' and 'date'.

During the analysis, I observed fluctuations in price with respect to month and year and found some prominent trends, such as prices dropping at the start of the year and increasing in the mid-year.

To optimize the loss function (Mean Squared Error), The sequential model is used with 400 epochs and employed the ADAM optimization algorithm. This resulted in a lower RMSE (loss function) compared to linear regression, indicating that my predictions are closer to the actual house prices.
