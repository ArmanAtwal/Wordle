# Wordle Clone

# Description
Wordle Game is a simple word-guessing game developed using the Pygame library. The objective of the game is to guess a five-letter word within six attempts. The game features a responsive user interface with intuitive letter selection and deletion functionalities, providing an interactive and enjoyable gaming experience.

# Features
User Interface: The game provides a visually appealing and responsive user interface. Players can select letters from an on-screen keyboard and delete them if needed.
Word Checking Algorithm: An efficient word-checking algorithm is implemented to provide visual feedback to the player. Correctly guessed letters are highlighted in green, partially correct letters in yellow, and incorrect letters in grey.
Limited Attempts: Players have a total of six attempts to guess the word. The game keeps track of the attempts and displays the remaining attempts to the player.
End Game Conditions: The game will end either when the player correctly guesses the word or when they run out of attempts. In both cases, a message will be displayed indicating the outcome of the game.
Word Database: A collection of words is included in the game, and a random word is selected for each round of play. This ensures that the game offers a fresh challenge every time.

# Installation
1. Clone the repository:
git clone https:
2. Install the required dependencies. Make sure you have Python and Pygame installed on your system.
pip install pygame

# Usage
1. Navigate to the project directory:
cd wordle-game
2. Run the game:
python main.py
3. Guess the word by selecting letters from the on-screen keyboard. Use the backspace key to delete letters if needed.

The game will display visual feedback on the correctness of your guesses. Green letters indicate correct guesses, yellow letters indicate partially correct guesses, and grey letters indicate incorrect guesses.

Keep guessing until you either guess the word correctly or run out of attempts.

# Contributing
Contributions are welcome! If you have any ideas, bug fixes, or improvements, feel free to submit a pull request.

# License
This project is licensed under the MIT License.

# Acknowledgments
The Pygame library for providing a powerful framework for developing games.
The Wordle game concept, originally created by Josh Wardle.
