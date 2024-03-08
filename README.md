Number Guessing Game Documentation
Overview
NumberGuessingGame is a simple console-based game implemented in Java. The objective of the game is for the player to guess a randomly selected number between a specified range within a limited number of attempts.

Features
Random Number Generation: The game selects a random number between a specified lower and upper bound.
User Interaction: The game prompts the player to enter their guess and provides feedback based on the correctness of the guess.
Limited Attempts: The player has a limited number of attempts to guess the correct number.
Feedback: The game provides feedback to the player after each guess, indicating whether the guess was too low, too high, or correct.
Game Outcome: The game ends either when the player guesses the correct number or when they exceed the maximum number of attempts.
Classes
NumberGuessingGame
Main class: Contains the main method to start the game.
Methods:
main(String[] args): Entry point of the game program.
Usage
Run the Program: Execute the NumberGuessingGame class to start the game.
Guess the Number: Enter your guess when prompted. The game will indicate whether the guess is too low, too high, or correct.
Repeat or End: Continue guessing until you guess the correct number or reach the maximum number of attempts.
Examples
Random Number: The game selects a random number between 1 and 100 for the player to guess.
Guess Feedback: After each guess, the game provides feedback indicating whether the guess is too low, too high, or correct.
Game End: The game ends either when the player guesses the correct number or reaches the maximum number of attempts.
Dependencies
java.util.Random: Used for generating random numbers.
java.util.Scanner: Used for user input.
Notes
Game Customization: The lower and upper bounds of the range, as well as the maximum number of attempts, can be adjusted as needed.
Error Handling: The program assumes valid input from the user and does not include extensive error handling for invalid input.
Game Logic: The game uses a simple linear search algorithm to compare the player's guess with the target number.
