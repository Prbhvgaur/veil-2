# Veil — Say what you mean, without saying who you are

A cinematic, single-file anonymous-messaging web app. Everything — 13 screens, the 20-question archetype ritual, personalized readings, discovery, inbox with read/archive states, WebGL "living veil", particle sigils, and the full crimson horror-neon design system — lives in one `index.html`.

## Run

Open `index.html` directly, or serve it:

```bash
python -m http.server 4173
# → http://localhost:4173
```

## Demo conventions

- Any 6-digit OTP code works, except `111111` (error path).
- Press `m` in the inbox to summon a new whisper.
- State persists in `localStorage` under `veil.*` keys.

## Notes

- Fonts load from Google Fonts; the WebGL Séance section loads Three.js r160 from cdnjs (graceful fallback offline). Everything else is inline.
