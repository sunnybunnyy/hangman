# Hangman Game with PySimpleGUI

## Project Overview

This project involves creating a graphical user interface (GUI) for the classic hangman game using the PySimpleGUI library. The game logic will be implemented in Python and connected to the GUI, allowing players to enjoy a visually engaging version of hangman.

## Introduction

Hangman is a classic word-guessing game where players try to guess a hidden word by suggesting letters. This project aims to create a GUI version of hangman using PySimpleGUI, making the game more interactive and visually appealing.

## Game Description

### Game Setup
- **Players**: Two or more players. In this version, the computer will be the selecting player, and one human will be the guessing player.
- **Word Selection**: The computer selects a word, represented by underscores for each letter.

### Guessing
- The player guesses letters one at a time.
- Correct guesses reveal the letter in the word.
- Incorrect guesses add a part to the hangman drawing (head, torso, arms, legs).

### Winning Conditions
- The player wins if they guess the word correctly.
- The computer wins if the hangman drawing is completed after six incorrect guesses.

## Features

- **Interactive GUI**: Built using PySimpleGUI, the interface is user-friendly and visually appealing.
- **Game Logic**: Handles word selection, letter guessing, and hangman drawing.
- **Feedback**: Provides immediate feedback on guessed letters and updates the display accordingly.
- **Game Outcome**: Manages game end conditions and offers options to restart or quit.

## Requirements

- Python 3.x
- PySimpleGUI

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hangman-pysimplegui.git

2. Change to the project directory:
   ```sh
   cd hangman-pysimplegui
   
3. Install the required dependencies:
   ```sh
   pip install PySimpleGUI
   
## Usage
1. Run the game:
   ```sh
   python hangman.py
   
2. Use the GUI to guess letters and try to complete the word before the hangman is fully drawn.

## Future Enhancements
- **Multiplayer Support:** Allow multiple human players to take turns guessing.
- **Difficulty Levels:** Introduce different difficulty levels with varying word lengths and guessing attempts.
- **Custom Word Lists:** Enable players to provide their own list of words for the game.
