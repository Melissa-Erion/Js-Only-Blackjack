# Js-Only-Blackjack
Blackjack Javascript Only

Blackjack Game

This is a simple implementation of the classic card game Blackjack (also known as 21) using JavaScript. In this game, you play against the computer (the dealer) and aim to get a hand value as close to 21 as possible without going over. This README provides an overview of the game and its functionality.
How to Play

    When you start the game, you will be prompted to choose your initial bet size. The minimum bet is $10, and it must be in increments of $10. The game will also display your current balance, which starts at $100.

    After placing your bet, the game will start a new round. You and the dealer will each receive two cards from a standard deck of cards.

    You will see one of the dealer's cards (the "upcard") and both of your cards.

    You have two options during your turn:
        Hit: You can choose to take another card from the deck to increase your hand value. Continue hitting until you are satisfied with your hand or until your hand value exceeds 21 (resulting in a loss).
        Stand: If you believe your current hand is strong enough to beat the dealer or if you want to minimize the risk of going over 21, you can choose to stand.

    After you stand, the dealer will reveal their facedown card, and the game will determine the winner based on the hand values. The dealer will follow a set of rules to determine when to hit or stand.

    The game will display the results of the round, including whether you won, lost, or had a push (tie). Your balance will be updated accordingly.

    You will have the option to start a new round with a different bet size or cash out and end the game.

Game Logic

The game logic is implemented using JavaScript and consists of several functions and properties:

    createDeck: Generates a deck of playing cards, represented as objects with properties for face value and suit.
    bet: Initiates the game by allowing you to place a bet and configure the game for a new round.
    configureForNewRound: Resets game properties for a new round.
    getHandValue: Calculates the total value of a hand, considering special rules for Aces.
    dealCard: Randomly selects and deals a card from the deck to a hand.
    newRoundOrNot: Determines whether you have enough balance to start a new round or cash out.
    getCardsInString: Converts card objects into a user-friendly string format.
    currentRoundEnds: Displays a summary of the round's results and updates the balance.
    playerTurn: Handles your turn, allowing you to hit or stand until the turn ends.
    dealerTurn: Simulates the dealer's turn according to predefined rules.
    startRound: Initiates a new round by dealing cards and handling the player's and dealer's turns.

Usage

To play the game, open the HTML file in a web browser. Follow the on-screen instructions to place bets, make choices during your turn, and interact with the game. Enjoy your Blackjack experience!

Please note that this is a simplified implementation of Blackjack and does not include advanced features like splitting or doubling down.
