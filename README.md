Sure, let's design a Flask application for playing Mahjong with virtual players:

## HTML Files:

### `index.html`:
- This is the main HTML page for the application.
- It will contain the game board, player information, and any necessary controls for gameplay.
- It will also include scripts to handle game logic and user interactions.

### `login.html`:
- This HTML page is used for user login purposes.
- It can be used to select a username and connect to the server.

### `game.html`:
- This HTML page will display the actual Mahjong game.
- It will include a virtual representation of the game board, tiles, and player information.

### `results.html`:
- This HTML page will display the results of a game.
- It will show the winning player, scores, and any relevant statistics.



## Routes:

### `/@`:
- This route will serve the `index.html` page, acting as the application's homepage.
- It will be the default route for the application.

### `/@login`:
- This route will serve the `login.html` page, allowing players to select a username and connect to the server.

### `/@game`:
- This route will serve the `game.html` page, starting a new game of Mahjong with virtual players.

### `/@results`:
- This route will serve the `results.html` page, displaying the results of a completed game.

### `/@move`:
- This route will handle player moves during the game.
- It will receive a player's move (e.g., picking a tile, discarding a tile, etc.) and update the game state accordingly.

### `/@status`:
- This route will provide information about the current game state.
- It can be used by clients to retrieve the game board, player information, and other relevant data.

### `/@chat`:
- This route will enable chat functionality between players during the game.
- It will allow players to send messages to each other, fostering a more interactive and social gaming experience.

This Flask application design provides a basic structure for a Mahjong game with virtual players. Depending on the specific requirements and features desired, additional HTML files, routes, and functionalities can be incorporated to enhance the application's capabilities.