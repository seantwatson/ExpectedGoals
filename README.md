# ExpectedGoals

This is my repository for all of my work on expected goals (xG) models for soccer data analytics.

The first project is from 2015 and was some of my first personal exploration into soccer analytics. The data used here is proprietary data from a company named Stratagem. Specifically I am using data which are csv's of Strata's "chances" data. This includes every "chance", or shot at goal, for 7 different leagues including MLS, Premier League, Serie A, Ligue 1, La Liga, Bundesliga, and the Champions League. Each file contains variables including the match, time, shot location, the body part of the shot, amount of defending/attacking players surrounding the chance, the amount of defensive pressure, where the chance came from (pass, cross, foul, etc.), and other descriptors.

This project is a little EDA, but is primarily focused on building a logistical regression model as well as analyzing and selecting the best performing model using the "outcome" variable to determine the probability that any given chance/shot results in a goal. Expected goals (or xG for short) is simply the name for the given probability of a goal.

Unfortunately due to my skills at the time of working this project, I was not able to work shot location or derive shot angle to use in the model, despite those being the most effective predictors. Professional xG models rely heavily on this, and the models are frequently visualized using 'shot maps' for a given player, team, or match. I would like to revisit this work and try to implement these variables now, but alas the missing data proves a barrier to that now.

I have however revisited this project a second time in Python instead of R, and with more familiarity and skills with the concepts. Here, I have used publicly available event data from StatsBomb. The main goal and differences of attempting this project a second time was about implementing shot distance and shot angle as key features of the model, which I was unable to do originally. Additionally I wanted to make a stronger effort of visualizing the results of my model, as well as talking through some of the strengths and weaknesses of the model and of the data I used.
