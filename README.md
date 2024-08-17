# Hangman Game

This Python script is a text-based Hangman game that challenges players to guess a hidden word within a limited number of tries. The game includes fun ASCII art and animations to enhance the user experience.

## Features

- **Custom Word List**: Users can input the path to a file containing a list of words, from which a random word will be selected for the game.
- **ASCII Art**: The game includes multiple stages of a Hangman displayed in ASCII art, making the gameplay more engaging.
- **Interactive Gameplay**: The script reacts to user input with different ASCII art displays depending on the correctness of the guesses.
- **Multiple Rounds**: Players have the option to play multiple rounds, with the ability to reuse the previous word list or provide a new one.

## How to Play

1. **Start the Game**: Run the script to begin the game.
2. **Input Word List**: Provide the path to a text file containing the list of words for the game. The script will randomly choose a word from this file.
3. **Guess the Word**: Type a letter to guess parts of the hidden word. You have six attempts to guess the word correctly before the game ends.
4. **Win or Lose**: If you guess the word within the allowed attempts, you win. If not, the game is over, and you can choose to play again.

## Getting Started

### Prerequisites

- Python 3.x
- A text file containing a list of words for the game.

### Running the Game

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/hangman-game.git
    cd hangman-game
    ```

2. Run the game:
    ```bash
    python hangman.py
    ```

3. Follow the on-screen instructions to play the game.

## Contributing

Feel free to submit issues or pull requests if you want to improve the game or add new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
