# Random-Forest-Intuition

Truth or Bluff model testing on Random Forest regression model Truth or Bluff using Random-Forest model. The dataset and prediction aim is same as previous model https://github.com/Hamza-Rayyan/Polynomial_linear_regression

Random Forest is a version of Ensemble learning.
Ensemble Learning: when you take multiple times and you put them together that result in a much more powerful version.
Steps:
  - Pick at random K data points from the Training set.
  -  Build the Decision Tree associated to these K data points.
  -  Choose the number Ntree of trees you want to build and repeat STEPS 1 & 2.
  -  For a new data point, make each one of your Ntree trees predict the value of Y to 
for the data point in question, and assign the new data point the average across all of the 
predicted Y values.
