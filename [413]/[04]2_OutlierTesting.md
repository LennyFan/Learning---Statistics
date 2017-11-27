
### standardization and studentization

#### Semistudentized residuals 

> e_i ~ N(0,sigma^2)

Hence, we can test outlier by the formula below follow the standard normal

> e_i / sigma ~ N(0,1)

#### standardization ( internally studentized residual )

However, since we don't know the real sigma, beta0, and beta1, the variance of residuals depends on X also. Therfore, the variance of e_i should be

> V[e_i] = sigma^2 ( 1 - 1/n - (x_i - \bar(x))^2/Sxx ) =  sigma^2 ( 1 - h_i ) 

where h_i is th leverage of the i-th data point. Then by CLT

> e_i / \sqrt{ MSE (1-h_i) }  

> #### However the single e_i and MSE are not independent, therefore the function above doesn't follow the t-distribution!!! The procedure is then to delete the ith observation, fit the regression function to the remaining n−1 observations, and get new ŷ_i by x_i. ( Same idea as cross validation )

#### studentization ( externally studentized residual )
