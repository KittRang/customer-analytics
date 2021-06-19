Campaign Response Model

We started out with the basic logistics regression from SkitLearn

<p align="center"><img src="images/log_regression_ori.jpg" height ="250"></p>

To improve upon the model, I choose to use GridSearch method rather than feature engineering. Doing so by calling GridSearchCV.

<p align="center"><img src="images/log_regression_grid.jpg" height ="250"></p>

The f1score on the weighted average and the accuracy were <b>Insignificantly</b> increased. 1%.
  
<p align="center"><img src="images/log_regression_result.jpg" height ="250"></p>
  
This is true for all the undersample,oversampled version of logistic regression, insignificant increased.
  
To produce better results, we then turn onto the XGBoost model
