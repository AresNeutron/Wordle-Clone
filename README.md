# Wordle Clone - React Application

## Introduction

This project is a clone of the popular word-guessing game, **Wordle**. Built using React, it allows users to guess a 5-letter word within 6 attempts. The game provides feedback on each guess, helping players to discover the correct word.

## Features

- **Interactive UI**: The application includes an interactive board where players can input their guesses.
- **Keyboard Component**: A virtual keyboard is provided for users to input letters, mimicking the mobile experience.
- **Word Validation**: The game checks if the guessed word exists in the word set.
- **Game Over Conditions**: The game ends when the player guesses the word correctly or exhausts all attempts.
- **Word Set Generation**: Words are dynamically generated from a predefined set for each game.

Usage
Once the application is running, you can:

Start typing a 5-letter word using the provided virtual keyboard.
Press Enter to submit the word.
Use the Delete key to remove the last letter.
The game will provide feedback:
Green: Correct letter in the correct position.
Yellow: Correct letter in the wrong position.
Gray: Incorrect letter.
Game Context
The application uses React's Context API to manage the game state, including the board, current attempt, selected letters, and game over status.
