## Estimator:
> Assume X,Y are two normal random variables. Knowning that the joint distribution is bivariate normal. Then using MLE to estimate the coefficient wil be Sxy/sqrt(Sxx*Syy). It turns out that the distribution of the estimatetor of coefficient is complex. Fisher suggested a transformation of coefficient which is asymtotically standard normal when n is large (CLT).

## Comapre to Beta 1 (slope):
The coefficient of correlation is a measure of the strength of the linear association between Y and X. 
It will always be the same sign as the slope estimatetor Beta1. However, it has several advantage different from Beta1.

- If we are not sure about the predicted and responsed variable ( not sure about whether y depends on x or x depends on y ), then we would like to use the correlation to analyze the relationship between them. 

- Beta1 ( slope ) depends on the unit of x and y, but coefficinnt doesn't

- The range of coefficient is [-1,1]

- * it is only useful to measure the linear association between x an y by the defination of correlation. Therefore, not useful to measur the nonlinear association!)
>> < Note > : Independent -> Uncorrelated.    Uncorrelated(linear uncorrelated) doesn't imply independent




## Spearman Rank Correlation v.s Pearson Correlation
> The Spearman correlation coefficient is often described as being "nonparametric". This can have two meanings: First, a perfect Spearman correlation results when X and Y are related by any monotonic function. Contrast this with the Pearson correlation, which only gives a perfect value when X and Y are related by a linear function. The other sense in which the Spearman correlation is nonparametric in that its exact sampling distribution can be obtained without requiring knowledge (i.e., knowing the parameters) of the joint probability distribution of X and Y. [ https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient ]
