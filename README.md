# MovieLens Recommender System using SVD and Factorization Machines

# Table of Contents

[1. Introduction](#section-a)  
[2. Action](#section-b)  


## <a name="section-a"></a>1.  Introduction

Since 1998, [GroupLens](http://www.grouplens.org) has been releasing movie ratings datasets from the 
[MovieLens](http://www.movielens.org) website. Each release gaining in popularity and in content.

Here's a snapshot of what the ratings.csv file looks like:

~[image of dataset]
(ratings.png)
 
 
## <a name="section-a"></a>2. Action

Step 1. Created simple SVD (singular value decomposition) recommender system

Step 2. Created recommender system using Factorization Machines (TensorFlow). Here is a [paper](http://www.algo.uni-konstanz.de/members/rendle/pdf/Rendle2010FM.pdf) 
on Factorization Machines. This project was done with the help of [tffm](https://github.com/geffy/tffm).

Step 3. Compared the two to see if a more robust recommendation engine provides better results.