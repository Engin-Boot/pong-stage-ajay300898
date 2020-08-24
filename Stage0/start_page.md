# Start Page

## Features

This is the first page when the game is opened and contains
links for different modules.

### Scenario : What does a user see when he opens the game

  Given the game is installed.
  
  When the game is opened.
  
  Then this module shows links to Profile, Settings, Play, Friends
  modules.

  
  ### Scenario : What happens when user clicks on one of the links

  Given the game is installed and the user is in start page.
  
  When the user clicks on one of the links.
  
  Then this module redirects user to appropriate module.
