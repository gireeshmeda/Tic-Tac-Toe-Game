HTML Structure - Creates a 3x3 grid board using buttons inside a div container.
CSS Styling - Uses grid layout for the board, hover effects, and color-coded X (blue) and O (red).
Game State - Tracks currentPlayer, gameState (array), and gameActive (boolean).
Dynamic Board - Generates 9 cells via JavaScript loop and appends them to the board.
Click Handling - handleClick updates cell content and checks for a winner/draw.
Win Logic - Checks 8 possible win patterns using winPatterns array.
Winner Highlight - Adds winner class to winning cells (green background).
Draw Detection - Triggers if all cells are filled (!gameState.includes('')).
Player Switch - Toggles between X and O after each valid move.
Reset Function - Clears the board, resets state, and restarts the game.
