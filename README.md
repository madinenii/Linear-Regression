# Linear-Regression-Salary Prediction

Step-1:-PREPROCESS THE DATA:-

We will follow the Following Steps:-
  
  1)Import the Libraries.
  
  2)Import DataSet.
  
  3)Check for Missing DataSet.
  
  4)Split the DataSet.
  
  5)Feature Scalling will be taken care by the Library 
    we will use for Simple Linear Regression Model.
    
Step-2:-FIITING SIMPLE LINEAR REGRESSION MODEL TO THE TRAINING SET:-
 
 To Fit the dataset into the model we will use LinearRegression class from 
 sklearn.linear_model library.then we make an object regressor of LinearRegression Class.
 now we will fit the regressor object into our dataset using method of LinearRegression Class.

Step-3:-PREDICTING THE RESULT:-
  
  Now we will predict the observations from our test set. we will save the output in a vector Y_pred.
  To predict the result we use predict method of LinearRegression class on the regressor .
  
Step-4:-VISUALIZATION:-
  
  The Final step is now we visualize our results. we will use matplotlib.pyplot library 
  to make Scatter Plots of our Training set results and test set results to see how close
  our model predicted the Values of Salary to be predicted
