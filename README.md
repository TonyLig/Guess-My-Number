# Guess-My-Number

This is a simple number guessing game implemented in JavaScript. The game generates a random number between 1 and 20, and the player needs to guess the correct number within a limited number of attempts.

![Number Guessing Game](GuessMYNumber.png)

Check out the live demo [here][Try the Game].

## Features

- Generates a random number between 1 and 20 for the player to guess.
- Keeps track of the player's score, which starts at 20 and decreases with each incorrect guess.
- Tracks the highscore, which is the highest score achieved by the player.
- Provides feedback to the player on whether the guess is too high or too low.
- Changes the background color and display style when the player guesses the correct number.
- Allows the player to reset the game and start a new round.

## Getting Started

1. Clone the repository or download the code.
2. Open the `index.html` file in a web browser.
3. Start guessing the number and try to beat the highscore!

## Code Explanation

- The JavaScript code is written in strict mode for safer coding practices.
- The game generates a random number using `Math.random()` and stores it in `secretNumber`.
- The `displayMessage` function is used to update the message displayed to the player.
- Event listeners are added to the "Check" and "Again" buttons to handle user interactions.
- When the "Check" button is clicked, the player's guess is retrieved and compared to the `secretNumber`.
- If the guess is correct, the player wins and the highscore is updated if necessary.
- If the guess is incorrect, the score is decreased, and appropriate feedback is displayed.
- When the "Again" button is clicked, the game is reset to its initial state.

[Try the Game]: https://tonylig.github.io/Guess-My-Number/
