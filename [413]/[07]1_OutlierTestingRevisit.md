
### Leverage

In [04]2_OutlierTesting.md, we knew that since e_i is depends on x_i also, the estimate variance of e_i should be equal to MSE(1-h_i) where h_i is leverage. It turns out that if the ith data point is far away from the estimate of mean of X \bar{X}, h_i will increase and the variance will decrease. That is, the fitted value will be "forced" close to y_i. 


Knowing that \sum h_i = p (predicted variables). The "average" value of h_i = p/n. Thus, if the leverage of ith data point is more than 2p/n, we might somehow believe it's a outlier!

> Some Methods: Leave one out, CrossValidation


### Cook's distance

Intuitively, an observation will have a large Cook's distance if it either has a large internally studentized residual or it's a high-leverage point.

