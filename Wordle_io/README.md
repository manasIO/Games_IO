# Wordle.IO 🟩🟨⬛

A stylish, browser-based Wordle clone — guess the **Word of the Day** in **5 attempts**.

## How to Play

1. Open `wordle.html` in any modern browser — no server, no install needed.
2. Type a **5-letter word** and press **Enter** to submit your guess.
3. Each tile flips and changes colour to give you clues:

| Colour | Meaning |
|--------|---------|
| 🟩 **Green** | Correct letter, correct position |
| 🟨 **Yellow** | Letter is in the word, wrong position |
| ⬛ **Gray** | Letter is not in the word at all |

4. Use the clues to narrow down the word — you have **5 guesses**.
5. A new word is available every day at midnight.

## Features

- **Daily word rotation** — same word for everyone on the same day
- **Animated tile flips** with staggered reveal
- **Confetti burst** on a winning guess
- **On-screen keyboard** with live colour feedback
- **Stats tracking** — win %, streaks, and guess distribution (stored in localStorage)
- **Session restore** — refresh the page and pick up exactly where you left off
- **Responsive design** — works on desktop and mobile
- **Zero dependencies** — single HTML file, no frameworks

## Running Locally

```bash
# Just open the file:
open Wordle_io/wordle.html

# Or serve it (optional):
npx serve .
```

## Project Structure

```
Wordle_io/
├── wordle.html   # Complete game (HTML + CSS + JS)
└── README.md
```

## Tech Stack

- Vanilla HTML5 / CSS3 / JavaScript (ES6+)
- Canvas API for confetti
- localStorage for stats persistence
- CSS animations (flip, shake, bounce, confetti)
