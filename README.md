# Hangman Game
Welcome to the Hangman game! This is a classic word-guessing game where you try to guess the letters in a hidden word before running out of attempts.

## Project Structure
hangman.py: Main game logic.
hangman_words.py: Contains the list of words to be used in the game.
hangman_art.py: Contains the ASCII art for the game logo and stages.
## How to Play
The game randomly selects a word from the word_list.
You have to guess the word by suggesting letters one at a time.
Each incorrect guess reduces your number of lives.
The game ends when you either guess the word correctly or run out of lives.
## TODOs
Update the word list to use the word_list from hangman_words.py.
Import the stages from hangman_art.py.
Import the logo from hangman_art.py and print it at the start of the game.
If the user has entered a letter they've already guessed, print the letter and let them know.
If the letter is not in the chosen_word, print out the letter and let them know it's not in the word.
