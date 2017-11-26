## Residual Test
- Constancy of Variance (absolute value, Brown-Forsythe test)
- Outlier 
- Correlation 
- normality (QQ)

## Constancy of Variance
- Brown-Forsythe test:

Partition observations x_i into several groups, corresponding to observations with different values. ( basic ANOVA test !! ) 
Comparing the variance between the group and the vriance withing the group. If we only partition into two groups we can use t-test. 

> [ check https://github.com/LennyFan/Learning---Statistics/blob/master/%5B430%5DIntro_to_statistics_outline.ipynb to get more detail of ANOVA and two-sample test]


## Normality
- Q-Q plot
- Shapiro-Wilks test
- Anderson-Darhling test

> Tests of normality is not particularly useful in p-value testing. It does not indicate what action to take. That is, strong evidence of non-normality is not the same as evidence of strong non-normality.
>
>  In general, mild deviations from non-normality can be detected for large data sets. However, there would be no reason to abandon least squares in this case as the deviation is mild and the effects of non-normality are mitigated by the large sample size. Should combining with other diagnostics.


## Correlation
- Wald-Wolfowitz test ( runs test )

[ check https://github.com/johnnychiuchiu/Machine-Learning/blob/master/LinearRegression/linearRegressionModelBuilding.pdf Run's test]

