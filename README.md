# Blackjack Game

This is a simple implementation of a Blackjack game using JavaScript. The game allows a player to draw cards and aims to reach a sum of 21 without exceeding it.

## How to Play

1. Open the `index.html` file in a web browser to start the game.

2. You'll see the player's name and the initial chip count displayed.

3. Click the "Start Game" button to begin a new round.

4. Two random cards will be drawn for the player, and their sum will be displayed.

5. You can choose to draw additional cards by clicking the "New Card" button as long as the total sum is less than or equal to 21.

6. If your card sum reaches 21, you win with Blackjack!

7. If your card sum exceeds 21, you lose and are out of the game.

## Rules

- Number cards are worth their face value (e.g., 2-10).
- Face cards (Jack, Queen, King) are worth 10.
- Aces are worth 11.

## Features

- Track your card total and game status in real-time.
- You can't draw cards once you've reached 21 or busted.

## Code Structure

- `player`: Contains player information (name and chips).
- `cards`: An array to store the player's cards.
- `sum`: The sum of the player's cards.
- `hasBlackJack`: Indicates if the player has Blackjack.
- `isAlive`: Indicates if the player is still in the game.
- `message`: Displays game messages.
- Functions like `getRandomCard()`, `startGame()`, `renderGame()`, and `newCard()` control the game logic.
- HTML elements are updated using `getElementById()` and `textContent`.

Feel free to explore and modify the code to add more features or customize the game further.

Have fun playing Blackjack!
