# unit-4-game
Crystal Collector: Game app that dynamically updates HTML pages with the jQuery library.

### **Creator:** `Carlos Quinones`
**Type of Project:** `JQuery Game`

Started on: August 30th 2019
Completed on: Sep 3th 2019
- - -

## Link to Travel App Website

* [Link to the Let's Go! Travel App Website](https://davidlevens.github.io/Project-1/)

- - -
## Description of Application
- - -

Crystals Collector is a web-based game, where a user has to guess the value of the crystals in order to match a random number geneartes by the system. 

The game is played as follows:

1. Four crystals are displayed to the user as buttons on the page. 

2. At the start of the game, a random number between 19-120 is displayed to the user. 

3. Each crystal has a random number between 1-12 associated to it. 

4. When the player clicks on a crystal, the system will add the value of the crystal to the user's total score.

5. The game does not display the value associated with the crytal unless if the user clicks on it. 

6. The player wins if their total score matches the random number from the beginning of the game.

7. The player loses if their score goes above the random number.

8. The game restarts whenever the player wins or loses.

9. When the game begins again, the player should see a new random number. Also, all the crystals will have four new hidden values. 

## JQuery File
- - -
`The game has 8 functions and 1 click event`

## Main functions created/used in this game are:

 - **RandomNumber:** Generates random game number to match

 - **pickRandomCrystals:** Generates array of random crystal values

 - **crystalValues:** Displays random crystal values

- **pickRandomNumber:** Picks random numbers to match at the beginning of the game.

- **pickRandomCrystals:** Picks random numbers and assigns them to each crystal.

- **crystalValues:** Changes value of each crystal button according to array

- **pickRandomCrystals:** Picks random numbers for crystals

- **gameReset:** Re-sets the game while leaving the wins/losses tally intact. Also generates the target random number and the hidden random values of the 4 crystals. The random number shown at the start of the game should be between 19 - 120.
Each crystal should have a random hidden value between 1 - 12.

- ** NOTE: If numbers generated are greater than 120, then the system displays " Sorry ... you Lost!" to the user and increments Losses score by 1. If crystal counter matches the target randwom number, then the alert "You Won" is displayed to the user and increments the score by one. 

      The Click Event captures the users click and parses the number.

## List of Technologies Used:
- - - 
- HTML 
- CSS
- Javascript
- JQuery
- Git
