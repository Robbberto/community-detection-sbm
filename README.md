# Community Detection on Stochastic Block Model

Authors: Francesco Borg, Roberto Ceraolo, Arturo Cerasi


Given a Stochastic Block model with two communities, the goal of this project is to test the performances of various algorithms, based on Markov Chain Monte Carlo simulation, in identifying the two com- munities. Several simulations using Metropolis-Hasting, Houdayer and a Mixed Metropolis-Houdayer algorithms have been run. For suitable values of the parameters, all the algorithms were able to identify the two communities, with different convergence rates. We observed two main insights: the convergence rate strongly depends on the number of nodes of the network (Houdayer performs the best in large networks settings). And the ability to correctly categorize the nodes into the two communities depends on the ratio of the probabilities of inter-cluster over intra- cluster connection, with a threshold point, above which the algorithms struggle to converge.
