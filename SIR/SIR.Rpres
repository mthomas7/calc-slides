SIR
========================================================
author: Math 111
date: 
autosize: true

Logistics
===
Syllabus questions?

Homework:
  * Webwork
  * Survey
  * HW Set 1
  * Section numbers in text (on calendar)

Graphing
===
Let's look at a graph of yesterday's data

Which of the following is a reasonable graph for R vs. t? Why? Why are the others NOT reasonable representations?
===
A
![](A.png)

***

B
![](B.png)

===
C
![](C.png)
***
D
![](D.png)

More graphs
===
* Now on paper, as a group, sketch possible graphs from S vs. t and I vs. t (on separate papers)
* What qualities did you need to ensure that your graphs had? Why?
* When you are done with the first two:
  * When will the R population be changing the fastest?
  * When will the S population be changing the fastest?
  
Factors
===
We discussed important features of our model. How do S, I, and R relate to each other?

Scenario 1
===
Suppose that the city's Board of Health reports that the measles infection has been spreading at the rate of 470 new cases per day for the last several days. 

If that rate continues to hold steady and our population starts with 20,000 susceptible people, determine the following:
* What will the size of the susceptible population be in 4 days? 
* How many new infections have occurred in these 4 days? 
* How many susceptibles were there 2 days ago?

Go deeper: express the susceptible population in terms of d, the number of days from today (i.e., $d=1$ is tomorrow, $d=-1$ is yesterday)

Scenario 2
===
Now, assume that in our of a population of 20,000 people, 940 are infected. Each day, about half of the infected population infects one susceptible.
* How many new infections occur on the first day?
* How many new infections occur from day 1 to day 2?
* How many new infections occur from day 2 to day 3?
* What are the challenges to writing a formula for the susceptible population?

Compare and Contrast
===
* How does scenario 1 relate to scenario 2? What is similar? What is different?
* Which one do you think is a better representation of the actual behavior of the infection?

Rates
===
* Both scenarios involve a rate.
  * Scenario 1: Constant rate
  * Scenario 2: Changing rate
* Which was more realistic?
* Goal: Find a mathematical expression

Notation
===
* $S(d)$, $I(d)$, and $R(d)$ are the **number** of susceptible, infected, and recovered people on day $d$
* $S'(d)$ is the rate at which the population of susceptibles is changing
* $I'(d)$ is the rate at which the population of infecteds is changing
* $R'(d)$ is the rate at which the population of recovereds is changing

S’(d), I’(d), R’(d) may change over time!

Rate of Recovery
===
incremental:true
* $R'(d)$: This seems complicated - how can we simplify the "3 day recovery rule"?
* What if we assume 1/3 of the current infected population recovers each day?

* Suppose $I(4) = 2100$ people
  * What would $R'(5)$ be?
  * What would $R(5)$ be?
  * What would $I(5)$ be?
* Write a mathematical expression for $R'(d)$

Rate of Transmission
===
* $S'(t)$
* What factors affect rate of disease transmission?
* Simple scenario:
  * 5 healthy people
  * 3 sick people
  * Interaction always leads to infection
* How many possible interactions are there between a healthy person and a sick person?
* How many people will get sick during day 1?
* What factors influence this?

Rate of Transmission
===
* $S'(t)$
* What factors affect rate of disease transmission?
* Simple scenario:
  * 5 healthy people
  * 3 sick people
  * Interaction always leads to infection
* How many possible interactions are there between a healthy person and a sick person?
* How many people will get sick during day 1?
* What factors influence this?
* What if 1/3 of interactions leads to infection?
* Write a mathematical expression

Notation
===
* S*I = the total number of possible "interactions" between healthy and sick people if there are S susceptibles and I infecteds
* p = proportion of interactions that actually happen in a day
* q = probability an interaction infects a susceptible.
* pSI = number of interactions that *occur*
* qpSI = number of new sick people

* a=qp 
* a is the "transmission coefficient""

Full model
===
$S'(t) = -a S(t) I(t)$

$I'(t) = a S(t) I(t)-b I(t)$

$R'(t) = b I(t)$

Using a spreadsheet
===
Let's use a spreadsheet to start to model this
