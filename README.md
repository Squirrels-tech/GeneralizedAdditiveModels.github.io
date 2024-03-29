# Generalized Additive Models
### What is GAM?
Generalized additive models were originally invented by Trevor Hastie and Robert Tibshirani in 1986. The GAM framework is based on an appealing and simple mental model:

* Relationships between the individual predictors and the dependent variable follow smooth patterns that can be linear or nonlinear.
* We can estimate these smooth relationships simultaneously and then predict g(E(Y))) by simply adding them up.

Mathematically speaking, GAM is an additive modeling technique where the impact of the predictive variables is captured through smooth functions which—depending on the underlying patterns in the data—can be nonlinear

```math
\left(g(E(Y)))=α+s1(x1)+⋯+sp(xp\right)
```
where Y is the dependent variable (i.e., what we are trying to predict), E(Y) denotes the expected value, and g(Y) denotes the link function that links the expected value to the predictor variables x1,…,xp.
