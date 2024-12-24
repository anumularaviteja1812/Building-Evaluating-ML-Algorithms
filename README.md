# Project- Building & Evaluating ML Algorithms

## Dataset - Supermarket Sales

The dataset you will be working with has been pushed to this repository under the name "supermarket_sales.csv".

## Tweaks

1. In the training.ipynb, Date and Time encoding are done using the Function Transformers in the pipeline. So, it is necessary to import 'Day_of_week(X)' and 'Timeslot(X)' functions in test.ipynb files as well to run the models.
2. All the models and X_test and t_test values for the repsective models are saved as pickle files from training.ipynb.
3. These models along with their X_test and t_test values are imported into the test.ipynb before making predictions in test.ipynb file

## Files for submission:
1. training.ipynb
2. test.ipynb
3. training.pdf
4. test.pdf
5. model1_lr.pkl - Pickle file for Multiple linear regression model without lasso regularization to predict gross income
6. model1_lasso.pkl - Pickle file for Multiple linear regression model with lasso regularization to predict gross income
7. model2_lr.pkl - Pickle file for Multiple linear regression model without lasso regularization to predict Unit price
8. model2_lasso.pkl - Pickle file for Multiple linear regression model with lasso regularization to predict Unit price
9. model3.pkl - Pickle file for Logistic regression model to predict the gender classification
10. model4.pkl - Pickle file for Logistic regression model to predict the Customer type classification
11. model5.pkl - Pickle file for Decision Tree classifier model to predict the day of purchase classification
12. model6.pkl - Pickle file for Random Forest classifier model to predict the day of purchase classification
13. X1_test.pkl and t1_test.pkl - X_test and t_test pickle files for Multiple linear regression model(with and without lasso) to predict gross income
14. X2_test.pkl and t2_test.pkl - X_test and t_test pickle files for Multiple linear regression model(with and without lasso) to predict unit price
15. X3_test.pkl and t3_test.pkl - X_test and t_test pickle files for Logistic regression model to predict the gender classification
16. X4_test.pkl and t4_test.pkl - X_test and t_test pickle files for Logistic regression model to predict Customer type classification
17. X5_test.pkl and t5_test.pkl - X_test and t_test pickle files to predict the day of purchase classification(same sets for both Decision Tree and Random forest classifiers)
18. Report "Project 1 - Building & Evaluating ML Algorithm.pdf" file
19. Edited Readme file containig tweaking to be made and all the files names 
