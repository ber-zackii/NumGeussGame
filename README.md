# Number Guessing Game

## Overview

This is a simple Number Guessing Game written in C. The program generates a random number between 1 and 100 and prompts the user to guess the number. It provides feedback if the guess is too high or too low and counts the number of attempts until the user correctly guesses the number.

## Features

- Generates a random number between 1 and 100.
- Prompts the user to guess the number.
- Provides feedback if the guess is too high or too low.
- Displays the number of attempts once the user guesses correctly.


## Code Explanation

- **Include Directives**: The code includes standard libraries for input/output operations (`stdio.h`), memory allocation (`stdlib.h`), and time functions (`time.h`).

- **Random Number Generation**: `srand(time(0))` seeds the random number generator with the current time, ensuring different sequences of random numbers each time the program is run. `number = rand() % 100 + 1` generates a random number between 1 and 100.

- **User Input**: The program uses `scanf` to get user input for guesses.

- **Game Loop**: A `do-while` loop continues to prompt the user for guesses until the correct number is guessed. It increments the attempt count and provides feedback based on whether the guess is too high or too low.
