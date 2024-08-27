# Hangman Game
This is a simple command-line implementation of the classic Hangman game. The game randomly selects a word from a list of fruits, and the player has to guess the word one letter at a time. The player wins if they correctly guess all the letters in the word before running out of chances.

## How to Play
1. The game will select a random word from a predefined list of fruit names.
2. You will be shown the number of letters in the word as underscores (`_`), and your goal is to guess the word by suggesting letters one at a time.
3. Each correct letter you guess will be revealed in its correct position(s) in the word.
4. If you guess a letter that is not in the word, you lose one chance.
5. You have a limited number of chances to guess the word. The number of chances is equal to the length of the word plus two extra chances.
6. The game ends when:
   - You guess the entire word correctly, in which case you win.
   - You run out of chances without guessing the word, in which case you lose.
7. If you guess the same letter more than once, you will be prompted to try a different letter.

## How to Run the Game
1. Clone the repository or download the script file.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script using Python:

   ```bash
   python hangman_game.py
