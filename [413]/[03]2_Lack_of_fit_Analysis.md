## F-test (ANOVA)

### Model

SSE = SSPE + SSLF (lack of fit)

> Notice that in each groups, we have same value of predict variables which also implies that the data must contain replications. 
As such, the test is usually only appropriate for data arising from experimental studies.

SSE = \sum_i^k \sum_j^{n_k} ( y_{ij} - \hat{y_i} )^2

SSPE = \sum_i^k \sum_j^{n_k} ( y_{ij} - \mu_i )^2

SSLF = \sum_i^k \sum_j^{n_k} ( \mu_i - \hat{y_i} )^2

> Note that \hat y_{ij} = \hat y_{ij'} for all j,j' in same group.


SS | SSE | SSPE | SSLF
--- | --- | --- |---
df | n-p | n-k | k-p-1

> where k is group and p is the number of predict variable


### Null hypothesis

The null hypothesis is the model is a good fit (no lack of fit!) or can be written as 

μ_k = β_0 + \sum^p_i β_i x_{ki} ( model is a good fit )

> #### Rejecting the null hypothesis in the lack of fit tests only implies that there is scant evidence that the relationship of the group mean μ_k is linear in the x_k and not that there is scant evidence of a relationship between the μk and the ξk.


## Partial Residual Plots
