# TLDR;

## The Problem

Imagine you are a contestant on *Let’s Make a Deal*, a famous American game show hosted by Monty Hall. 

In the event, the host presents you with three closed doors---let’s call them $A$, $B$, and $C$.

He then informs you that behind one of the doors is a brand new car, while behind the two others are goats. 

You really want the car, and if you can guess the door the car is behind, you get to keep it. 


The host invites you to guess which door contains the car and so you guess door $A$.

At this point, instead of letting you know if you guessed correctly, the host, who knows where the car is, opens a door that you did not guess, door $B$, which reveals a goat. 

The host then gives you the opportunity to change your guess to the remaining door, door $C$. 

The question is, should you stay with door $A$ or switch to door $C$?

## The Solution

The surprising solution to the question of whether you should keep door $A$ or switch to door $C$ is that you should switch. 

If you stick with door $A$, the probability of winning the car is $\frac{1}{3}$. If you switch to door $C$, it is $\frac{2}{3}$. 

## The Reason

There are actually only two relevant scenarios of the game: Either the contestant guesses correctly the first time, or the contestant guesses incorrectly the first time. 

The first scenario has a probability of $\frac{1}{3}$, while the second has a probability of $\frac{2}{3}$, since there are two incorrect doors and one correct door to choose from.  

Now, if the contestant is right and switches, she will obviously lose. 

But, if the contestant is wrong and switches, she will win. 

The scenarios keep their probabilities, so switching in second scenario yields a $\frac{2}{3}$ probability of winning.

She will win because if a door is revealed to be empty, *the other door is the only one remaining and so must have the car*. 

The host has no choice but to reveal the door that does not hide the car. 

Therefore, the contestant has a $\frac{2}{3}$ chance of winning if they switch. So, she should switch.

## What's missing

Although the above makes logical sense, it's still not clear why it's true.