## Bonferroni Correction

#### Idea

The basic idea is that the individual confidence intervals doesn't imply the joint confidence intervals. Thefore, using the preperty of union of probability, we can thus give a very rough lower/upper bound to our confidence intervals. Since β1 and β0 are both functions of y_i, these two parameters are not independent. Therefore, the true confidence interval might be larger than Bonferroni Correction bound.

For example, let β1 and β0 be two parameters. Then a joint confidence region of size at least 1 − α for (β1, β0) can be obtained by combining a confidence interval of size 1 − α/2 for β0 with another confidence interval of size 1 − α/2 for β1. We can use Bonferroni Correction when we want to compute

- (joint) significance level for a family of hypotheses tests

- (joint) confidence region for a family of confidence intervals

> #### It provides a very conservative upper/lower bound. Similarly, if there is a large number of joint confidence intervals, then the individual confidence intervals are (much) larger than usual.

#### Methods
- Benjamini-Hochberg procedure
- Benjamini-Hochberg-Yekutieli procedure



## Benjamini-Hochberg procedure

[ to be filled ]

reference [ https://rpubs.com/aaronsc32/simultaneous-confidence-intervals ]



## Conclusion

> ### The Bonferroni correction procedure is thus one way to control the number of false discoveries. More (or maybe less) precisely, Bonferroni correction control at a significance level α attempts to guarantee that P[a > 0] ≤ α. In contrast, the Benjamini-Hochberg (BH) procedure aims to control the false discovery rate a/R. Roughly speaking, the BH procedure attempts to guarantee that E[a/R] ≤ α.



## Working-Hotelling estimate

[ to be filled ]
