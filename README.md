# Stone_Paper_Scisor_SimpleProjectPython

The import random statement is used to import the random module. The random module provides functions that allow us to work with random numbers and make random choices.

In this specific code, the random module is used to randomly select an option for the computer's choice in the rock-paper-scissors game. By importing the random module, we gain access to the choice() function, which is used to select a random element from a given sequence.

The line computer_input = random.choice(possible_options) utilizes the random.choice() function to randomly select an option ('s', 'p', or 'c') from the possible_options list and assigns it to the variable computer_input. This random selection simulates the computer's choice in the game.

**CODE**


The code imports the random module, which allows us to generate random numbers and make random choices.

The user is prompted to enter their choice (either 'S', 'P', or 'C').

The computer makes a random choice among 's', 'p', or 'c', representing "scissors", "paper", and "rock" respectively.

The computer's choice is printed to the console.

The code checks the user's input against the computer's input to determine the outcome of the game.

If the user and computer have the same choice, it's a tie and "This is a Tie" is printed.

If the user's input is 's' (scissors), and the computer's input is 'c' (rock), the user wins and "YOU ARE THE WINNER!!!" is printed. Otherwise, if the computer's input is 'p' (paper), the computer wins and "Computer is the Winner" is printed.

If the user's input is 'p' (paper), and the computer's input is 'c' (rock), the computer wins and "Computer is the Winner" is printed. Otherwise, if the computer's input is 's' (scissors), the user wins and "YOU ARE THE WINNER!!!" is printed.

If the user's input is 'c' (rock), and the computer's input is 's' (scissors), the computer wins and "Computer is the Winner" is printed. Otherwise, if the computer's input is 'p' (paper), the user wins and "YOU ARE THE WINNER!!!" is printed.
