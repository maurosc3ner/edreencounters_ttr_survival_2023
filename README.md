![image](github.png)

# Description

Briefly, survival analysis is a branch of statistics that deals with analyzing the expected duration of time until one or more events happen. These events could be death in placebo vs treatment trial, mechanical failure in engines, or probability of- and time free of having an emergency department visit (my case). It's about understanding the 'lifespan' of a subject in a system.
We determined the probability of ED encounterfree survival time using hazard ratios (HRs) and time to recurrence (TTR) of ED encounter using Bayesian survival models. This repo covers all code developed for the project:

-Full probabilistic workflow (bayesian) for survival analysis in rstanarm, including recurrent visits (frailty).
-model specification with splines, priors, and validation.
fancy visualization from scratch in ggplot.
-even deployment in Shiny (working progress).

# Other sources

-Full manuscript here->[https://doi.org/10.1016/j.jaip.2024.07.009]

-My bayesian survival tutorial in R->[https://maurosc3ner.github.io/bayesian.survival.github.io/]
