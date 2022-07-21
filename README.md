<div id="top"></div>

<br />
<div align="center">

<h2 align="center">Diabetes Diagnosis
</h2>
<p size=large> Using Data Mining and Classification to diagnose patients with diabetes</p>
<div align="center">
</div>
<br>
</div>

## Overview
We have health related data of over 70k patients in form of a DataFrame containing 22 columns. In this project we want to use XGBoost to classify and diagnose patients with diabetes.

First we need to preprocess our data by handling of missing values, renaming columns, normalizing and scaling values, conversion of categorical values, and separating features from labels of our data. 

Then we create our classifier model and train it with specific parameters. At the end of the training we report confusion matrix, precision and recall for train and test data.

Further we fine-tune our model on different variation of parameter values to find hyperparameters of the most accurate model.

Finally we visualize the change in model's performance by plotting the change in hyperparameters `learning_rate`, `max_depth`, `n_estimators` and `colsample_bytree` and their effect on values of `mean_fit_time` and `meant_test_score`.

 > For detailed explanation (in Persian) of this project please refer to the notebook itself.