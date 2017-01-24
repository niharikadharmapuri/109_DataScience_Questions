# Statistical Questions

##### Questions
[Central Limit Theorem](#CLT)  
[Sampling](#Sampling)  
[Type I & Type II error](#error)  
[Linear regression](#regression)  
[Linear regression assumptions](#regression_assumptions)  
[Statistical Interaction](#interaction)  
[Selection bias](#selection_bias)  
[Non-Gaussian data](#nongaussian)  
[Binomial formula](#binomial)

_Statistical computing is the process through which data scientists take raw data and create predictions and models backed by the data. Without an advanced knowledge of statistics it is difficult to succeed as a data scientist – accordingly it is likely a good interviewer will try to probe your understanding of the subject matter with statistics-oriented data science interview questions. Be prepared to answer some fundamental statistics questions as part of your data science interview._

<a name='CLT'>
### What is the Central Limit Theorem and why is it important? 

The central limit therom dictates that when you repeatedly calculate the mean from different samples of a population, the distribution of those means will be normal. The larger the size of each sample, the faster the resulting distribution will converge to normal. This is true regardless of the distribution of the population. 

The central limit theorem is important because it allows the utilisation of a suite of statistical tests that assume a normal distribution. 

<a name='Sampling'>
### What is sampling? How many sampling methods do you know?

Sampling is a way of approximating the distribution of a population without having to perform a census on that population. 

#### Methods of sampling

_Simple Random sampling_
  
  Every point has the same probability of selection as any other point. Minimizing bias and simplifies analyses. However sometimes the randomness can be a hindrance and provide  biased samples by chance. 
  
_Systematic Sampling_ 
  
  Systematic sampling takes an ordered set of data and samples at regular intervals from a randomised starting point. For example, sampling every third data point. 

_Stratified Sampling_

  When a population has pre-existing categories or 'strata' then these categories can be used as an independent sub-population. We can apply differenting sampling strategies to each category. This also allows statistical inference at multiple levels of the data. 

_Probability-proportional-to-size sampling_

PPS sampling can be used as an alternative to stratified sampling described above. Instead of sampling from strata, the probability of a data point being selected is relative to the frequency of the strata that data point belongs to in the population. 

_Cluster sampling_

Cluster sampling takes a cluster of data points and samples heavily from within that cluster. Often clusters are within geographical boundaries which offers a cost effective alternative to simple random sampling. 

Because of the oversampling within a cluster, this sampling style often requires a higher sampling size to achieve similar levels of accuracy as a simple random sample. 

_Quota sampling_

This is a non-probability based sampling technique. Here there may be some criteria (or a quota) imposed by the researcher on what the end sample may look like. For example: the sample should contain 50 males and 60 females. Because data points are chosen deliberately, this makes quota sampling a non-random method - and is often avoided because of this. 

For more examples of sampling methods, [check out the Wikipedia page.](https://en.wikipedia.org/wiki/Sampling_(statistics)#Sampling_methods)

<a name='error'>
## What is the difference between Type I vs Type II error?

Type I errors happen when we reject a true null hypothesis. Also known as false positives. This type of error is often controlled by the 'level of significance' and alpha test. For example: a type I error would occur when we accept a drug has an effect on a disease, but in reality it did not.  

Type II errors happen when we fail to reject a false null hypothesis. Also known as false negatives. For example: A type II error would occur if we accepted that a drug had no effect on a disease, but in reality it did.

<a name='regression'>
## What is linear regression? What do the terms P-value, coefficient, R-Squared value mean? What is the significance of each of these components?

Linear regression is used to model the relationship between a variable a researcher is intersted in (response) and variables that may explain the variation in that variable (predictors). 

The result of a regression will give you a coefficient for each predictor, a corresponding p-value and a R^2 value for the complete model.

A coefficient often represents the change in the response for a one-unit change in the predictor - assuming all other predictors are held constant. If the predictor is categorical, then the value represents the change in the response for one category, relative to a reference category. 

Each coefficient will have a p-value. The p-value is the result of a test asking 'is the coefficient significantly different from zero'. If the p-value is below our threshold, then we believe the predictor is significantly different from zero and therefore has a significant effect on the response. The threshold is commonly 0.05. 

R^2 differs from the coefficient and p-value in that it represents the goodness of fit of the model as a whole, rather than individual predictors. R^2 values range from 0 - 1, where a value of 1 means the model perfectly fits the data. It provides a value which shows how much of the total variation within the data is explained by the model. 

<a name='regression_assumptions'>
## What are the assumptions required for linear regression?

<a name='interaction'>
## What is a statistical interaction?

<a name='selection_bias'>
## What is selection bias?

<a name='nongaussian'>
## What is an example of a dataset with a non-Gaussian distribution?

<a name='binomial'>
## What is the Binomial Probability Formula?