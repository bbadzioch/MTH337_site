# Weekly digest 8

## Alan

:::{epigraph}
Could you explain how enumerate works?
:::

I explained it in class on Thursday. If `mylist` is a list then  `enumerate(mylist)` 
returns an iterable that produces tuples `(i, mylist[i])` where `i`=0, 1, 2,...


## Nicholas

:::{epigraph}
In real world analysis, what are the actual ways authorship is determined? I am interested in how 
a program manages to differentiate between tone and turn of phrase to understand who's writing the text.
:::

Comparison of word frequencies is one of the most common methods, but you can train artificial neural 
networks to pick up more delicate stylistic features of the type you mentioned. 


## Josh

:::{epigraph}
Is matplotlib the only graphing library? Are there other libraries that could be better for representing 
different types of visuals? Are we able to use other libraries in our project reports?
:::


There are many Python plotting libraries, e.g. bokeh, plotly, altair, seaborn. I don't think I will have 
time to introduce them in this course, but if you want to use one of them in a report and know how to do it, 
feel free to use it.

## Joseph

:::{epigraph}
I noticed on Week 10 material that there was a list and dictionary about the solar system. 
Is that the next topic for this course?
:::

This is sample data for working with pandas library. I will talk about it next.


## Alyssa

:::{epigraph}
Are there any specific videos or websites I can review online to help me learn more and understand better.
:::

There are a lot Python-related resources online. If there is something in particular 
that you are unsure about, do a web search, and you will usually get many useful
results. I am available to answer any questions too. 


## Pierce

:::{epigraph}
How long will we have to complete the next couple of projects?
:::

Project 4 is due April 10, project 5 probably two weeks later.



## Jaimie

:::{epigraph}
After the text attribution project, what will our next project be about? 
:::

Analysis of numerical data.



## Erica

:::{epigraph}
Why do we use enumerate() when looping through training or test texts?
:::

This helps with iterating over training and test texts, while at the same 
time keeping track of indices that indicate at which spot of a numpy array 
results of comparisons of these texts should be stored. 



## Janna

:::{epigraph}
How many more projects will we be doing this semester?
:::

There should be time for 6 projects altogether.


## Chloe

:::{epigraph}
How many more projects do we have?
:::

There should be time for 6 projects altogether.


## Rodrigo

:::{epigraph}
What was the reason for combining all training texts before checking word 
frequency and later comparing them to test texts?
:::

Training texts should be combined only to find what are the most common words 
in all these texts. Frequencies of these words should be computed for each training 
text and test text individually - without combining these texts. 



## Ryan

:::{epigraph}
In the project, how many texts do you think is adequate when testing to look 
at different lengths of words most common words etc?
:::


You are expected to use all texts. There are 5 training texts that give samples of 
writing by 5 different authors. You are supposed to compare these training tests 
to all test texts using various methods and check in how many cases the closes training 
texts to a given test text is the one written by the same author.


## Vidhi

:::{epigraph}
What is the quiz on?
:::

Counter, enumerate and list sorting.


## Daniel

:::{epigraph}
How many more projects do we have?
:::

There should be time for 6 projects altogether.



## Muhammed

:::{epigraph}
Is it possible to get some guidance on the projects during office hours before 
submitting it such as areas that I can improve, any advice etc.
:::

Yes, of course. Just come over. 


## Andrew

:::{epigraph}
What will be the topic of the next project?
:::

We will work on analyzing some numerical data. 



## Briana

:::{epigraph}
How many projects are left do you think are left and are there any extra credit opportunities?
:::


There should be time for 6 projects altogether. I may assign some extra credit tasks, but I have been 
actually giving extra credit on every project so far. If a report includes something that goes beyond 
expectations, it may get an A+ grade. 




## Berkley

:::{epigraph}
How many authors will we need to detect (from of a piece of their writing) for the project?
:::

All training and test texts come from 5 different authors, so this is how many we are trying to 
identify in this project. 



## Bernice

:::{epigraph}
How many more project reports do we have left in the semester?
:::

There should be time for 6 projects altogether.



## Henry

:::{epigraph}
What are the best practices for organizing Python code so it stays clean and 
easy to understand as programs get more complex?
:::

You can organize your code using functions and classes (which we have not covered 
in this course so far). For larger programs, the code should be also split into 
several files, reflecting logical structure of the program.




















<br/><br/>