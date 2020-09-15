# Bridgetree - API Developer Challenge
In this challenge we would like for you to create a .NET Core API in a Docker container that will enable the game of Snakes and Ladders to be played (Source: [Wikipedia](https://en.wikipedia.org/wiki/Snakes_and_Ladders)). Please see below for basic rules of play:

### The Board
Below is an image of the gameboard. You will need to setup the game to play according to this board. 
![SnakesAndLaddersGameBoard](/sandl.jpg)
 
### The Rules of the Game
1.	Players cycle through turns. Player 1 starts. Once their turn is over play proceeds to Player 2, etc., and then back to Player 1. 
2.	Players will ‘roll’ two dice and move the sum of both dice. Players will follow the numbers up the board in order from 1 to 100. Players will start off the board, thus a player’s first roll will move them to the square that is equal to the sum of the two dice.
3.	If the value of both dice is the same (called a double), then that player gets to roll again.
4.	Climb up ladders. The ladders on the game board allow you to move upwards and get ahead faster. If you land exactly on a square that shows an image of the bottom of a ladder, then the player moves all the way up to the square at the top of the ladder. 
5.	Slide down snakes. Snakes move you back on the board because you must slide down them. If you land exactly at the top of a snake, move the player all the way to the square at the bottom of the snake.
6.	To win, players must land exactly on the last square. The first person to reach the last square on the board wins (even if they rolled a double). But there's a twist! If you roll too high, your player "bounces" off the last square and moves back. You can only win by rolling the exact number needed to land on the last square. For example, if you are on square 98 and roll a five, move your game piece to 100 (two moves), then "bounce" back to 99, 98, 97 (three, four then five moves). If a bounce back results on a player landing on a snake or ladder square, then the above rules apply for those square types.

### API Requirements
The API will need to allow the client at a minimum to do the following:
* Retrieve the location of a player on the game board.
* Roll for a player and move the player acccordingly.

The API will also need to persist the state of a game so players can pick back up where they left off at a later time. Feel free to fill in any other gaps as you see fit to help facilitate game play.

Please complete your solution in a GitHub repo and provide the link to us. If you have questions, please reach out to your Bridgetree contact and we will get back to you.
