# The Naja Era — 365 Days of Creativity

A purple-and-gold interactive first work anniversary website for Naja, Graphic Designer at Brandmarker.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Build and deploy

```bash
npm run build
```

Deploy the project on Vercel (framework: Vite, build: `npm run build`, output: `dist`).

## Personalize

Edit `src/data.js` to replace placeholder timeline milestones, awards, memory captions, and team messages. To add photos, place them in `src/assets/`, import them at the top of `src/data.js`, and set `image` in the memory entries (add `position` to control the crop). Only use photos and messages with permission. The example messages are placeholders, not real quotes from colleagues.

## Notes

- This is a static frontend, so no backend or database is needed.
- The song in `src/assets/` starts when the visitor opens the secret project and loops; the sound icon in the header plays or pauses it.
- Motion is reduced for visitors with reduced-motion preferences.
# naja-1year
