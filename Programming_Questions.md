# Programming Questions

_To test your programming skills, employers will ask two things during their data science interview questions: they’ll ask how you would solve programming problems in theory without writing out the code, and then they will also offer whiteboarding exercises for you to code on the spot. For the latter types of questions we will cover a few examples below, but if you’re looking for in-depth practice solving coding challenges, visit Interview Cake. They have an in-browser module for typing code, and they can walk you through tricky problems – all absolutely free._

##### Questions
[General](#general)    
	[Programming Languages](#languages)    
	[Pros & Cons](#procon)    
	[Personal Algorithm](#algo)    
	[Personal Projects](#perspro)    
	[Tidy Data](#tidy)
	[Last Project](#lastpro)
	
<a name='general'>

## 2.1 General

<a name='languages'>

### With which programming languages and environments are you most comfortable working?

I am most comfortable working in R and Python & VBA. I have some experience with statistical software SPSS & SAS, C# & SQL. 

<a name='procon'>

### What are some pros and cons about your favorite statistical software?

R:     
R is a great language for statistical analysis, has a very supportive and active community and is open source. 

However, R does have a steep learning curve - so can be seen as inaccessible. If you want to program anything non-statistical - this language is not ideal and the programs cannot be made executable, you can only save scripts. 

Python:    
Python, as with R, is syntactically easy to write. Again with R there is a supportive community and loads of libraries to make tasks easier and faster. Python is better than R for non-statistical programs and can make executables. 

Python, however, is not as fast as other compiled languages, such as Java or C++.

Both the languages are good for certain scenarios - and there are other languages that may be better for other situations. I usually work on statistical and small programs therefore these languages suit the tasks I perform very well. 

<a name='algo'>

### Tell me about an original algorithm you’ve created.

When working for Pingar International I needed to automatically determine the number of topics for a topic model. In order to do this I retrieved the AIC value for a set range of groups (which could be defined by the user). It was often the case that as more groups were added, AIC continuously got smaller. This meant extracting the lowest AIC value would only select the most number of groups, which did not make practical sense. However, there was often a sharp change in AIC values decreasing, leaving a distinct elbow curve in the distributions of AIC values. Often the elbow of this curve showed a reasonable number of topics in the data. So in order to select this value I used ....

<a name='perspro'>

### Describe a data science project in which you worked with a substantial programming component. What did you learn from that experience?

<a name='tidy'>

### How would you clean a dataset in (insert language here)?

> _Tidy datasets are all alike but every messy dataset is messy in its own way_   
> _Hadley Wickham_

To clean a messy dataset is a difficult process to describe since a messy dataset is uniquely messy. 

I primarily use R, so will answer this question here. However, most of the work will be understanding the structure and assumptions made in the dataset.

Firstly we have to determine the type of data we have. This could be structured files  (e.g. SQL Database, .xlsx files, .csv files etc.) or unstructured (.txt, .rtf etc.). 

If there are multiple data files / tables, we also should determine their relationships and attempt to build a map of how the files are linked. 

To cover all possibilities of cleaning a messy dataset  would be tedious. However, the result of cleaning should be consistent. Depending on how the data will be used after cleaning there are few end results. The two most common being either long or wide format data. 

Long format data will hold measurement columns (often one) representing the measurement values, and a id column, which will show the variables the measurement values represent. Although this dataset is not that easy to determine for a human, it is a common format for visualising data. 

A wide format dataset is more commonly seen by humans, as it holds a row per observation and columns represent variables. This makes data easier to sift through as a human, but make this slightly harder computationally. 

<a name='lastpro'>

### Tell me about the coding you did during your last project?