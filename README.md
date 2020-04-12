# Snake game
Snake is the classical game where the player maneuvers a line which grows in length, with the line itself being a primary obstacle.

### Description

I create this game based on pygame, tkinter libraries. I separated to 2 main parts of class. 
- 1st class = To create the area of movement of snake, the cube is started to consider.
- 2nd class = I created the characteristic of snake. Then, the abilities of snake are also set as well.

In those classes, I used for loop with if-statement to define for controlling. The movement of snake is controlled by the 4 arrow buttons. Then, the snake can be moved in 4 directions.
- Up
- Down
- Left
- Right

Afterthat, the grid is included to the area by defining the def function. In the main function, the cube (food for snake) is set for extending the length of snake. Moreover, the position of food is also been random in the region. Finally, I set the message box for alert the player who controls the snake to bite itself.
