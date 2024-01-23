# Predicting Home Appraisal Values

![image](https://github.com/reggierobbins33-dQeOrZ/proj_2_team_3/assets/142754993/69d7453b-3a8c-4994-8078-b6241b22b86b)

##Models Used

1. Linear Regression
2. Lasso Regression
3. Ridge Regression



##Summary/Overview

Our project is focused on predicting home appraisal values. We wanted to see what factors/variables contribute to home appraisal values. Use correlation to see how each data point associates with each other. We’ll also fit a linear regression model to the home appraisal data to create a predictive model. We’ll also fit and compare a Lasso Regression and Ridge Regression model to the data to compare the performance of the two models.

##How to achieve the desired result
1. In order to achieve the outcome we are looking for we need to first clean the data
2. Explore the date
3. Find any correalation betweein the variables and its realtion the the value of homes
4. Fit the data so that we can model them properly
5. Scale the data
6. Create our train_test_split to see which data to separate from othe variable we are predicting
7. Create our models and show the differeces between the three and see which one was the best predictor

##Conclusion

I found out that these models weren't the best at predicting home values. The mean squared error, mean absolute error, and the coefficients were very far off from 0 and 1. the were showing very high positive and negative values. This told me that this was not going to be the best fit at predicting the appraised values. However, I did find out that the r2 score was a great predicter for this specific dataset with its outcome being very close to 1. All in all I would not use these models for this dataset based off the outcome.
