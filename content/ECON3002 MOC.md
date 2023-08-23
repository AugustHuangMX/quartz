---
title: ECON3002 MOC
---

#Econometrics 

[[What is Econometrics]]

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

# Lecture Notes

## Probability

The probability of an outcome is the proportion of the time it occurs in the long run

*Notation:* For an event $A$ , the number $Pr(A)$ indicates the probability that A will occur.

The $\Omega$ stands for all possible outcomes.


A *discrete* random variable i.e the coin (0 or 1 no others)

A *continuous* random variable i.e the time spent on phone

### Discrete Random Variable

$p(x)=Pr(X=x)$

Probability density function

Cumulative distribution function

Uniform distribution have no modes

##   Expected value and variance of a linear function

The basic knowledge: [[Variance]]

Prove: if $Y=a+bX$ then $Var(Y)=b^2Var(X)$ , why?

Since $Var(X)= E[(x-E(X))^2]$  so that $Var(Y)=E(a+bx-E(a+bx))^2$

$Var(Y)=E[(b(x-\overline x))^2]$ (the right part is the $Var(X)$)

So $Var(Y)=b^2Var(X)$

## [[Standard Deviation]]

The [[Standard Deviation]] of $X$ is denoted as $\sigma _X$, also the $\sqrt {Var(X)}$ 

## Joint and Marginal Distributions

The [[Joint Distribution]] is the probability that two [[Discrete Random Variable]] $X$ and $Y$ simultaneously take on particular values. (say $x$ and $y$)


---



# Reference 

