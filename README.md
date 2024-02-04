# blackjack
Here's a brief description of its functionality:

1. Card Deck Creation:
The card_deck function creates a deck of 52 cards, including different card types (Hearts, Spades, Clubs, Diamonds) and values (Ace, 2-10, Jack, Queen, King).

2. Card Value Determination:
The card_value function calculates the value of a given card based on user input. It handles special cases for face cards (J, Q, K) and allows the user to choose whether an Ace is worth 1 or 11.

3. Drawing Cards:
The new_card function randomly selects a card from the deck.
The remove_card function removes a specified card from the deck.

4. Gameplay Loop:
The code uses a while loop to allow the player to continue playing until they decide to exit.
It initializes the player's hand and the dealer's hand with two cards each.

5. Player's Turn:
The player is presented with their initial hand and total.
The player is then prompted to hit or stand in an attempt to get a hand value as close to 21 as possible without exceeding it.

6. Dealer's Turn:
After the player stands, the dealer reveals their face-down card.
The dealer must hit until their hand total is 17 or higher.

7. Outcome Determination:
The code checks for various win/lose conditions, including blackjack, busting (going over 21), and comparing total values between the player and dealer.

8. Play Again:
After each round, the player is asked if they want to continue or exit.

9. Exit and End:
The game continues until the player decides to exit, at which point a "Thank you for playing" message
