# Game Brief — Alien Tic-Tac-Toe

## Game
Alien Tic-Tac-Toe (the course's featured game).

## Player goal
Get three X marks in a line on a 3×3 board. You claim a square by winning a short battle against an alien.

## Smallest first version
One page (`index.html`) with: instructions and a Start button, a 3×3 board, a battle panel for the chosen square, an end-of-game message, Play again, and Restart game. No timers, sounds, images or extra effects.

## How a turn works
1. Choose an empty square. The board locks.
2. The alien attacks: Laser, then Shield, then Claw (same order every battle).
3. Pick the counter: Laser → **Shield**, Shield → **Blast**, Claw → **Dodge**.
   - Right counter: alien loses 1 health. Wrong: you lose 1 health.
4. Both sides start at 2 health. First to 0 loses the battle (at most 3 exchanges).
5. Win the battle → X in the square. Lose → O in the square.

## Win, lose, draw
- Three X in a line: **You won**.
- Three O in a line: **The aliens won**.
- Full board, no line: **Draw**.

## Controls
Mouse, touch, or keyboard (Tab, then Enter or Space). Buttons: Start, Shield, Blast, Dodge, Next exchange, Return to board, Play again, Restart game, Help.

## Completed round and replay
A round is complete when the board is won, lost or drawn. Play again clears the board. Restart game clears everything at any time; an abandoned battle gives no mark.

## Out of scope (version one)
Random alien moves, timers, sound, animation, images, scores across games, accounts, multiplayer.

## Where it lives
- Folder: `my-first-game/` in https://github.com/Me-Lost/AllThingsOpenVibeCoding
- Vercel project: to be created at the publish step

## Checks that prove it works
The course test checklist: the five battle sequences, all eight lines, the full-board draw, the last-cell win, Play again, Restart during battle, Help during battle, keyboard and phone play. Results go in `game-test-report.md`.
