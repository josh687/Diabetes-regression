The objective of this dataset is to build a predictive model for diagnosing diabetes in female patients who are at least 21 years old and of Pima Indian heritage. The model should predict whether a patient has diabetes (Outcome = 1) or does not have diabetes (Outcome = 0) based on several diagnostic measurements, including glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

In this report, we will approach the method of modelling in four sections.

The first step is to build the full logistic regression model by incorporating all variables.
We then perform a backward selection to select variables with a high impact on the model and build our reduced model.
Further modelling methods then include Lasso and Ridge regression.
We then compared the result of our model using the testing dataset to find the accuracy, sensitivity, auc performance values, and specificity of a logistic regression model based on our training data.


Best model accuract: Lasso Regression.
Training Accuracy - 96.4%
Validation Accuracy - 93.3%
