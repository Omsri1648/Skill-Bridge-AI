# SkillBridge AI

A responsive React + TypeScript learning dashboard prototype with a dark charcoal / electric-green visual system.

## Run locally
1. Install Node.js 18+.
2. Extract this folder and open a terminal inside it.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite (usually http://localhost:5173).

For a production build: `npm run build` then `npm run preview`.

## Included
- Dashboard, roadmap, AI tutor, skill-gap analyzer, coding practice, adaptive quizzes, analytics, achievements and settings.
- English, Tamil and Hindi interface switching (stored in localStorage).
- CSV score upload and manual score entry.
- Quiz scoring, adaptive difficulty, roadmap completion, profile preferences, XP and streak simulation.
- Browser persistence for settings, progress, scores and tutor messages.
- Sample/demo data is explicitly labelled.

## Important implementation notes
- The tutor uses local demonstration responses; it does not claim a live LLM is connected.
- Coding practice uses a safe, predefined exercise checker and does **not** execute arbitrary submitted code.
- Data is stored in this browser using localStorage. This is a prototype, not multi-user authentication or cloud sync.
- To add a real AI provider, create a server-side API endpoint and store credentials in server environment variables. Do not expose keys in frontend code.
