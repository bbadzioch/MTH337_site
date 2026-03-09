# Weekly digest 6

## Joseph

:::{epigraph}
Is the rest of this course going to be on numpy arrays, or are there other topics to be covered?
:::

We will use other Python data structures, but numpy array will keep showing up, since they
are useful in many computations.


## Alan

:::{epigraph}
Will our next project be due before or after break?
:::

After.

## Jaimie

:::{epigraph}
Do you think the epidemic project will be due before or after spring break? 
:::

After. 


## Erica

:::{epigraph}
Will the next project be due after break?
:::

Yes.


## Ryan

:::{epigraph}
In the project, what would be the best way to implement bullet point four? I am struggling trying to build up a working method for it. 
:::

This should not involve significant changes to the code. In the staring array describing states of all nodes, 
some nodes will be in the state 3 - vaccinated. Then, at each epidemic step nothing happens to these nodes - 
they  stay in state 3 forever.


## Rodrigo

:::{epigraph}
Will we learn how to animate the epidemic models like the one in the project demonstration? 
Or will the project be based on static models?
:::

I will show how to incorporate some interactivity in plots. However, most useful plots for this project 
will be static.


## Alyssa

:::{epigraph}
Do you know yet when the next project will be due?
:::


Yes, I have posted it already - see "Current Tasks" page. 


## Briana

:::{epigraph}
Are any of the weekly digest dropped? I missed the week before this (Weekly Digest 5) because I couldn't find the link and 
I'm wondering how much it will affect my grade? What are the drops for this class overall actually?
:::

It is in the syllabus: I will drop one digest, one quiz, and one project. 



## Pierce

:::{epigraph}
Is the next project due before, after or during spring break?
:::

After.


## Muhammed

:::{epigraph}
How much long/in detail should the project 3 be? Similar to project 1?
:::


I don't think that any project should be necessarily shorter or longer than 
any other. It mostly depends on what you do with it. 


## Henry

:::{epigraph}
How does changing the probability change the connections in the random graph?
:::


If probability of connecting two vertices by an edge is lower, then the graph will 
have fewer edges. If a graph has $n$ nodes and probability that any two 
nodes are connected by an edge is $p$, then the expected number of edges
will be  $\ \frac{pn(n-1)}{2}$.



## Bernice

:::{epigraph}
Are we able to collaborate with other classmates on our projects? For example, 
working together on operations but having different code.
:::


It is fine if you talk about the projects, but the report has to be written 
by each of you on your own. You also need to be able to explain it in detail, 
including every piece of code you submit.



## Shane

:::{epigraph}
Will we have everything we need to know for the project before spring break?
:::

Yes.



## Vidhi

:::{epigraph}
How many projects are left for the semester?
:::

There should be around 6 altogether.


## Berkley

:::{epigraph}
The overview for the Epidemic Project shows a gif/video of the edges 
and nodes changing color with disease and recovery, will we need to produce 
something like this for the project?
:::

This gif was produced with matplotlib, but you will not need to do this. 


## Daniel

:::{epigraph}
How else can we study for quizzes past the practice quiz
:::

Real quizzes are similar to practice ones, so if you can do the practice one
without problems, you should be fine. 


## Nicholas

:::{epigraph}
When you presented your simulation of the Epidemic Project, your graph cycled 
through the spread of the epidemic. Was that a specific matplotlib.pyplot/networkx 
feature, or were you using time.sleep maybe?
:::

The animation was done with 
[matplotlib animation feature](https://matplotlib.org/stable/users/explain/animations/animations.html), 
and then the resulting animation was saved as a gif. This is not 
essential to this project, so I don't plan to go into this in class, 
but it is not complicated. 


## Christian

:::{epigraph}
How would changing probability in a random graph affect the structure overall?
:::


Increasing probability means increasing the average degree of each vertex, which 
affects overall properties of the graph. For example, if probability is big enough
then the graph will have a [giant component](https://en.wikipedia.org/wiki/Giant_component). 
This means that you will be able to get from almost any vertex to almost any 
vertex following a sequence of edges.

## Aidan

:::{epigraph}
How could we go about adding more states to the project? We could, in theory, add 
states like "dead" or "vaccinated."
:::

It depends how you want these new states to behave. "Dead" is actually not different 
than "recovered" - in both cases a node is first sick, then transitions to a new state, 
and then nothing else happens to it. "Vaccinated" behaves as "recovered" from the start - 
a node never changes its state. Unless you want to simulate a vaccine that is also 
partially effective (as vaccines typically are). Then a vaccinated node can still get sick, 
but with a lower probability.

## Andrew

:::{epigraph}
Is there an easy way to select random values from a custom distribution using NumPy?
:::

Yes. `numpy.random` implements many 
[commonly used distributions](https://numpy.org/doc/stable/reference/random/generator.html#distributions). 
For example, this code creates  an array of 100 numbers drawn from the normal 
distribution with mean 0 and standard deviation 1:

:::python

import numpy as np

rng = np.random.default_rng()
arr = rng.normal(loc=0, scale=1, size=100)
:::

If you want to use something not already implemented, then this is also not hard to do, 
but would take longer to explain. 


## Jarrod

:::{epigraph}
How does the connectivity of a graph affect how quickly an epidemic spreads in the model? For example, 
would a graph with a few highly connected nodes spread infection faster than a graph where all nodes 
have about the same number of connections?
:::

This is actually a good question to investigate as a part of this project. 






<br/><br/>