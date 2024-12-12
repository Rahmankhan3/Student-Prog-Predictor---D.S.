# Student-Prog-Predictor---D.S.
This is my data science project which predicts the program to be choosen by a student based on their demographic and academic attributes. 

Algorithms Used:
1.Logistic Regression
  -Used as the classifier to predict the target variable prog.
  -It calculates probabilities of the target classes using a linear equation and applies a threshold to make predictions.
  
2.OneHotEncoding and Standard Scaling:
 OneHotEncoding -
  -Transforms categorical variables into a numerical format that machine learning algorithms can understand.
Standard Scaling -
  -Standardizes numerical features so that they have a mean of 0 and a standard deviation of 1. This helps most machine learning models (especially linear ones) perform better.
  -Ensures numerical features are on a similar scale, improving the convergence of optimization algorithms used by models like Logistic Regression.
