## Remedial Measures

How to improve the model if the fitted linear regression model is not appropriate for the given data?

### Overview 

- Transformation of the response and/or predictor variables (BOX-COX, GLS)
- Embedding into high dimensional space (Kernal)
- Feature Selection (Lasso Regression, AIC, BIC )
- Adding additional predictor variables, interactions among predictor variables, or transformation of existing predictor variables.
- Estimation using weighted least squares if the variance of the error term are not constant.
- Perform robust regression/estimation if there are outliers in the data.

#### Box-Cox Transformation ( transform on response variable y )

A way to transform non-normal response variables into a normal shape. If the data isn’t normal, applying a Box-Cox can help getting best lambda where y^lambda is normal. 

[ http://www.statisticshowto.com/box-cox-transformation/ ]

![alt text](https://raw.githubusercontent.com/LennyFan/Learning---Statistics/%5B413%5D/Course_Content/%5B03%5DBox-Cox_example1.png)
