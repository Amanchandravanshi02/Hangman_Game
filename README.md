# Hangman Game

Welcome to the Hangman game! This is a simple console-based implementation of the classic word-guessing game. 

## How to Play

1. The game will randomly choose a word from a predefined list.
2. You have 10 attempts to guess the word by suggesting letters one at a time.
3. Each incorrect guess will reduce your remaining attempts and bring the hangman closer to being fully drawn.
4. If you guess all the letters in the word before running out of attempts, you win!
5. If you run out of attempts before guessing the word, you lose and the hangman will be fully drawn.

## Game Rules

- Only valid alphabetical characters (a-z) are accepted as input.
- Repeating a previously guessed letter will notify you without penalizing your remaining attempts.
- Each incorrect guess will result in drawing another part of the hangman.

## Getting Started

1. Ensure you have Python installed on your machine.
2. Copy the `hangman.py` script from this repository.
3. Open a terminal or command prompt and navigate to the directory containing `hangman.py`.
4. Run the script using the following command:

   ```sh
   python hangman.py
