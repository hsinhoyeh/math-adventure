# 🌟 Math Adventure / 數學大冒險

A bilingual math puzzle game for kids aged 6–10, playable in the browser with no install required.

**Live:** https://hsinhoyeh.github.io/math-adventure/

---

## Features

- **Three themes** — Airline ✈️, Cargo 🚛, City Bus 🚌
- **Three difficulty levels** — Easy / Medium / Hard with a countdown timer
- **Leaderboard** — top 5 scores per difficulty, saved in the browser
- **Bilingual** — English and Traditional Chinese (繁體中文) with Bopomofo / 注音符號 annotation
- **Voice reading** — questions are read aloud automatically via the Web Speech API; tap 🔊 to replay
- **50/50 hint** — removes two wrong answers when you're stuck

## How to play

1. Enter your name and pick a difficulty
2. Choose a theme (Airline / Cargo / Bus)
3. Answer 10 math questions before the timer runs out
4. Your score is saved to the leaderboard

## Tech

Single self-contained `index.html` — no build step, no dependencies. Uses:

- Web Speech API for text-to-speech (`zh-TW` / `en-US`)
- CSS `ruby` / `<span>` for inline Bopomofo annotation
- `localStorage` for leaderboard and language preference

## Development

```bash
# clone and open directly — no server needed
git clone git@github-hsinhoyeh:hsinhoyeh/math-adventure.git
open math-adventure/index.html
```

Deployments go live automatically via GitHub Pages on every push to `master`.
