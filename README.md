Rock Paper Scissors Game
A simple Rock Paper Scissors game implemented using HTML, CSS, and JavaScript. The game allows the player to compete against the computer and keeps track of the score over multiple rounds.

Features
Player can choose between Rock, Paper, or Scissors.
The computer randomly selects one of the three options.
The game calculates the winner of each round based on the standard Rock Paper Scissors rules.
Displays the current score for the player and the computer.
A reset button is provided to restart the game.
Instructions
Click on Rock, Paper, or Scissors to make your choice.
The game will display the result of the round (Win/Loss/Tie).
The game continues for 10 rounds (configurable).
The winner is determined after 10 rounds.
Click the Restart button to reset the game and start fresh.
Installation
Clone the repository or download the files.
Open the index.html file in a browser to start playing the game.
File Structure
bash
Copy
Edit
/rock-paper-scissors-game
    ├── index.html       # HTML file
    ├── rps.css          # CSS file for styling
    ├── rps.js           # JavaScript file with game logic
    ├── rock.jpeg        # Rock image
    ├── paper.jpeg       # Paper image
    └── scissor.jpeg     # Scissors image
Game Logic
Choices: The player and computer can choose Rock, Paper, or Scissors.
Winning conditions:
Rock beats Scissors.
Scissors beats Paper.
Paper beats Rock.
After each round, the game updates the score and checks if the maximum rounds have been played. If so, it ends the game and shows the winner.

License
This project is open-source and free to use. Feel free to make modifications to suit your needs.
