# A Bayesian analysis of the impact of household income in the 2016 US Presidential Elections
## #R #JAGS #Markov Chain Monte Carlo

This project address the question if votes varied significantly across the 50 states based on the median household income 
during the U.S. presidential elections of 2016. A hierarchical Bayesian model to capture individual differences and group-level tendencies. 

This research brings insight as to why individual preferences could differ from the group-level tendencies. 
Accordingly, it has been noted that richer people are more likely to vote for Republican candidates while poorer people are more inclined to vote for Democratic candidates. 
However, in recent decades, we can observe the opossite: poorer states have voted for conservative Republicans while rich states favor liberal Democrats. 

The model considers an over-arching distribution: the model puts each state's estimated probability of voting for the Republican candidate 
under a distribution of state income categories. State income categories were classified as poor, middle, mid-upper and rich. 

The model implemented **Markov Chain Monte Carlo (MCMC)** to generate a sequence of samples from the posterior distribution of the parameters. 

For a theoretical explanation of the model and explanation of the results, please refer to the paper published in this repo. 
The code to compute the model was built in R, using **JAGS package**.
