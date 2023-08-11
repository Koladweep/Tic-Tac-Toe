# Tic-Tac-Toe
A game made in the process of learning AI the fun way.
Tic-Tac-Toe Documentation  /\* Add your styles here \*/ body { font-family: Arial, sans-serif; } .documentation-header { text-align: center; font-size: 2em; margin-bottom: 1em; visibility:hidden; } .container { max-width: 800px; margin: 0 auto; padding: 1em; } .content { line-height: 1.5; } .back-button { margin-top: 2em; text-align: center; } .buttons{padding:10px; position :relative; bottom :4%; right:-70%; }

This document provides an overview of the Tic-Tac-Toe game, including its implementation, features, and behavior.

Tic-Tac-Toe Game Documentation
==============================

*   Overview
------------

Tic-Tac-Toe is a simple Player Vs A.I. game where both take turns placing their symbol (Player is ❌ and AI is ⭕) on a 3x3 grid. The player who succeeds in placing three of their symbols in a row, column, or diagonal wins the game.

*   Implementation
------------------

The game is implemented using HTML, CSS, and JavaScript. The HTML code defines the structure of the page, including the game board, buttons for resetting the game and changing difficulty levels, and elements for displaying messages to the player. The CSS code defines the styles for these elements, such as their size, position, and color. The JavaScript code defines the game's logic and behavior, such as how to handle player moves, check for a win or draw, and reset the game.

*   Features
------------

One of the key features of this game is its AI opponent, which uses different heuristics and algorithms to determine its moves depending on the selected difficulty level.

1.  At the "easy" level, the AI chooses a random available cell.
2.  At the "medium" level, it tries to choose the center or a corner cell if available(This increases the probability of winning.
3.  At the "tough" level, it uses a simplified version of the minimax algorithm to simulate all possible moves and outcomes and choose a move that maximizes its chances of winning while minimizing its chances of losing by **even trying to block the Player from winning.😃**
4.  The game cannot start without a toss and you cannot backout once it begins 😈🔱.

*   Behavior
------------

The game's behavior is controlled by several variables and functions defined in the JavaScript code. When the user clicks on a cell in the game board or on one of the buttons (e.g., reset or toss), an event listener function is called that updates the game state and HTML elements accordingly. For example, when a player clicks on an empty cell in the game board, the \`playerMove\` function is called. This function updates the content of the clicked cell to show the current player's symbol (always "X") and checks if the current player has won or if there is a tie. If neither of these conditions is met, it switches to the other player (the computer) and calls the \`computerMove\` function. **The \`computerMove\` function uses different heuristics to determine its move depending on the selected difficulty level (as described above). Once it has chosen a move, it updates the corresponding cell in the game board with its symbol (always "O") and checks if it has won or if there is a tie. Overall, the game's behavior is determined by a combination of user interactions (e.g., clicking on cells or buttons) and internal logic (e.g., checking for wins or ties) implemented in JavaScript.**

11.  credits
    -------
    

**Tailored with the help of**

***   **ChatGPT 3.5:**The friendly developer copilot and the interactive developer book that will finally make you feel"I'ts time I read documentation. It helps when you get to see before you read.**2.  **BinG!**:All the javascript and logic was developed by the Bing Chatbot that is built on ChatGPT-4
3.  **Mozilla developers network:**
Helped me with the HTML, CSS, colors(learning) and project ideation(I'm now learning to do this before getting into the tech). MDN Got me started with web development
4. The ascii Art(removed) is generated with the help of(https://ascii-generator.site/)
5. This documentation was rendered in Markdown with the help of (https://codebeautify.org/).
