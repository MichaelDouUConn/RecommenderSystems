# RecommenderSystems

This repository contains an implementation of the collaborating filtering algorithm with an application to a MovieLens data set.

## Data

Ratings of 1682 movies by 943 users.

## Code

MATLAB

## Implementation

### Step 1: 
Perform row-wise mean normalization on the data matrix, i.e. substract each rating by an average rating of this movie.
### Step 2:
Calculate the cost function and gradient. Perform collaborating filtering using conjugate gradient optimization technique to learn the parameters X and Theta (both are matrices).
### Step 3:
Provided recommendation based on predicted ratings on movies that user i has not rated and wateched.
