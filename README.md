# Hangman-game
# Hangman Game

A simple text-based Hangman game implemented in Python. The player guesses letters to uncover a hidden word before running out of attempts.

## Features
- Random word selection from a predefined list.
- Tracks correct and incorrect guesses.
- Displays remaining attempts.
- Shows missed letters.
- Allows replaying after game completion.

## Requirements
- Python 3.6 or later (Tested on Python 3.12.3)

## How to Play
1. Run the script using:
   ```bash
   python hangman.py
   ```
2. Guess one letter at a time.
3. If the letter is correct, it will be revealed in the word.
4. If incorrect, an attempt is deducted.
5. Win by guessing all letters before running out of attempts.
6. Lose if all attempts are used up.
7. Option to replay after each round.

## Installation & Setup
1. Install Python from [python.org](https://www.python.org/downloads/).
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hangman-game.git
   ```
3. Navigate to the project folder:
   ```bash
   cd hangman-game
   ```
4. Run the game:
   ```bash
   python hangman.py
   ```

## Example Gameplay
```
Welcome to Hangman! Guess the word letter by letter.
Word: _ _ _ _ _ _
Attempts left: 6
Enter a letter: a
Good job! That letter is in the word.
...
Congratulations! You guessed the word: python
```

## Contributions
Feel free to fork the project and submit pull requests for improvements!

## License
This project is open-source under the MIT License.

