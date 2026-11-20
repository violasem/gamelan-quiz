# Gamelan in Pop Culture Quiz 🎵🔔

A projector quiz for the Permias U-M gamelan workshop: play a clip, the crowd guesses where it's from (4 options, one is a troll), then reveal.

## Run it
Open `index.html` in a browser (Chrome works best), press **F** for fullscreen.

## Add the clips
Put audio files in the `clips/` folder with these names:
- `clips/akira.mp3`
- `clips/zelda.mp3`
- `clips/spirited-away.mp3`
- `clips/mario.mp3`

Trim them to ~10–15 seconds of the gamelan part. To change questions, edit the `QUESTIONS` list near the top of the `<script>` in `index.html`.

## Host controls
| Key | Action |
|---|---|
| Space | Start / play-pause clip |
| C | 10-second countdown (auto-reveals at 0) |
| R | Reveal answer |
| T | Troll attack 💀 (for when someone picks the troll answer) |
| G | Hit the gong |
| → / ← | Next / previous question |
| F | Fullscreen |
