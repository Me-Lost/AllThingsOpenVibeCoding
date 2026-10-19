# Game Test Report — Alien Tic-Tac-Toe

Tested 2026-10-19 in a headless Chrome browser (desktop and phone-sized screen), using the course test checklist.

| Check | Result |
|---|---|
| Nothing happens before Start | Passed |
| Two correct (Shield, Blast) → X | Passed |
| Two incorrect (Blast, Shield) → O | Passed |
| Win on third (Shield, Shield, Dodge) → X | Passed |
| Lose on third (Blast, Blast, Blast) → O | Passed |
| Repeat input gives only one damage event | Passed |
| Zero health ends the battle with no Next exchange | Passed |
| Clicks during a battle and on occupied cells do nothing | Passed |
| A win places one X and no automatic O | Passed |
| All 8 lines recognized for X and for O | Passed |
| Full-board draw (X O X X O O O X X) | Passed |
| Last-cell win (X O O O X X X O X) | Passed |
| Play again clears the board | Passed |
| Restart during a battle clears everything; next battle starts at 2 of 2 | Passed |
| Help during a battle keeps the board and battle as they were | Passed |
| Keyboard play (Tab, Enter, Space) | Passed |
| Phone: tap works, no sideways scrolling | Passed |
| No errors in the browser console | Passed |
| Partner playtest with a real person | Not tested |
| Live site on Vercel | Not tested |

## Still to do
- Partner playtest: watch someone play without help and note where they get stuck.
- Publish on Vercel and check the live link.
