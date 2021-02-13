# Connect Four AI

This project is an implementation of a Connect Four AI using a minimax algorithm with alpha-beta pruning. The game playable in a representation in the console and its a head to head game against the AI.


## Implementation

The AI is built using the minimax algorithm with alpha-beta pruning. The psudeo code for the algorithm can be found [here](https://en.wikipedia.org/wiki/Alpha–beta_pruning). For the evaluation function we used simple score given condition such as three in a row and two in a row. The state of the game is represented using a numpy matrix and certain helper functions is used to update the state.


## Possible Improvements
* A better heurstic evaulation function.
* Some performance optimizations to make the algorithm run faster.
* AI against AI games.
* Grahpical Interface.
