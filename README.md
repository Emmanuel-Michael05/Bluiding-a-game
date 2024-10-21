# Guessing Game Console Application

## Description
This project is a simple console-based guessing game where the user has to guess a secret word within a limited number of attempts. The game allows the user to input guesses, and if the correct word is guessed within the allowed attempts, the user wins. Otherwise, the user loses.

## Features
- The user has 3 attempts to guess the secret word.
- After 3 incorrect attempts, the game ends with a "You Lose!" message.
- If the user guesses the secret word correctly within the limit, the game ends with a "You Win!" message.

## How to Play
1. The game starts by prompting the user to guess the secret word.
2. The player has a maximum of 3 guesses.
3. If the player guesses the correct word, they win. If they run out of guesses, they lose.

## How to Run
1. Clone or download this repository.
2. Open the project in Visual Studio Code or any C# IDE.
3. Run the application by pressing `F5` or using the terminal/console to execute:
   ```bash
   dotnet run
Follow the prompts to enter your guesses.
## Example Output
Enter guess: dog
Enter guess: cat
Enter guess: parrot
You Lose!
Or
Enter guess: hamster
You Win!

## Files
Program.cs: Contains the logic of the game, including the guessing mechanism and win/lose conditions.

## Author
Emmanuel Michael Ikechukwu

This `README.md` covers the basic instructions on how to play the game, run the project, and provides example output for better clarity. You can modify it to fit any further features or changes in your project.
