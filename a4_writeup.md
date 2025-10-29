# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
The most difficult part to tic-tac-to was the has_won(self, player) function. This function really tripped me up because I tried solving it using loops because I tried to find the "best" or "most efficent" code for it to work. However, I realized that I just had to create a list of all the possible winning combinations and figure out if the player won through that. Additionally, I still was getting used to using self in my code as this was something new to me, as in java, although I did use "this.", the implementation in python is slightly different, which took some time getting used to.

2. Explain how you would add a computer player to the game.
I would add a computer player to the game use random functions, so that It would randomly place "X" or "O" on the board. I could make it better, however, by creating and algoritm based on what the player inputs, so that it could counter whatever the player does ending every game as a tie. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
I would create it so that it would take the input of the player after every move, and after going through a database would find the best possible move to make after. For example, if the player starts in a corner, the computer would play "X" or "O" in the opposite corner, or if the player is about to win, the computer will realize and defend.