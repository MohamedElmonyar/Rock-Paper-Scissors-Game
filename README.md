# Rock, Paper, Scissors Game

## Introduction:
This is a classic game where the player competes against the computer. In each round, the player selects either Rock, Paper, or Scissors, while the computer randomly selects one of them. The winner is determined based on the following rules:
- Rock beats Scissors.
- Scissors beats Paper.
- Paper beats Rock.
- If both players choose the same option, it's a draw.

## Main Components of the Project:
1. **Enum `enGameChoice`**:
   Contains three options: Rock (1), Paper (2), Scissors (3).

2. **Enum `enWinner`**:
   Defines the winner of each round: Player1 (1), Computer (2), or Draw (3).

3. **Struct `stRoundInfo`**:
   Stores information about the current round, such as the round number, Player1's choice, the Computer's choice, the winner of the round, and the name of the winner.

4. **Struct `stGameResults`**:
   Stores the overall game results, including the number of rounds played, Player1's wins, Computer's wins, draw times, the game's winner, and the winner's name.

5. **Function `RandomNumber`**:
   Generates a random number between two given values.

6. **Function `GetComputerChoice`**:
   Randomly selects the computer's choice from the three options (Rock, Paper, Scissors).

7. **Function `WhoWonTheRound`**:
   Determines the winner of the round based on the choices of Player1 and the Computer.

8. **Function `WhoWonTheGame`**:
   Determines the overall winner of the game based on the number of wins for Player1 and the Computer.

9. **Function `ChoiceName`**:
   Returns the name of the choice based on the number (1 for Rock, 2 for Paper, 3 for Scissors).

10. **Function `WinnerName`**:
   Returns the name of the winner based on the result (Player1, Computer, or Draw).

11. **Function `ReadPlayer1Choice`**:
   Prompts Player1 to select one of the choices (Rock, Paper, or Scissors) by entering a number between 1 and 3.

12. **Function `PrintRoundResults`**:
   Displays the results of the current round.

13. **Function `PlayGame`**:
   Runs the game for a specified number of rounds and displays the results after each round, then determines the winner of the game.

14. **Function `StartGame`**:
   Starts the game and allows the player to play again after finishing the game.

## How to Use:
1. Run the program.
2. Choose the number of rounds you want to play.
3. In each round, select either Rock (1), Paper (2), or Scissors (3) when prompted.
4. Results for each round will be displayed, and the overall winner will be announced at the end.
5. After the game ends, you can choose whether to play again or exit the game.

## Sample Output:
