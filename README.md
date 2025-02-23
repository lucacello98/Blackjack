
Description:
A simple implementation of the classic Blackjack card game in Python. The game allows the user to play against the computer, where both the player and the computer are dealt cards, and the goal is to get a higher score without exceeding 21.

Features:
Card Dealing: Random cards are dealt from the deck.
User Interaction: The player can choose to "hit" (get another card) or "stand" (keep their current hand).
Computer Logic: The computer automatically draws cards if its score is below 17.
Game Outcome: The game compares the player's and the computer's score to determine the winner.
Blackjack: If the player or the computer gets a score of 21 with just two cards, they automatically win with a "Blackjack".

How It Works:
Card Dealing: Both the player and the computer are dealt two cards at the start of the game.
Player's Turn: The player is shown their current cards and the first card of the computer. The player can choose to "hit" to receive another card or "stand" to keep their current hand.
Computer's Turn: The computer draws cards until its score is 17 or higher.
Game Outcome: The scores are compared:
   - A score of 21 with two cards is a "Blackjack" and wins immediately.
   - If the player or computer goes over 21, they lose.
   - If neither exceeds 21, the higher score wins.



