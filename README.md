

unit-4-game
Creator: Carlos Quinones
Type of Project: JQuery Game

Started on: August 31st 2019 Completed on: Sep 3th 2019

Important Links
<ahref src="https://ceq2000.github.io/unit-4-game/index.html">Link to the game site</a>

Link to my repository

Description of Application
Crystals Collector is a web-based game, where a user has to guess the value of the crystals in order to match a random number geneartes by the system.

The game is played as follows:

Four crystals are displayed to the user as buttons on the page.

At the start of the game, a random number between 19-120 is displayed to the user.

Each crystal has a random number between 1-12 associated to it.

When the player clicks on a crystal, the system will add the value of the crystal to the user's total score.

The game does not display the value associated with the crytal unless if the user clicks on it.

The player wins if their total score matches the random number from the beginning of the game.

The player loses if their score goes above the random number.

The game restarts whenever the player wins or loses.

When the game begins again, the player should see a new random number. Also, all the crystals will have four new hidden values.

JQuery File
The game has 3 functions and 1 click event

Functions created/used in this game are:

gameBegin: Re-sets the game while leaving the wins/losses tally intact. Also generates the target random number and the hidden rndowm values of the 4 crystals. The random number shown at the start of the game should be between 19 - 120. Each crystal should have a random hidden value between 1 - 12.

playGame: Adds up the numbers associated to the crystal everytime a user clicks a crystal

checkResult: Checks if the crystal total equals the target random number

** If greater, then the system displayes " You Lost" to the user and incrments Losses score by 1 If crystal counter matches the target randwom number, then the note "You Won" is displayed to the user and increments the score by one.

The Click Event captures the users click and parses the number.
List of Technologies Used:
HTML
CSS
Javascript
JQuery
Git
