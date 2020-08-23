# Play with a friend

## Features

Allows to play with friend.

### Scenario: Play multiplayer with friend

  Given the game is installed, opened and there is active
  internet connection.

  When the user selects play with friend.

  Then this module shows list of friends who are active and sends request
  to selected friend and waits for friend to accept the request. If accepted
  it starts the game. If not waits for certain amount of time, quits and shows
  previous page.
