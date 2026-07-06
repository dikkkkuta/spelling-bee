# 🐝 Spelling Bee

A single-page, browser-based spelling game for kids, with multiple difficulty
levels and five ways to practise a word list.

## Difficulty levels

- **CVC** — 3-letter consonant-vowel-consonant words (e.g. *cat*, *dog*),
  filterable by vowel
- **Easy / Medium / Hard** — progressively longer word lists

## Game modes

- ✏️ **Spelling Quiz** — type the word from its picture/clue
- 🔀 **Scramble** — unscramble the jumbled letters
- 💡 **Fill the Gap** — fill in the missing letters
- 🔤 **ABC Practice** — simple letter-learning mode
- 👂 **Listen & Spell** — hear the word spoken aloud, then spell it

## How to play

1. Open `index.html` in a browser — no install or build step needed.
2. Pick a difficulty (CVC / Easy / Medium / Hard), then pick a mode.
3. Spell each word before your 3 ❤️ lives run out.
   - Get it right to score points and build a streak (2+ in a row triggers a
     streak bonus).
   - Get it wrong (or run out of time) and you lose a life and your streak
     resets.
   - Tap **💡 Hint** if you're stuck — it reveals a clue but costs points.
4. Finish the word list (or run out of lives) to see your score and star
   rating on the results screen.

## Running it

This is a self-contained HTML/CSS/JS file with no dependencies:

```bash
# just open it directly
open index.html        # macOS
start index.html        # Windows

# or serve it locally (recommended for audio features in "Listen & Spell")
npx serve .
```
