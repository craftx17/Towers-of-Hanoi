# Towers-of-Hanoi
Logic game

- there are three towers. The goal of the game is to move all of the discs from tower A to tower C without ever putting a bigger disc on a smaller one
- would like to have an option between 3 and 8 discs
- need to figure out how to make gui interface


Outline:

Need a disc class and a tower class.
towers hold discs.

Tower variables: 
string location (start, middle, or end)
stack pile (holds discs)

Disc variables:
int weight (range from 1 to 8)
