---
title: ECON3002 MOC
---

#Econometrics 

[[What is Econometrics]]

[[Lecture Notes for ECON3002]]

---


# Self Textbook notes

## 2.3 Two Random Variables

### Joint and Marginal Distributions

The [[Joint Distribution]] and the [[Marginal Probability Distribution]]

### Conditional Distributions

The distribution of a random variable $Y$ conditional on another random variable $X$ taking on a specific value is called the conditional  distribution of $Y$ given $X$, it is written as $Pr(Y=y|X=x)$

![[截屏2023-08-23 14.42.19.png]]

In the table 2.2, the $Pr(Y=y|X=x)$ could be expressed that what is the prob of a long commute if I *already know* it is raining?

That is  asking  $Pr(Y=0|X=0)$ , and it is equals to $0.15/0.30=50\%$ 

$$
Pr(Y=y|X=x)=\frac{Pr(X=x,Y=y)}{Pr(X=x)}
$$

> Remember the second part is the event that you already know.

### The law of iterated expectations

[[The Law of Iterated Expectations]]  is the mean of Y is the weighted average of the conditional expectation of $Y$ given X, weighted by the prob distribution of $X$ 
$$
E(Y)=\sum^l _{i=1}E(Y|X=x_i)Pr (X=x_i)
$$
So that the expectation of $Y$ is the expectation of the conditional expectation of $Y$ given $X$,

$$
E(Y)=E[E(Y|X)]
$$

And this is the core of  [[The Law of Iterated Expectations]]

### The Independence

[[Independence]] Two random  variables $X$ and $Y$ are said to be *independently distributed* if 

$$
Pr(Y=y|X=x)= Pr(Y=y)
$$

Since the conditional distribution implies that 

$$
Pr(Y=y|X=x)=\frac{Pr(X=x,Y=y)}{Pr(X=x)}
$$

That is 

$$
Pr(X=x,Y=y)=Pr(X=x)Pr(Y=y)
$$

Then the $X$ and $Y$ are independent.




---



# Reference 

