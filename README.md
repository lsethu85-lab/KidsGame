# MN bro's Gaming Dashboard

A kid-friendly, standalone browser gaming dashboard created as a single `index.html` file. It is designed for easy hosting on GitHub Pages and does not require React, Node.js, npm, external APIs, or downloadable sound files.

## Powered By

**Powered by Sethu**

## Project Overview

MN bro's Gaming Dashboard includes a collection of simple games for kids:

- Chess: Human vs Computer
- Memory Match
- Tic-Tac-Toe Puzzle
- Car Race Game
- Built-in sound effects
- Sound On / Sound Off toggle
- Mobile-friendly controls
- GitHub Pages-ready single-page setup

The project is intentionally simple so kids can play safely and parents can host it easily.

## Main File

The complete app is contained in:

```text
index.html
```

You only need this one file to run or host the dashboard.

## Features

### 1. Chess: Human vs Computer

- Player uses white pieces.
- Computer uses black pieces.
- Includes three difficulty levels:
  - **Easy**: computer picks random moves.
  - **Medium**: computer prefers stronger captures and better moves.
  - **Hard**: computer evaluates captures, center control, and risky replies.
- Simplified kid-friendly chess movement.
- Pawns can promote to queens.

> Note: This is a simplified learning version of chess. Castling, en passant, and full check/checkmate validation are not included.

### 2. Memory Match

- Flip cards to find matching animal pairs.
- Tracks number of moves.
- Plays sounds when cards flip and when matches are found.

### 3. Tic-Tac-Toe Puzzle

- Classic 2-player X and O puzzle.
- Detects winner or draw.
- Plays a winning sound.

### 4. Car Race

- Dodge road blocks.
- Use keyboard arrow keys or on-screen buttons.
- Tracks score.
- Plays movement and crash sounds.

### 5. Sound Effects

The dashboard uses the browser Web Audio API to generate sound effects directly in the browser.

No `.mp3`, `.wav`, or external audio files are required.

Sound effects are included for:

- Button clicks
- Chess moves
- Chess captures
- Game wins
- Memory card flips
- Memory matches
- Car movement
- Car crash

Users can enable or disable sound with the **Sound On / Sound Off** button.

## How To Run Locally

1. Download the `index.html` file.
2. Open it directly in a web browser.
3. Start playing.

No installation is required.

## How To Use With GitHub Pages

### Step 1: Create a GitHub Repository

Create a new GitHub repository, for example:

```text
mn-bros-gaming-dashboard
```

### Step 2: Upload Files

Upload these files to the repository:

```text
index.html
README.md
```

### Step 3: Enable GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Save the settings.

### Step 4: Open Your Website

GitHub will provide a Pages URL similar to:

```text
https://your-username.github.io/mn-bros-gaming-dashboard/
```

Open the URL to play the dashboard online.

## Recommended Repository Structure

```text
mn-bros-gaming-dashboard/
├── index.html
└── README.md
```

## Customization Ideas

You can improve the dashboard later by adding:

- Local high score history
- Parent timer controls
- More puzzle games
- Better chess engine rules
- Achievement badges
- Player profile selection
- Background music toggle
- Dark mode
- More car race levels

## Browser Compatibility

The dashboard should work in modern browsers such as:

- Microsoft Edge
- Google Chrome
- Mozilla Firefox
- Safari

For best sound support, use a modern desktop or mobile browser.

## Safety Notes

This project is designed to be kid-friendly:

- No login required
- No ads
- No chat system
- No external API calls
- No tracking code
- No online multiplayer

## License

You may use, edit, and share this project for personal and educational use.

## Credits

Created for MN bro's Gaming Dashboard.

**Powered by Sethu**
