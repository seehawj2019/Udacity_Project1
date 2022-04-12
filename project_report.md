# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Shing Her

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: After submitting my results, they were rejected with an error.  The reason for this is because I didn't have the "DateTime" column.  I only had just the "count" prediction.

### What was the top ranked model that performed?
TODO: WeightedEnsemble_L3

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: The EDA found negative values which they had to be set to zero.  The addtional features created was to split out the datetime to YEAR, MONTH, and DAY.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: The initial model for WeightedEnsemble_L3 has a score of -112.656462 while with the new features WeightedEnsemble_L3 had a score of -50.261669

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: After trying the two new hyper parameters, it remained the same as the initial.  I'm not sure how to conduct this hyper paramemters tuning so I'm sure I did it incorrectly.

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I would spend more time of hyper parameter tuning.  This is something that I don't know how to use the API and I'm not familiar with it.  This is something that I'm struggling with.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.

model	hpo1	hpo2	hpo3	score
0	initial	None	None	None	1.40864
1	add_features	None	None	None	1.82494
2	hpo	num_epochs	learning_rate	activation	1.40864



### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![](model_test_score.png)


### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.



## Summary
TODO: Add your explanation
