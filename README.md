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

## Add pictures (optional)
Put images in `images/` with the names listed in `QUESTIONS` (e.g. `images/akira.jpg`). If a picture is missing, a big emoji shows instead.

Trim the clips to ~10–15 seconds of the gamelan part. To change questions, edit the `QUESTIONS` list near the top of the `<script>` in `index.html`.

## Host controls
Click an option with the mouse: correct = confetti + gong, wrong = shake, troll = 💀 attack. Hover the bottom bar for buttons, or use keys:
| Key | Action |
|---|---|
| Space | Start / play-pause clip |
| C | 10-second countdown (auto-reveals at 0) |
| R | Reveal answer |
| T | Troll attack 💀 (for when someone picks the troll answer) |
| G | Hit the gong |
| → / ← | Next / previous question |
| F | Fullscreen |
