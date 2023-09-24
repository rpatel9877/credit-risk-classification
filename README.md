# credit-risk-classification
Overview
- The data was split into training and testing sets. The training data was used to create the first Logistic Regression Model. This model was applied onto the testing data. The model's purpose was to determine whether a loan was a high or low-risk.
- The data was then resampled using RandomOverSampler. The resampled data was then used to create the second Logistic Regression Model. This model also had the same goal of determining if a loan was high or low-risk.

Results
 Model 1:
-- 93% Precision (Low-Risk: 100%, High-Risk: 87%)
-- 94% Accuracy
-- 95% Recall

- Model 2:
-- 93% Precision (Low-Risk: 100%, High-Risk: 87%)
-- 100% Accuracy
-- 100% Recall

Summary
- Model 2 had less false prediction of the data and would be the better model to use due to it's higher accuracy and recall.
