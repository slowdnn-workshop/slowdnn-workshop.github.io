---
name: Daniel Soudry
role: Speaker
website: https://sites.google.com/site/danielsoudry/
affiliation: Technion
photo: soudry.png
talk: How catastrophic can catastrophic forgetting be in linear regression?
abstract: 'Deep neural nets typically forget old tasks when trained on new tasks. This phenomenon, called "catastrophic forgetting" is not well understood, even in the most basic setting of linear regression. Therefore, we study catastrophic forgetting when fitting an overparameterized linear model to a sequence of tasks with different input distributions. We analyze how much the model forgets the true labels of earlier tasks after training on subsequent tasks, obtaining exact expressions and bounds. We establish connections between continual learning in the linear setting and two other research areas: alternating projections and the Kaczmarz method. In specific settings, we highlight differences between forgetting and convergence to the offline solution as studied in those areas. In particular, when T tasks in d dimensions are presented cyclically for k iterations, we prove an upper bound of T^2 * min{1/sqrt(k), d/k} on the forgetting. This stands in contrast to the convergence to the offline solution, which can be arbitrarily slow according to existing alternating projection results. We further show that the T^2 factor can be lifted when tasks are presented in a random ordering. Joint work with Itay Evron, Edward Moroshko, Rachel Ward, and Nati Srebro, published in COLT 22.'
---
