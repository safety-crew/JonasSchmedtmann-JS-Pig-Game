# Pig Game

A simple two-player dice game built with HTML, CSS, and JavaScript.

## Description

Pig Game is a classic dice game where two players take turns rolling a single die. Players accumulate points with each roll but must decide when to "hold" their score or risk losing their accumulated points by rolling a 1.

## Game Rules

1. The game has 2 players, taking turns.
2. In each turn, a player rolls a dice as many times as they wish.
3. Each roll gets added to their CURRENT score.
4. BUT, if the player rolls a 1, their CURRENT score is lost and it becomes the next player's turn.
5. The player can choose to 'Hold', which means that their CURRENT score gets added to their TOTAL score. After that, it's the next player's turn.
6. The first player to reach 100 points or more wins the game.

## Features

- Clean and responsive user interface
- Dynamic dice roll animation
- Score tracking for both players
- Current turn indicator
- Win state detection
- Reset game functionality

## Project Structure

- `index.html` - The main structure of the game
- `style.css` - Styling and layout of the game
- `script.js` - Game logic and functionality
- `images/` - Contains dice images (dice-1.png through dice-6.png)

## Technical Implementation

### HTML
- Structured with semantic sections for each player
- Score displays for both current and total scores
- Control buttons for game actions

### CSS
- Modern design with gradient background
- Responsive layout using Flexbox
- Visual feedback for active player and winner
- Smooth transitions between states
- Backdrop filter for glass-like effect

### JavaScript
- Event-driven architecture
- Game state management
- Random dice generation
- Player switching logic
- Score calculation and validation

## How to Play

1. Open `index.html` in a web browser
2. Player 1 starts by clicking the "Roll dice" button
3. Continue rolling or click "Hold" to secure your points
4. Try to reach 100 points before your opponent
5. Click "New game" to start over

## Setup

No installation required. Simply download all files and open `index.html` in a web browser.

## Requirements

Any modern web browser with JavaScript enabled.

## Future Improvements

- Add customizable winning score
- Implement player name customization
- Add sound effects
- Create single-player mode against computer AI
- Add local storage to save game state
