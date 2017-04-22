# Modeling Questions

_Data modeling is where a data scientist provides value for a company. Turning data into predictive and actionable information is difficult, talking about it to a potential employer even more so. Practice describing your past experiences building models – what were the techniques used, challenges overcome, and successes achieved in the process? The group of questions below are designed to uncover that information, as well as your formal education of different modeling techniques. If you can’t describe the theory and assumptions associated with a model you’ve used, it won’t leave a good impression._

##### Questions
[Model design](#modeldesign)    
[Data visualisation](#datavis)    
[Personal Algorithm](#algo)    
[Personal Projects](#perspro)    
[Tidy Data](#tidy)
[Last Project](#lastpro)

<a name='modeldesign'>

### Tell me about how you designed the model you created for a past employer or client.

In academia, where I have spent most of my time modelling, I usually being by exploring the data. This is usually though visualisation of the data, but can also be through basic correlation tests and descriptive statistics. 

It is often the case in academia that you are building a model to support a theory, so there is some direction based on previous theory. 

<a name='datavis'>

### What are your favorite data visualization techniques?

Coming from a statistical background, I often rely on basic graph representations such as scatterplots, box-plots and bar charts to represent data. Although not glamorous approaches to data visualisation they are easily understood by most people. I think the most important aspect of data visualisation is for the end user to understand the message it is trying to convey and therefore should be displayed in the simplest form (which is often the most effective) 

### How would you effectively represent data with 5 dimensions? 

It will depend on the data. With the right combination this could be displayed in a single graph. 2 continuous variables in a scatter plot, which are sized, shaped and coloured by 3 other categorical variables. 

This pattern can be replicated for 3 continuous variables in a 3D space, and varying size and colour. 

If all variables were continuous, then this problem becomes more difficult. Less important variables could be split into buckets in order to make categorical variables. Although the first approach I would take would be to make a 5 x 5 matrix of scatterplots in order to understand the relationship between each of the pairs of variables. 

### How is kNN different from k-means clustering?

kNN, or k-nearest neighbors is a classification algorithm, where the k is an integer describing the the number of neighboring data points that influence the classification of a given observation. K-means is a clustering algorithm, where the k is an integer describing the number of clusters to be created from the given data. Both accomplish different tasks.

### How would you create a logistic regression model?


### Have you used a time series model? Do you understand cross-correlations with time lags?


### Explain the 80/20 rule, and tell me about its importance in model validation.


### Explain what precision and recall are. How do they relate to the ROC curve?

Answer. Recall describes what percentage of true positives are described as positive by the model. Precision describes what percent of positive predictions were correct. The ROC curve shows the relationship between model recall and specificity – specificity being a measure of the percent of true negatives being described as negative by the model. Recall, precision, and the ROC are measures used to identify how useful a given classification model is.

### Explain the difference between L1 and L2 regularization methods.

### What is root cause analysis?

### What are hash table collisions?

### What is an exact test?

### In your opinion, which is more important when designing a machine learning model: Model performance? Or model accuracy?

One approach to this question

### What is one way that you would handle an imbalanced dataset that’s being used for prediction? (i.e. vastly more negative classes than positive classes.)

### How would you validate a model you created to generate a predictive model of a quantitative outcome variable using multiple regression?

### I have two models of comparable accuracy and computational performance. Which one should I choose for production and why?

### How do you deal with sparsity?

### Is it better to spend 5 days developing a 90% accurate solution, or 10 days for 100% accuracy?

### What are some situations where a general linear model fails?

### Do you think 50 small decision trees are better than a large one? Why?

### When modifying an algorithm, how do you know that your changes are an improvement over not doing anything?

### Is it better to have too many false positives, or too many false negatives?