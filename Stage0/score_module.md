# Score Module

## Features

  This module keeps track of score of the players
  and declares the winner

### Scenario : Set the score to zero

  Given the game is installed and player is in start page.
  
  When player selects on of the option to play in the play module.
  
  Then this module sets the scores of both players to zero.

### Scenario : Update the score

  Given the game is in progress.
  
  When the ball hits the wall behind the paddle and controller
  module calls score module.
  
  Then this module updates the score of the player by determining the
  position of the ball.

### Scenario : Declare the winner

  Given the game is in progress.
  
  When the one of the players score becomes 10 points.
  
  Then this module declares that player as winner.
