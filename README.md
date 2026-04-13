# Ping_Pong-HTML

Ultimate Pong is a browser-based arcade game built with HTML, CSS, and JavaScript. The project delivers an enhanced Pong experience with responsive canvas gameplay, AI opponent difficulty, power-ups, scoring, and local high score persistence.

## Features

- Responsive `canvas` game area that adapts to window size
- Player paddle controlled by mouse or touch drag
- Computer AI opponent with selectable difficulty levels
- Ball speed adjustments and automatic acceleration after paddle hits
- Randomly spawning power-ups: speed boost, slow effect, and bigger paddle
- Advanced options: ball size selector, AI behavior modes, power-up toggle, sound toggle, and trail effects
- Sound effects for ball hits and scoring
- Score display for player, computer, and persistent high score saved in `localStorage`
- Pause and reset buttons for quick game control

## How to Run

1. Open the project folder in your editor.
2. Start a simple local server from the project directory:

```bash
cd /workspaces/Ping_Pong-HTML
python3 -m http.server 8000
```

3. Open your browser and go to:

```text
http://localhost:8000
```

4. The game loads from `index.HTML`.

## Controls

- Move the mouse over the canvas to control the player paddle.
- On touch devices, drag your finger on the canvas.
- Use the Speed slider to adjust the ball movement multiplier.
- Use the Difficulty selector to change the AI paddle speed.
- Select ball size from the advanced panel to switch between small, medium, and large mode.
- Choose AI mode to change computer opponent behavior: Normal, Predictive, or Reactive.
- Use the advanced panel to toggle power-ups, sound, and trail effects.
- Click Pause to freeze the game.
- Click Reset to restart scores and reset ball/paddle state.

## Notes

- The game ends when either player reaches a winning score of 10.
- High score is stored locally in your browser and shown on the screen.
- If the browser blocks audio, allow sound playback for the hit and score effects.

## Files

- `index.HTML` — main game file with embedded styles and JavaScript.
