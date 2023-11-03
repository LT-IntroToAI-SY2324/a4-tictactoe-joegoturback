# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
I think the challenging part of making tic tac toe was making the game over after a conditon had been met, such as when a player won or when the game was drawn. Making the board was the easy part, however th egame mechanics was a bit more challenging, although not too hard. However, trying to fixing bugs or programming mistakes was difficult because there is a lot to trace.

2. Explain how you would add a computer player to the game.
I would first write code that would enable the player to choose wither X or O, and whichever they pick, the omputer is in control of the opposite side. Then I would make a randomizer fo the computer to put in their mark anywhere on the board as long as the space hey pick isn't filled in already. In order to not make the computer pick a space that is already filled in, I would include a conditional statement that makes it not pick a square that is not an asterisk.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

I think I might make a conditional statement that first checks for every explicit winning move. For example if the player made a mistake and there was two of the computer's marks in a row diagonally or straight, the computer would place the last mark in the winning square. However, this would require a lot (eight) if statements for each possible winning combination. And to deflect a player's threat to win, the computer would check if two of the player's marks were in the same row and the next square was open, when it's the computer's turn. Like how the computer checks to see if there is a winning position, I would make a lot of if statements to check if the player's marks were two straight or diagonal and there was an open square in the third. Then the computer wold place its mark on that square, stopping the player from winning. Alongside that, I would just have the computer play normally placing on random squares.