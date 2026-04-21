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

This is an exploratory project. If there is some pattern in data, 
e.g. in building numbers, then it is interesting and one can think what is the 
reason for this. It this pattern is similar to one visible in some other data, 
then it is even more interesting. If there is no pattern, then it is also a bit 
of new knowledge. 


## Erica

:::{epigraph}
What’s the difference between using matplotlib directly vs. seaborn for plotting, 
and do you have a preference when plotting?
:::

Seaborn is build on top of matplotlib. It provides an interface convenient 
for working with pandas dataframes and similar objects. Everything that seaborn does 
can be done directly with matplotlib, but it may take more work. 

You don't need to choose between seaborn and matplotlib, since they can be used together.
You can use seaborn functions to create a plot visualizing some data, and then use matplotlib 
functions to further edit that plot.


## Nicholas

:::{epigraph}
How much less efficient is Python coding than other languages like C++? Is MATLAB faster?
:::

Such comparisons depend on what you are doing and how you are doing it. Python code not using 
any external libraries will be in general slower than C++ or MATLAB. However, Python libraries
used for scientific computing, machine learning, AI etc. (numpy, scipy, tensorflow ...) can match 
performance of C++ and MATLAB, since these libraries themselves are written in lower level 
languages - C, C++ and Fortran. Python has also a very large ecosystem - if you want to do something, 
there are usually several Python tools that will help with it. MATLAB is more specialized, so it has 
very good tools for some applications and few for others. For example, if you would like to 
design and train a neural network, Python will be a better choice than MATLAB, since it provides 
better tools. Doing this with C++ would require more coding and probably not that much performance 
gain, since Python code would internally run code written in C++ anyway. 


## Ryan

:::{epigraph}
In the upcoming project due this week, how many of the csv files do you recommend we use? 
Is 3 a good number to show?
:::

I would say, at least 3-4 for part 1 and then the wikipedia file for 
part 2. Some files have more than one sort of data that may be of interest.
E.g. in the library data there is a column with the number of people 
living in the service area of a library and another column showing the number 
of books a library owns. You should aim for a variety of data - i.e. data 
that has very different meanings.



## Muhammed

:::{epigraph}
When will the final project be due?
:::

I am not sure yet, we will see how much time it will take to get through 
the material for it.



## Chloe

:::{epigraph}
When is our last day of class?
:::

According to the [UB calendar](https://www.buffalo.edu/registrar/calendars/current-academic-calendar.html)
classes end on Wednesday, May 6. Thus, the last class meeting will be on Tuesday, May 5. 



## Alyssa

:::{epigraph}
When is the last project likely going to be due?
:::

I am not sure yet, we will see how much time it will take to get through 
the material for it.



## Pierce

:::{epigraph}
When will our last quiz be?
:::

I have not decided yet. 



## Brianna

:::{epigraph}
What is the difference between Jupyter Notebook and Python Script?
:::

Python script is just code written in Python. Jupyter Notebook is 
software that can be used to write, edit, and execute Python scripts. 
Python scripts can be written and run without using Jupyter Notebook - there are many tools for that.


## Henry

:::{epigraph}
How does re.findall() decide what to return when a regular expression contains groups?
:::

If there are no groups in the regular expression, `re.findall()` returns a list with matches of 
the whole pattern. If the regular expression contains groups, `re.findall()` will match
the whole pattern, but it will return only parts of the pattern that correspond to the groups.


## Rodrigo

:::{epigraph}
When using the "?" in regular expressions, what exactly does "optional" mean? 
Is it a random chance that the preceding character is included? If so, how is that helpful here?
:::

Regular expressions are deterministic - there is nothing random about results they produce.
The meaning of `?` can be described as "match the previous character 0 or 1 times". For example, 
the regular expression `r"ab?c"` will match both "ac" (since "b" appears 0 times) and "abc" 
(since "b" appears one time). It will not match "abbc" though.  



## Vidhi

:::{epigraph}
Will we have a quiz the last week of classes?
:::

I have not decided on this yet. 


## Shane

:::{epigraph}
Have all of the projects been weighted the same or are some of them more or less than one another?
:::

I mentioned in the syllabus that projects may have different weights, since I though about assigning 
some shorter less-weighted projects, but actually all projects will be wighted the same.


## Bernice

:::{epigraph}
How many more project reports do we have left in this semester?
:::

Altogether there will be 6 projects. 


## Dixith

:::{epigraph}
How can you tell faster what regular expression will match just by looking at it?
:::

It just takes some practice. 


## Berkley

:::{epigraph}
For the next project, how many files should we be aiming to use? Additionally, 
is there a certain number of graphs we should include in the next project?
:::

I would say, at least 3-4 files for part 1 and then the wikipedia file for 
part 2. Some files have more than one sort of data that may be of interest.
E.g. in the library data there is a column with the number of people 
living in the service area of a library and another column showing the number 
of books a library owns. You should aim for a variety of data - i.e. data 
that has very different meanings.

As for plots, there should be a bar plot showing the distribution of first and 
last digits in each data source you are analyzing. There may be some other plots
if you want to compare data coming from different sources. Aside from that - 
it depends on how you choose to structure your report. 


## Andrew

:::{epigraph}
Is the regex syntax used by Python unique to Python, or is it shared by other 
programming language(s) with regex?
:::

There are two POSIX standards for regular expressions: basic and extended.
Extended regular expressions add some extra functionality to basic ones, 
for example `+` and `?` have no special meaning in basic regular expressions.  
Programming languages and other tools (e.g. `grep`) in general adhere to one of 
these standards.  Python `re` library uses extended regular expressions, `grep` 
by default uses basic ones, but one can use `grep -E` to switch to extended. 


## Daniel

:::{epigraph}
What are regular expressions in MTH 337?
:::

Regular expressions are patterns specifying matches in text files. I talked about them
last Thursday. 


## Jarrod

:::{epigraph}
I’m still a little confused about when to use patterns like `".*"` versus something more specific. 
I also want to better understand greedy vs non-greedy matching and when it matters?
:::

`.` matches any character except the new line character, `*` means "repeat 0 or more times, as many 
times as possible". Thus, `.*` will match a whole line of text. This may not be very useful on its own, 
but it can be used as a part of a pattern. For example, `r".*abc.*"` will match any line that contains 
"abc". 

Regex matches are by default greedy, i.e. they match as large part of a string as possible. 
I did not talk in class about non-greedy matches (where matches are as short as possible), but you can
specify them by using `*?` and `+?`. For example, `re.findall(r"a.*b", "abcbd")` will return `["abcb"]`
while `re.findall(r"\b.*?b", "abcbdb")` will return `["ab"]`. 



## Christian

:::{epigraph}
How can I better interpret the results produced by my code beyond just verifying that it runs correctly?
:::

The goal of every project is to investigate some topic, describe the investigation process 
and results is produces. Writing correct code is only a part of this. For example, the project 
on first/last digits needs to include code to produce frequencies of digits appearing data, but 
it also must describe observations regarding these frequencies, comparisons between frequencies
coming from different sources etc. 













































<br/><br/>