# PacMan-Game

Pacman is a classic arcade game developed in the 1980s. The objective of the game is to control Pacman, a yellow character, through a maze while eating dots and avoiding four ghosts that are trying to catch and kill him. The game is divided into levels, each of which consists of a maze and a certain number of dots that must be eaten. The ghosts become faster and more difficult to avoid as the player progresses through the levels. Pacman has to eat power pellets which give him the temporary ability to eat the ghosts. The game ends when Pacman loses all of his lives or when he completes all levels of the game. The game has become an icon in the video game industry and is still popular today.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python pac.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* ```from random import choice```: This line imports the choice function from the random module. It is used later to randomly select a direction for the ghosts to move.

* ```from turtle import *```: This line imports everything from the turtle module. This is used to draw the game window and the game elements.

* ```from freegames import floor, vector```: This line imports two functions, floor and vector, from the freegames module. floor is used to round off the position of the game elements to the nearest integer, and vector is used to represent the position and direction of the game elements.

* ```state = {'score': 0}```: This line creates a dictionary called state with an initial score of 0.

* ```path = Turtle(visible=False)```: This line creates a turtle object called path with its visibility set to False. This is used to draw the walls of the game.

* ```writer = Turtle(visible=False)```: This line creates a turtle object called writer with its visibility set to False. This is used to display the score on the game screen.

* ```aim = vector(5, 0)```: This line creates a vector object called aim that represents the direction that Pacman is moving in.

* ```pacman = vector(-40, -80)```: This line creates a vector object called pacman that represents the position of Pacman on the game screen.

* ```ghosts = [...]```: This line creates a list called ghosts that contains four ghost objects. Each ghost is represented as a list of two vector objects - one for the position and one for the direction.

* ```tiles = [...]```: This line creates a list called tiles that represents the layout of the game. Each element in the list is either a 0 or a 1, where 0 represents a wall and 1 represents a space that Pacman can move through.
