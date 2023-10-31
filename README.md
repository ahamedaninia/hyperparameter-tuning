# hyperparameter-tuning
DSC 550 Week 9 assignment - Hyperparameter Tuning

Objectives for this assignment:
Import the dataset and ensure that it loaded properly.
Prepare the data for modeling by performing the following steps:
Drop the column “Load_ID.”
Drop any rows with missing data.
Convert the categorical features into dummy variables.
Split the data into a training and test set, where the “Loan_Status” column is the target.
Create a pipeline with a min-max scaler and a KNN classifier (see section 15.3 in the Machine Learning with Python Cookbook).
Fit a default KNN classifier to the data with this pipeline. Report the model accuracy on the test set. Note: Fitting a pipeline model works just like fitting a regular model.
Create a search space for your KNN classifier where your “n_neighbors” parameter varies from 1 to 10. (see section 15.3 in the Machine Learning with Python Cookbook).
Fit a grid search with your pipeline, search space, and 5-fold cross-validation to find the best value for the “n_neighbors” parameter.
Find the accuracy of the grid search best model on the test set. Note: It is possible that this will not be an improvement over the default model, but likely it will be.
Now, repeat steps 6 and 7 with the same pipeline, but expand your search space to include logistic regression and random forest models with the hyperparameter values in section 12.3 of the Machine Learning with Python Cookbook.
What are the best model and hyperparameters found in the grid search? Find the accuracy of this model on the test set.
Summarize your results.
