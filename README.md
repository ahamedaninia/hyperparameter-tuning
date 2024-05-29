# Hyperparameter Tuning

## Project Overview
The purpose of this project is to understand how to incorporate hyperparameter tuning to a given machine learning model. 


## Objectives:
1. Import the dataset and ensure that it loaded properly.
2. Prepare the data for modeling by performing the following steps:
  1. Drop the column “Load_ID.”
  2. Drop any rows with missing data.
  3. Convert the categorical features into dummy variables.
3. Split the data into a training and test set, where the “Loan_Status” column is the target.
4. Create a pipeline with a min-max scaler and a KNN classifier (see section 15.3 in the Machine Learning with Python Cookbook).
5. Fit a default KNN classifier to the data with this pipeline. Report the model accuracy on the test set. Note: Fitting a pipeline model works just like fitting a regular model.
6. Create a search space for your KNN classifier where your “n_neighbors” parameter varies from 1 to 10. (see section 15.3 in the Machine Learning with Python Cookbook).
7. Fit a grid search with your pipeline, search space, and 5-fold cross-validation to find the best value for the “n_neighbors” parameter.
8. Find the accuracy of the grid search best model on the test set. Note: It is possible that this will not be an improvement over the default model, but likely it will be.
9. Now, repeat steps 6 and 7 with the same pipeline, but expand your search space to include logistic regression and random forest models.
10. What are the best model and hyperparameters found in the grid search? Find the accuracy of this model on the test set.
11. Summarize the results.
