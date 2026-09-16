# 🪨📄✂️ Rock Paper Scissors

A classic Rock, Paper, Scissors game built with vanilla JavaScript, HTML, and CSS — play against the computer with persistent score tracking and an animated win screen.

**🎮 [Live Demo](https://hasa24.github.io/ROCK-PAPER-SCISSORS/)**


## Features

- 🖱️ Simple click-to-play interface — no drag or typing needed
- 🧠 Randomized computer opponent logic
- 📊 Score tracking for both player and computer, persisted across sessions via `localStorage`
- 🤝 Automatic tie-handling with a replay prompt
- 🏆 Animated "You Won" celebration screen with trophy and stars
- 📖 In-game rules modal for quick reference
- 🎨 Custom UI with hover effects and smooth transitions — no CSS frameworks used

## Tech Stack

- **HTML5** — page structure
- **CSS3** — styling, animations, and layout (flexbox/grid, no frameworks)
- **Vanilla JavaScript** — game logic, DOM manipulation, and `localStorage` persistence

No external libraries or build tools — everything is hand-written from scratch.

## How to Run Locally

1. Clone the repository:
```bash
   git clone https://github.com/Hasa24/ROCK-PAPER-SCISSORS.git

```
2. Navigate into the project folder:
```bash
   cd ROCK-PAPER-SCISSORS
```
3. Open `index.html` directly in your browser, or serve it locally:
```bash
   npx serve .
```

## How to Play

1. Click Rock, Paper, or Scissors to make your move.
2. The computer picks randomly at the same time.
3. The result (win, lose, or tie) is shown instantly, along with both picks.
4. On a tie, hit **Replay** to try again immediately.
5. On a win or loss, hit **Play Again** to reset the board — scores persist until you clear your browser storage.
6. Win the round to see the celebration screen 🎉

## Project Structure

ROCK-PAPER-SCISSORS/
├── image/ # Game assets (rock, paper, scissor icons, trophy, stars)
├── index.html # Markup and game structure
├── index.js # Game logic and DOM interactions
└── style.css # Styling and animations


## Future Improvements

- Responsive layout for mobile devices
- Sound effects on win/lose/tie
- Best-of-N match mode
- Reset score button

---
