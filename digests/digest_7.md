# Weekly digest 7

## Alyssa

:::{epigraph}
Where would we go to find our mid-semester grades for this class?
:::

I am provide you  with letter grades for project reports and quiz scores. 
If you would like to talk about your final grade, we can meet during my office 
hours or at some other time.  


## Jaimie

:::{epigraph}
Is there a way we can view our overall grade for this class? 
:::

You can estimate it on your own. The final grade is based on 3 components: 
project reports (75%), quizzes (15%), weekly digests (10%). Each component 
will give you a letter grade. These letter grades will be converted to grade points
(A+ = 4.33, A = 4.0, A- = 3.67 etc.), then I will compute their weighted average 
using the above weights, and convert the resulting number back to a letter grade. 

The project reports component is the average of letter grades from all projects 
(dropping the lowest project grade). 

To get the quiz component, compute the sum of all quiz scores (dropping the lowest score). The score 
of 80% or above the maximum possible score will give you an A for quizzes. 70% or above will give a B, 
60% or above a C, 50% or above a D. I may adjust these cutoffs, depending on the quiz average scores, 
but they will not go up. 

The third grade component is for weekly digests. Here only the number of submitted digests counts, 
not what you actually wrote in them. It you missed no more than one digest, your digest grade is an A. 
If you missed 2, it is a B etc. 


## Erica

:::{epigraph}
How could we modify the program to find the most frequent words in the text instead of just counting all occurrences?
:::

You need to convert the dictionary into a list of tuples and the sort the list. 
This was a part of class last Thursday.


## Ryan

:::{epigraph}
Will there be a quick turnaround on the new upcoming project because the epidemic project took us a while?
:::

Project 4 will be due on Friday, April 10.


## Chloe

:::{epigraph}
When is our next project due
:::

Project 4 will be due on Friday, April 10.


## Jenna

:::{epigraph}
When will the next project be due?
:::

Project 4 will be due on Friday, April 10.


## Jenna

:::{epigraph}
When will the next project be due?
:::

Project 4 will be due on Friday, April 10.


## Muhammed

:::{epigraph}
How will the final grade be calculated for the projects section. i.e. let's say I get an A- as overall projects letter grade, then out of 75% how much percentage will I be getting?
:::

Convert the letter grade to grade points: A+ is 4.33, A is 4.0, A- is 3.67 etc. Then take 75% of this. 
Letter grades for quizzes and weekly digests will be weighted in the same way. 



## Shane

:::{epigraph}
Will there be a grade calculator or anything like that for us to get a better idea of where we are in the class.
:::

I guess at this point, you could use Python to write one on your own. 
See my response to Jaimie for explanations how it should work.



## Henry

:::{epigraph}
When should we use a set instead of a list in real world applications?
:::

Sets are useful for working with collections of objects where each object can appear only once
and there is no ordering involved. A collection of all unique words in a book, a collection 
of all links on a webpage etc. could be represented by sets. 


## Rodrigo

:::{epigraph}
Is it possible to do cryptography in Python? If so, will we learn some encryption/decryption methods using code?
:::

Python can be used for cryptography and there are several Python libraries with tools for that. 
There is not much time left this semester, but I will see if I can include something related to this. 


## Vidhi

:::{epigraph}
How do you keep improving regarding what you learn ? 
:::

This mostly boils down to practice.



## Jarrod

:::{epigraph}
When working with text processing, is there a more efficient or built-in way to clean and analyze large amounts of 
text instead of looping through every character manually? how do these basic techniques scale when working with very 
large datasets or real-world applications?
:::

It depends on what you want to do, but there are many text processing tools that can be helpful. 
For example, I plan to talk soon about regular expressions, which are very useful in many cases. 

## Andrew

:::{epigraph}
How are Python strings stored in memory?
:::

Strictly speaking, it depends on the Python interpreter. The standard interpreter, the one 
we are using, is CPython, which is written in C. It implements strings as C-arrays of characters 
of an explicit length. Internally, this means that a CPython string is a structure in C, that 
stores an array of characters, the length of the string and some additional data. 
This means that you could modify strings in place, but it would require tweaking CPython (or using 
Python C-API). This is doable, since the source code is freely available.


## Bernice

:::{epigraph}
What is a real-world example of using dictionaries and requests in python?
:::

We essentially used both in this course for practical applications: 
requests to get books from websites, and dictionaries to do some analysis of their 
content. 



## Berkley

:::{epigraph}
Have people in the past used Python to detect who wrote what in the Federalist Papers (like we talked about in class)?
:::

People certainly used computer code to analyze Federalist Papers and investigate 
who wrote them. I don't know if they used specifically Python for this purpose, 
any programming language could be used for such tasks. 

## Aidan

:::{epigraph}
Can "string.ascii_lowercase" be treated as almost a string in of itself? Like if you were to attempt to change 
a letter in it would it change that letter locally or not at all?
:::

`string.ascii_lowercase` is just a string with all lower case letters. It is provided for convenience, 
so one does not need to type the whole alphabet in cases when it may be needed. It has no influence 
on how Python processes text. Also, Python stings are immutable, so you can't change a sting in place, 
you can only create a new, modified string.


<br/><br/>