# Assignment context

As our client (a company that produces healthy beverages) enters its next wave of growth, it needs data driven insights to inform where to fuel this expansion. First and foremost, [brand] wanted to understand the value-based mindsets and behaviors of its potential customer segments.

We fielded a survey to a representative sample of 1,000 U.S. adults interested in health and trying new things. The survey included a battery of 51 psychographic survey items to surface the segments of Americans most likely to be interested in [kombucha](https://en.wikipedia.org/wiki/Kombucha) according to several dimensions (e.g., openness and adventure, healthy lifestyles, values alignment). The segmentation is a useful heuristic for understanding and targeting [brand]’s current and potential future audiences based on values and behaviors that are key to activating kombucha drinkers.

For this assignment, we would like to:

-   Create clear and concise segments from the psychograhic battery of questions
-   Use the demographic variables as profiling / explanatory variables only (won't include these in the clustering process)

The goal is to group like-minded people together based on their mindsets and attitudes, not their demographic profile.

Imagine that we are the end client, and we want to know **what type of customers are out there, and which ones are more or less likely to try kombucha in particular, and why.**

# Overview of Approach

Below I outline the approach taken to complete this analysis. This will include the following steps:

1.  Import and clean the data
2.  Prepare the data for use in NMF (Non-negative Matrix Factorization), which will provide us with clusters and their dominant features (i.e. values)
3.  Cluster the data using NMF. This will include determining the optimal number of clusters to use
4.  Assign the clusters to each respondent
5.  Evaluate each cluster's demographic variables, including their likelihood to try kombucha
6.  Analyze the values index for each cluster to understand how their values differ from the overall population

The steps above will allow us to understand the different segments of the population, their likelihood to try kombucha, and their values. This will allow us to make recommendations to the client on who these segments are and which to target.
