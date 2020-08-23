# Calculate ball direction

## Features

This module calculates ball direction.

### Scenario : Ball direction when it hits the side walls

  Given the game is in progress.
  
  When the ball hits one of the side walls.
  
  Then the angle of incidence of the ball is equal to angle of reflection.
  
### Scenario : Ball direction when it hits the paddle

  Given the game is in progress.
  
  When the ball hits one of the paddles.
  
  Then the angle of reflection can be more than or less than angle of incidence
       of the ball depending upon the speed and direction of the paddle.
