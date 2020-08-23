# Calculate ball speed

## Features

This module calculates ball speed.

### Scenario : Ball speed when it hits the side walls

  Given the game is in progress.
  
  When the ball hits one of the side walls.
  
  Then the speed of the ball remains same in x and y direction.
  
### Scenario : Ball speed when it hits the paddle

  Given the game is in progress.
  
  When the ball hits one of the paddles.
  
  Then the speed of the ball in x direction remains same but the
       the speed of the ball in y direction gets added or subtracted
       based on the speed and direction of the paddle.
