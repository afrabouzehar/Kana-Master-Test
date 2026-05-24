# 🏯 Kana Master Test
### `01_big_kana_test.html`

A comprehensive, single-file hiragana & katakana examination covering the full kana syllabary across five scored sections.

---

## What's Inside

**5 sections, ~105 questions per session** — all randomised on every load.

| # | Section | Type | Questions |
|---|---------|------|-----------|
| I | Hiragana | Multiple choice | 20 |
| II | Katakana | Multiple choice | 20 |
| III | Type It | Keyboard input | 25 |
| IV | Identify the Script | Multiple choice | 20 |
| V | Mixed Challenge | Multiple choice | 20 |

---

## How to Use

1. Open `01_big_kana_test.html` in any modern browser — no internet required after load.
2. Use the **section tabs** at the top to jump between sections freely.
3. Answer every question in a section, then click **Next →** to proceed.
4. After Section V, click **Finish →** to see your results.
5. Hit **↺ Restart Test** to get a fresh randomised set.

---

## Question Types

### Multiple Choice
A kana character is displayed. Choose the correct romaji from 4 options.  
Immediate colour-coded feedback: green = correct, red = wrong.

### Type the Romaji *(Section III)*
Type the romaji reading into the input box and press **Enter** or **Submit**.  
Alternate spellings are accepted:

| Standard | Also accepted |
|----------|--------------|
| `shi` | `si` |
| `chi` | `ti` |
| `tsu` | `tu` |
| `fu` | `hu` |
| `ji` | `zi` |
| `n` | `nn`, `m` |

### Identify the Script *(Section IV)*
Given a character, decide whether it is **Hiragana** or **Katakana**.

---

## Scoring & Grading

| Grade | Score |
|-------|-------|
| 優 · Excellent | 90 %+ |
| 良 · Good | 75 – 89 % |
| 可 · Passing | 60 – 74 % |
| もう一度 · Try Again | below 60 % |

Progress is tracked live in the top bar. The final results screen shows correct, wrong, total, and your grade.

---

## Characters Covered

- **Hiragana:** あ–ん + dakuten (が、ざ、だ、ば) rows
- **Katakana:** ア–ン + dakuten (ガ、ザ、ダ、バ) rows
- Sections draw random subsets each run, so no two tests are identical.

---

## Technical Notes

- Pure HTML + CSS + Vanilla JS — zero dependencies, no build step.
- Fonts loaded from Google Fonts (Playfair Display, DM Mono, Noto Serif JP).
- Works offline once the fonts have cached (or with a local font fallback).

---

*Part of the Kana Learning Suite · see also `02_kana_flashcards.html` and `03_words_reading_test.html`*