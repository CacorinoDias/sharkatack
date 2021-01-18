
## 1. Introduction:

This is an analysis of shark attacks that happened around the world. The main objective was to try to find how many women were killed by sharks versus men, around the world. 

We were provided with a data set available on Kaggle, the information contained by the  data set was messy, so we were asked to clean it and answer a specific business question.

Besides the information available in the data set we also used google to do some factchecking of those attacks.

## 2. Hypothesis: ho How many females were killed by sharks versus males.

When we were given this task, the first thing I thought was that, probably we are going to have more males than females getting killed by sharks. 

I thought about this due to my personal experiences, I grew up near the shore and I was always into sea sports, many of my friends spearfished, were surfers and a bunch of relatives of mine fish, as well as I. So, though I knew many girls that were into these activities, my perception was that these activities were practiced by, mostly males.

I decided to take a look at the age groups of the victims.

## 3. Data Cleaning:

To get into the conclusions I head to exclude a bunch of attacks:

#### 3.1 Males and Females:


Inside the data set some of the rows represented group attacks where the genders of the victims were not mentioned, we excluded those rows.

If it represented an attack we knew how many the victims were and their  genders, we duplicated the lines for how many the victimns were.


#### 3.2 Males and Females:

We excluded all those cases where we could not assume the age of the person. We had many rows where, instead of a number we had (teen, adult, middle aged, etc.)

If we had (60's, 50's, 30's, ...) we assumed it was (65, 55,35,...)

If it was between a certain age, we attributed the average between those two. (ex: 24 or 26, we would assume it was 25).

#### 3.2 Fatality:

we excluded thoses cases where we could not conclude if the person died.

We also excluded the cases where the actual attack had appened.


## 4. Conclusions:

As we can see from the graph below most of the victims are people between the ages of 0 to 25.


![](Images/Age%20Group.png)


The data base includes attacks that happened hundreds of years ago. As we can see from the graphic bellow, throughout history most of the victims were male, and most of them were between 0 and 20 years old, thoug if we consider just the attacks where the victims were female, the largest group consists of females between 20 and 35 years old.


![](Images/Female%20and%20Male%20Deaths%20Age%20Group.png)


This is just a graph that shows that the through the years the number of attacks is on the rise thought, and this is very important it doesn’t take into consideration the fact that, world population is on the rise too.

![](Images/By%20Year.png)

