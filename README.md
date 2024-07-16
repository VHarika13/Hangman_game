# Hangman using python

This is a simple Hangman game implemented in Python. The game randomly selects a word from a predefined list, and the player must guess letters to uncover the word before running out of lives.

## Features

Random selection of a word from a predefined list.
Visual representation of the Hangman as ASCII art.
Display of the current state of the word with blanks for unguessed letters.
Player input for guessing letters.
Feedback on correct and incorrect guesses.
Game over conditions for winning or losing.

## Modules
 1. hangman_words.py:
 This module contains a list of words (word_list) used by the game. It imports word_list into the main Hangman script for word selection.

 2. hangman_art.py:
 This module contains ASCII art representations of the Hangman and stages of the Hangman as the player makes incorrect guesses (stages). It imports these into the main Hangman script for visual representation.
