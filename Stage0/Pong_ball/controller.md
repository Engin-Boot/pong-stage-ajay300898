# Controller

## Features

  This module moniters the position of the ball and
  triggers appropriate modules.
  
### Scenario : Ball hits side wall or paddle

  Given the game is in progress.
  
  When the ball hits the side wall or paddle (by getting information
      from the ball_position module).
      
  Then this module calls ball direction and ball speed modules.
  
### Scenario : Ball hits wall behind the paddle

  Given the game is in progress.
  
  When the ball hits the wall behind the paddle (by getting information
      from the ball_position module).
      
  Then this module pauses the game and calls update score module.
