# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### NAME HERE
Arslan Ghazi

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Add your explanation
I realized that my predicted result needed a lot of improvements. The changes that were needed required were extra features and optimization of hyper parameters to get better results. 
### What was the top ranked model that performed?
TODO: Add your explanation
The top ranked model for me was with tuned hypermaters and added extra features.
## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation
Exploratory data analysis changed data types of some features so that autoguon model can understand them better as those data were actually category and autogluon model was utilising them as ints.
### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation
It perfomed much better (the improvement was by a score of 1.2), the reasons was that actually only 1 additional feature was added however all those features which were changed from int to category also contributed since they were actually not part of the model.
## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation
Hyper parameter tuning did made much difference in my case. Just tuning learning rate from 0.5 to 0.02 resulted 

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation
I would work towards adding more features or looking if any feature is still being interpreted incorrectly and take actions accordingly.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|autogluon|num_epochs|num_boost_round|learning_rate|--|
|initial|100|2|0.5|1.56009|
|add_features|100|2|0.5|1.52723|
|hpo|100|2|0.02|0.51981|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png]
(img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.


![model_train_score.png]
(img/model_test_score.png)

## Summary
TODO: Add your explanation
