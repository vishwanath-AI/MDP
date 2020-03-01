# Markov Decision Processes
First we define an MDP, and the special case of a GridMDP, in which
states are laid out in a 2-dimensional grid.  We also represent a policy
as a dictionary of {state:action} pairs, and a Utility function as a
dictionary of {state:number} pairs.  We then define the value_iteration
and policy_iteration algorithms.

If you need a brief intro of reinforcement learning in a simple way,   
Reinforcement-Learning = Representation + Evaluation + Optimization.

### Concept of pareto dominance
An outcome of a game is Pareto dominated if some other outcome would make at least one player 
better off without hurting any other player. That is, some other outcome is weakly preferred by all players and strictly 
preferred by at least one player. If an outcome is not Pareto dominated by any other, than it is Pareto optimal, 
named after Vilfredo Pareto.

### Value Iteration building process for mathmatical notation  
Value iteration is a method of computing an optimal MDP policy and its value. 



Refrence:  
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7424300  
https://artint.info/html/ArtInt_227.html  
http://aima.cs.berkeley.edu/python/mdp.html  
https://en.wikipedia.org/wiki/Markov_decision_process  
https://en.wikipedia.org/wiki/Markov_decision_process#Notable_variants  
https://pymdptoolbox.readthedocs.io/en/latest/api/example.html  
https://www.cse.unsw.edu.au/~cs9417ml/RL1/algorithms.html
