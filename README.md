# Rizz UI Prototype

A working HTML/JS prototype of three connected screens for **Rizz**, an AI-character dating app.

## Screens
1. **Home** — TikTok-style vertical scroll feed of character cards (swipe up to discover next character)
2. **Match Success** — Celebration modal after tapping the CTA on a card
3. **Date / Characters** — Profile grid showing in-progress and completed characters

## Run locally
Just open `index.html` in any modern browser, or serve the folder with any static server:

```bash
npx serve .
# then open http://localhost:3000
```

## Stack
- Vanilla HTML / CSS / JS — no build step
- Rizz design tokens (`colors_and_type.css`) imported directly
- Pretendard Variable for Korean type, Inter for Latin

## Interaction model
- **Swipe up (or mouse drag up)** → next character (exploration)
- **CTA "대화 시작하기"** → match success (selection)
- The two intents are intentionally separated.
