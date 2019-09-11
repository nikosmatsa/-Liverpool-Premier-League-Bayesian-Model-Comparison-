# -Liverpool-Premier-League-Bayesian-Model-Comparison-


P.Value is absolute so IT SUCKS..!!!
Bayes factor is OK.
But have you ever wondered if there is even something far more better 
than all these when it comes to model comparison?
If you dive deep into the Hamiltonian Monte Carlo (Stan)
world you will find new methods of calculating the model comparison
using LOO-CV(Leave-One-Out Cross Validation) which is, through asymptotic, 
the same as WAIC.This time we compare the expected predictive accuracy of 
one model against another, via their log likelihood.
For this purpose i represent to you Liverpool's data from Premier League
season 2018-19 and i fitted in stan 2 models, calculating their rate "lambda" 
of goals.Goals in football are a rare event so poisson selection is obvious.
First fitting model is a Log Poisson-Gamma(prior) 
and the second is a Log Poisson-Normal(prior).Enjoy my code in R..!!!
