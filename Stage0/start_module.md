# Start Module

## Features

  This module sets the ball in middle and starts the counter.
  
### Scenario : Start the game

    Given the game is in progress.
    
    When the game starts for the first time or one of the player
    scores point.
    
    Then this module resets the position of the ball in the middle
    of the board and starts a 3 seconds counter after which the
    gets initial speed and random direction.
