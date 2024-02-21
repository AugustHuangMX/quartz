What do we learn from this chart about the presence of either adverse selection or moral hazard in the market for medical insurance? 


---

[[HealthCare->Seminar1]]


---

# Papers

## Paper 1: Finkelstein et al (2012)

Question: Do people incur higher health expenditures if they have medical insurance?

Problem is that we could not just compare the health spending across those with and without insurance. The groups are fundamentally different. That is, the less healthy people more likely 

1. To be insured.
2. Spend more on health.

Another reason is related to [[Moral Hazard]]. We consider the **Insurance Policy** will lead to **More medical spending**. And due to [[Adverse Selection]], The things become opposite.

And people himself could have [[Endogeneity Issue]].

![[截屏2024-02-20 19.15.44.png|400]]

[[Econometrics]] thinking, suppose we decided to just compare people with and without insurance, like a [[Simple Linear Regression]]. "Randomized control trial" designs: 

$HealthSpend_{i}= \beta_{0}+\beta_{1}Insurance_{i}+\beta_{2}X_{i}+u_{i}$

So that if unhealthy people more likely to have insurance, the bias $\beta_{1}$ would increase. ($X_i$ stands for  other possible effects: like age, gender, etc.)

The empirical approach concludes a lottery: 90,000 people signed up for 10,000 slots. This breaks the [[Endogeneity Issue]] among these people.

**Question**: why is it different from difference-in-difference (DID)?

With Randomized control trial (RCT), we don't need such strong assumptions. The significance difference in DiD is that we have to *assume the trend in the treatment and control group would have been the same in absence of treatment*.

*It simulates a randomized control trial*. 

The **idea** is compare [[HealthCare]] utilisation of treatment group against the control group. (so that people are considered as the same, excluding whether he is chosen.)

**Potential Problem**: not everyone selected by the lottery goes on to get insurance (in fact, only 60% who won applied to this)

## Analysis 1: Intention to treat 

$y = \beta_{0}+\beta_{i}Lottery +X|beta_{2}+V\beta_{3}+\epsilon$

$Lottery = 1$ if won the lottery, 0 otherwise.

We **Only** focus on $\beta_1$

## Analysis 2: [[Two Stage Least Squares]]


## Main Findings:

Winning lottery => More likely to be insured, higher [[HealthCare]]  utilization, better health, lower medical bills after around 1 year.


## Paper 2: Olivella and and Vera-Hernandez (2013)



