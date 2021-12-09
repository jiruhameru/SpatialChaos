What is this?

This is a simple simulation of the dynamics referred in the paper: ‘Evolutionary games and spatial chaos’ by Martin A. Nowak and Robert M. May. (Nature 359(6398):826-829, 1992) which describes a 2D spatial and deterministic version of the Prisoner's Dilemma, where players have no memories of past encounters. Interesting kaleidoscopic patterns are obtained with particular parameters of (Temptation).


How it works

Each player is preset with a fixed strategy, either to Cooperate or Defect. At each round, players interact with their immediate neighbors using Prisoner's Dilemma game rules, after that, the site is occupied either by its owner or by one of the neighboring players depending on who gets the highest payoff. The color coding is as follows: red represents a Defector that follows a Defector, blue: a Cooperator that follows Cooperator, yellow: a Defector that was a Cooperator, green: a Cooperator that was a Defector.


The particular case of kaleidoscopic pattern is generated using specific values for the payoff matrix, in particular the temptation to defect (T).


How to use it?

The following values constitute the payoff matrix: 

T -> 2.0

R -> 1.0

P -> 0.01

S -> 0.0



The temptation value (T) being the important variable to this distinctive pattern is refered to as 'b' in the code, as well as in the original paper.


Things to notice

At first, the lattice is set with only one defector in the middle (red) and all cooperators (blue). A beautiful dynamic kaleidoscopic pattern starts forming and expanding. The symmetry is astonishing. 

Video demonstration:
https://vimeo.com/416408060


