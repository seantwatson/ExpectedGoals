# ExpectedGoals

This is the repository for an expected goals model I built using Stratagem data in 2018. Stratagem as a company since then appears to have stepped back from soccer/sports analytics as a whole, and I had been given the data for personal use, so unfortunately the data in this project appears to be lost. This is posted mostly for documentation of work rather than repeatability.

The data I use here is from csv's of Strata's "chances" data. This includes every "chance", or shot at goal, for 7 different leagues including MLS, Premier League, Serie A, Ligue 1, La Liga, Bundesliga, and the Champions League. Each file contains variables including the match, time, shot location, the body part of the shot, amount of defending/attacking players surrounding the chance, the amount of defensive pressure, where the chance came from (pass, cross, foul, etc.), and other descriptors.

This project is a little EDA, but is primarily focused on building a logistical regression model as well as analyzing and selecting the best performing model using the "outcome" variable to determine the probability that any given chance/shot results in a goal. Expected goals (or xG for short) is simply the name for the given probability of a goal.

Unfortunately due to my skills at the time of working this project, I was not able to work shot location or derive shot angle to use in the model, despite those being the most effective predictors. Professional xG models rely heavily on this, and the models are frequently visualized using 'shot maps' for a given player, team, or match. I would like to revisit this work and try to implement these variables now, but alas the missing data proves a barrier to that now.



