# Score Module

## Features

  This module keeps track of score of the players
  and declares the winner

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
