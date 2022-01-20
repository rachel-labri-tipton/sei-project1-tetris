// Tetris 2.022

Hi there, this is my first full coding project completed for the the General Assembly Software Engineering Part-Time Bootcamp (Nov 2021 - May 2022). 

Tetris is a classic arcade game created in 1984 by Alexey Pajitnov. If you're a 90's kid, you might of played it on your GameBoy. The game requires players to rotate and move falling Tetris pieces, tetriminoes (each piece is made of 4 blocks). Players clear lines by completing horizontal rows of blocks without empty cells. If the pieces reach the top, the game is over. 

I've named my game here Tetris 2.022 because I worked on it in 2022. In my game, if the pieces reach the top, the game ends and the player is prompted to play again. If the player scores 1,000 on a certain level, they "win" and are asked to try another level. Before starting to code, I read about the game and researched different approaches to handling the drawing of the pieces and their movement. I decided to go with a set of arrays that built the tetriminoes as arrays filled in by applying a specific class. 


THE LOGIC BEHIND THE GAME 

The game is built around the following functions: 

Drawing the pieces: 
drawPiece()
undrawPiece()
moveDownScreen()
stopMovement()

Moving the pieces: 
moveLeft()
moveRight()
rotatePiece()

Fixing rotation of the pieces at the edge of the board: 
isAtRight()
isAtLeft()
checkRotatedPiece() 

Score and Line Count: 
addScore()

Levels (this is apart of the code I find repetitive): 
nextStep() (original play functio)
levelUp2() (time interval increased)
levelUp3() (time interval increased)

Ending play: 
endGame()   
resetGame()
undrawBoard()


Sound functionality: 
Each movement of a piece has a sound function except when a piece lands on another piece. This part of the code is a bit repetitive as well. As I was adding this at the end, it was working, so I went with it. I've also added a button to play the original Tetris Game. I didn't manage to get the button to toggle play and pause. 


Future versions: 
I would like to build in a function that changes the color of the screen when the level is changed and a function that draws the next piece in a small grid next to the board. I worked on this for awhile, but decided to let it go as the deadline for the project was approaching.




