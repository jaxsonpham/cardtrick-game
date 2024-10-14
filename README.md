Overview
This project implements a card trick game using a deck of randomly generated cards. The game deals the cards into three columns, prompts the user to choose which column their card is in, and redeals the cards. After repeating this process three times, the program will reveal the secret card chosen by the user.

How to Play
Start the game: When you run the program, the deck is shuffled using a random number generator to ensure a new random deck each time.
Dealing the cards: The program will deal out the cards into three columns, row by row.
Select a column: After viewing the dealt cards, you will be prompted to choose the column that contains your secret card by inputting 0, 1, or 2.
Card pick up and redeal: The program picks up the cards in a specific order based on your selection: one remaining column, your selected column, and the final column.
Repeat the process: This process will repeat two more times, and the deck will be redealt each time.
Secret card revealed: After the third redeal, the program will deal the first 10 cards in the deck and reveal the 11th card as your secret card.
Program Features
Random Deck Generation: Each card in the deck is randomly assigned a rank and suit using rand() and srand(time(0)) to ensure randomness.
Card Formatting: The cards are displayed in the format <Rank> of <Suit> to maintain clarity and alignment.
Card Trick Logic: The user is prompted to select the column containing their card three times, and the program appropriately redeals the deck before revealing the secret card.
Deck Display Option: The user is prompted at the beginning of the game if they wish to print the entire deck before starting the card trick.
