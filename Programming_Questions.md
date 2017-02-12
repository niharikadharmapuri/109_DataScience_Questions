# Statistical Questions

__To test your programming skills, employers will ask two things during their data science interview questions: they’ll ask how you would solve programming problems in theory without writing out the code, and then they will also offer whiteboarding exercises for you to code on the spot. For the latter types of questions we will cover a few examples below, but if you’re looking for in-depth practice solving coding challenges, visit Interview Cake. They have an in-browser module for typing code, and they can walk you through tricky problems – all absolutely free.__

##### Questions
[General](#general)    
	[Programming Languages](#languages)
	[Pros & Cons](#procon)
	[Personal Algorithm](#algo)
	
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

<a name='CLT'>
### Describe a data science project in which you worked with a substantial programming component. What did you learn from that experience?

<a name='CLT'>
### Do you contribute to any open source projects?

<a name='CLT'>
### How would you clean a dataset in (insert language here)?

> Tidy datasets are all alike but every messy dataset is messy in its own way
> - Hadley Wickham

I primarily use R, so will answer this question here. However, most of the work will be manual - in order to understand the structure and assumptions made in the dataset. It is difficult to determine the exact process of cleaning the dataset - because as the quote above suggests, unclean data sets are all unique. 

Firstly we have to determine the type of data we have. This could be structured files  (e.g. SQL Database, .xlsx files, .csv files etc.) or unstructured (.txt, .rtf etc.). 

If there are multiple data files / tables, we also should determine their relationships and attempt to build a map of how the files are linked. 

To cover all the possibilities from the examples above would be tedious - so we will make the assumption that we have an unclean .csv file of data, with one row per observation (which seems like a reasonable assumption) and a large number of rows. 

Reading in and viewing the first number rows in R is easily performed with the `read.csv` and `head` or `tail` functions. 

<a name='CLT'>
### Tell me about the coding you did during your last project?