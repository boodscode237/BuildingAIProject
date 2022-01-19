# Detecting false recommendation comments on UDEMY courses

Final project for the Building AI course

## Summary

This project will try to detect spam comments on UDEMY courses. Sometimes we see comments that make us want to buy a course but when we start the course, it is not exactly what we expected. We will try to solve that problemto check if there are some spams recommendations among them.


## Background

Problems solved:
* problem 1 => Detect spams among the comments on a course;
* problem 2 => Avoid time wasting;
* problem 3 => Avoid money spending.


## How is it used?

The users are Udemy students who want to choose a worthed lesson. Avoid them to spend a lot of time watching videos that are not what they paid for.

It takes public informations about users, see check if they bought a course in the past, if they finished a course and how long they have been on UDEMY (If they are new or old). Also check the time between the course released and the comments. For a long course the comment should be made after a long time etc.


## Data sources and AI methods
Udemy API is the data provider. For that we need a special access.

## Challenges

The problem doesn't say if the course is bad of not. It just gives an opinion about the veracity of a recommendation based on what it has as input. Limitation are that the inputs for training are not sufficient enough. Because some other data as the number of hours spents on the site is important but we are can't access them for the privacy rules.
## What next?

Could be helpful to user if administrators of the site did that to show a percentatge of recommendation veracity.


## Acknowledgments

* [Element of AI](https://www.elementsofai.com/)
