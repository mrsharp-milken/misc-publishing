# Code Pictionary

## Overview

A collaborative drawing and coding game where players alternate between drawing shapes and writing code to describe those drawings. The goal is to see how much the original picture drifts after passing through multiple rounds of interpretation.

## How to Play

**Step 1 - Draw:** Draw a picture on the left half of your paper (max 6 shapes), then pass to the next person.

**Step 2 - Code:** The next person writes code on the right half that would recreate the drawing.

**Step 3 - Fold:** Same person folds the paper to hide the drawing side, then passes it along — only the code is visible.

**Step 4 - Redraw:** A new person reads the code and draws what it describes on a fresh piece of paper, without peeking at the original.

**Step 5+ - Repeat:** Continue the cycle (Code → Fold → Pass → Draw on new paper) for 6 rounds total, then reveal and compare the full chain from start to finish.

## Shape Functions Cheat Sheet

| Function | Description | Example |
|---|---|---|
| `draw_rect(x, y, w, h, color)` | Rectangle with top-left corner at (x, y) | `draw_rect(2, 3, 4, 2, "red")` |
| `draw_circle(x, y, r, color)` | Circle centered at (x, y) with radius r | `draw_circle(5, 5, 2, "blue")` |
| `draw_ellipse(x, y, w, h, color)` | Ellipse centered at (x, y) | `draw_ellipse(5, 7, 3, 1, "green")` |
| `draw_arc(x, y, r, start, end, color)` | Arc centered at (x, y). Angles: 0=right, 90=up | `draw_arc(5, 5, 2, 0, 180, "orange")` |

## Notes

- The coordinate grid runs from 0–10 on both axes.
- Each paper is folded between the draw and code sections so only the code is passed forward.
- The handout includes commented-out grid sections for Rounds 1–6 (alternating draw and code panels), intended for print use.
