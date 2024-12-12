This project aims to build a machine learning model to predict the program a student will choose based on their academic performance and demographic features. The prediction is made using a Logistic Regression model, which is trained on the data after preprocessing steps such as handling categorical and numerical features.

Steps Involved:
1.Data Loading:
  The dataset is loaded from a CSV file and its first few rows and summary statistics are displayed.
2.Data Preprocessing:
  Categorical features (female, ses, schtyp, honors) are one-hot encoded.
  Numerical features (read, write, math, science, socst, awards) are standardized using StandardScaler.
3.Data Visualization:
  A count plot is used to visualize the distribution of the different programs.
  A heatmap shows the correlation between numerical features.
4.Model Creation: 
  A Logistic Regression classifier is used to predict the program choice.
5.Model Evaluation: 
  The model's performance is evaluated using a Confusion Matrix and Classification Report, which provides detailed performance metrics.
6.Prediction: 
  A function is implemented to predict the program choice for a new student based on their input data.

Key Technologies and Libraries:
-Pandas for data handling
-Matplotlib and Seaborn for data visualization
-Scikit-learn for machine learning model creation, data preprocessing, and evaluation
-Logistic Regression as the classification model

Use Case:
This model can be used by educational institutions or counselors to predict which program a student might be interested in based on their academic background and other demographic features.
