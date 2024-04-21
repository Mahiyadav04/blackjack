# blackjack
This code implements a simplified version of the game Blackjack. Here's a breakdown of how it works:

1. It defines a function `deal_card()` that randomly selects a card from a predefined list representing a deck of cards.

2. It defines a function `calculate_score(cards)` that takes a list of cards as input and calculates the total score. It handles the special case of an Ace, where its value can be either 1 or 11 depending on the situation.

3. The `compare(user_score, computer_score)` function determines the outcome of the game based on the scores of the player and the computer. It handles scenarios such as blackjack, bust (going over 21), and draws.

4. The `play_game()` function orchestrates the gameplay. It deals two cards to the player and the computer, then prompts the player to draw more cards or pass. It also manages the computer's decision-making process for drawing cards.

5. After each game, the player is asked if they want to play again. If they do, a new game starts.

Overall, this code provides a basic implementation of the Blackjack game, allowing users to play against a computer opponent.
