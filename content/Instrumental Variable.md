We usually name the IV be $Z$.

A valid instrument should satisfy:

- Instrument Relevance: $Cov(X,Z) \neq 0$ (Easy to declare)
- Instrument Exogeneity: $Cov(Z,u) = 0$ (Hard to argue)

We then use [[2-Stage Least Square]] (2SLS) to estimate this question.

1. Regress endogeous regressor 
2. 