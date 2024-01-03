# Project Name

Up Grad Assignment - Advanced Regression

## Problem Statement

Aiming to make a strategic entry into the Australian real estate market, Surprise Housing, a prominent US-based housing company, leverages data analytics to make informed investment decisions. To enhance their predictive capabilities and assess the potential profitability of prospective properties, the company has meticulously gathered a dataset from housing sales in Australia, encapsulated in the accompanying CSV file.

In pursuit of identifying lucrative opportunities, we are tasked with constructing a robust regression model employing regularization techniques. This model will play a pivotal role in predicting the true value of prospective properties, empowering Surprise Housing to make sound investment decisions and capitalize on the Australian real estate market. The application of regularization ensures the model's stability and prevents overfitting, providing a reliable foundation for strategic property acquisitions.

For ridge regression, the optimal alpha value is determined to be 10, while for lasso regression, it stands at
When doubling the alpha for both regressions, there is a noticeable impact on the rsquare values. For ridge regression, the rsquare decreases for the training set and remains constant for the test set. On the other hand, in lasso regression, both the train and test set rsquare values decrease.

Post-adjustment, the most influential predictor variables are as follows:
OverallQual
TotalBsmtSF
Neighborhood
Exterior1st
LotArea
CentralAir

## Outcome

Ensuring a model's robustness and generalizability involves achieving a high r-square value, indicating a good fit. While the model may not precisely produce a linear line, it closely aligns with actual values, avoiding overfitting and ensuring accuracy in predictions.
