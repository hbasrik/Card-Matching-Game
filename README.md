# Card Matching Game

This is a simple **Card Matching Game** built using vanilla JavaScript. The objective of the game is to match all pairs of cards by flipping them over and finding the matching images. The game keeps track of the player's score and shuffles the cards after every game.

## Features

- **Flip to Match**: Players click on two cards to flip them. If the images on the two flipped cards match, the cards stay flipped. If not, the cards flip back after a short delay.
- **Score Tracking**: The player's score increases by 1 for every successful match.
- **Win Condition**: The game ends when the player matches all 8 pairs of cards.
- **Card Shuffling**: After each game, the cards are shuffled to provide a new challenge.

## How the Game Works

### Card Flipping

- The game consists of 16 cards (8 pairs of matching cards).
- Players can flip two cards at a time by clicking on them.
- If the images on the two flipped cards match, they remain flipped and cannot be clicked again.
- If the images do not match, the cards flip back after a brief animation.
  
### Score Tracking

- Each time the player makes a successful match, their score increases by 1.
- The score is displayed on the screen using the `scoreDisplay` element.

### Winning the Game

- The player wins the game when all 8 pairs of cards are matched.
- A congratulatory message is displayed, and the cards are reshuffled for a new game.

### Shuffling Cards

- The `shuffleCard()` function randomizes the card order at the start of the game and after a player wins.
- The cards are shuffled using an array of numbers representing the card pairs, which is then randomized and applied to the card images.


### Demo

https://github.com/user-attachments/assets/608f3b9a-cc72-46a4-bcbe-cf5cc5f119e6


