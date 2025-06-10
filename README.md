# Mosquito Attraction and Beer Consumption: Permutation Test Analysis

This project analyzes the effect of beer consumption on mosquito attraction using statistical methods demonstrated in John Rauser's talk Statistics Without the Agonizing Pain (Strata Hadoop 2014).

We use a dataset containing mosquito attraction responses from participants who consumed either beer or water. The analysis compares the mean number of mosquitos attracted in the two groups and applies a permutation test to assess whether the observed difference is statistically significant or could have occurred by random chance.

The key steps include:

Calculating observed differences in means between the beer and water groups

Running a permutation test with 10,000 simulations to generate a null distribution of differences

Computing the p-value to evaluate the significance of the observed difference

Visualizing the permutation distribution alongside the observed difference

The results strongly support the conclusion that beer consumption significantly increases mosquito attraction, with a very low p-value rejecting the null hypothesis of no difference.
