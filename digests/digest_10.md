# Weekly digest 10

## Joseph

:::{epigraph}
Will we be starting something new next week, or are we still working on project #5 ?
:::

We will move on to something new. 


## Jenna

:::{epigraph}
How many of the files should we be analyzing in the project?
:::

I would say, at least 3-4 for part 1 and then the wikipedia file for 
part 2. Some files have more than one sort of data that may be of interest.
E.g. in the library data there is a column with the number of people 
living in the service area of a library and another column showing the number 
of books a library owns. You should aim for a variety of data - i.e. data 
that has very different meanings.


## Jaimie

:::{epigraph}
What scenarios are best for using regex?
:::

Regex is used to search text for data based on some prescribed patterns. 
For example, you can search for phone numbers, email addresses, urls, 
dollar amounts etc.


## Alan

:::{epigraph}
What is the significance behind analyzing the building numbers from library street addresses? 
Is there an intentional pattern, or is any stand-out number just a coincidence?
:::

The this is an exploratory project. If there is some pattern in data, 
e.g. in building numbers, then it is interesting and one can think what is the 
reason for this. It this pattern is similar to one visible in some other data, 
then it is even more interesting. If there is no pattern, then it is also a bit 
of knowledge. 


## Erica

:::{epigraph}
What’s the difference between using matplotlib directly vs. seaborn for plotting, 
and do you have a preference when plotting?
:::

Seaborn is build using matplotlib. It provides interface more convenient 
for working with pandas dataframes and similar objects. Everything that seaborn does 
can be done directly with matplotlib, but it may take more work. 

You don't need to choose between seaborn and matplotlib, since they can be used together:
you can use seaborn functions to create a plot visualizing some data, and then use matplotlib 
functions to further edit that same plot.


## Nicholas

:::{epigraph}
How much less efficient is Python coding than other languages like C++? Is MATLAB faster?
:::

Such comparisons depend on what you are doing and how you are doing it. Python code not using 
any external libraries will be in general slower than C++ or MATLAB. However, Python libraries
used for scientific computing, machine learning, ai etc. (numpy, scipy, tensorflow ...) can match 
performance of C++ and MATLAB, since these libraries themselves are written in lower level 
languages - C, C++ and Fortran. Python has also a very large ecosystem - if you want to do something, 
there are usually several Python tools that will help with it. MATLAB is more specialized, so it has 
very good tools for some applications and few for others. For example, if you would be trying to 
design and train a neural network, Python would be a better choice than MATLAB - since it provides 
better tools, and the Python code would be internally running code written in C++. 













<br/><br/>