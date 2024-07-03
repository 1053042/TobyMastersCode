# TobyMastersCode
This repository contains the code used in my masters project on modelling the evolution of parental care in variable environments. There are three parts:

Part 1:
This contains the R code that finds the resident equilibrium value for a sex specific population that provides a certain form of care (male, female or biparental) at a range of different values for different life history parameters. It then saves these values to a datset. This code uses only male care but can be changed for biparental and female care (as shown in the code. These values are saved in a dataset for use in parts 1 and 2.

This also contains the mathematica code that finds the fitness of a mutant care strategy that invades a resident strategy accross two environments that vary in life history and finds the geometric mean of this fitness. The code only does this for a transition from male to female care but can be adjusted for a transtion between any form of sex specific care.

Part 2:

This contains the mathematica code that finds the fitness of a strategy that distributes its offspring evenly accross environments (alpha = beta = 0.5) invading a strategy that does not distribute its offspring. In both the resident and mutant startegy have the same form of care. This produces graphs that shows the fitness of this mutant startegy as the environment becomes increasingly variable. The code only shows male care but can be changed to show any form of care (see code).

Part 3:

This contains the R code that uses rk4 analysis to find the resident equilibrium values of a strategy that distributes its offspring between environments (alpha and beta <1. Alpha = 1 - beta). It iterates the process over multiple values of alpha and beta then repeats over variation in different life history variables. Only male care values are used but can can changed accordingly. It saves these values as a dataset.

The this mathematica code finds the geometric mean fitness of a mutant strategy invading across a variable environment when it distributes its offspring more between environment 1 or environment 2. (e.g. alpha > 0.5 or alpha < 0.5).
