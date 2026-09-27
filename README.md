# Tile Tunes

A small piano-tiles style browser game. Tap the black tiles as they scroll down and each one plays the next note of a song. It's plain HTML, CSS and JavaScript in a single `index.html` file, with no frameworks, build tools or audio files. All sounds are generated with the Web Audio API.

## How to play

1. Open `index.html` in a browser. It works on phones (portrait) and desktop.
2. Pick a song on the start screen: Ode to Joy, Für Elise or Twinkle Twinkle Little Star.
3. Tap the black **Start** tile at the bottom to begin.
4. Tap each black tile in order, starting with the lowest one. Every correct tap plays the next note of the song.
5. **Hold tiles** (tall tiles with an arrow, from 15 points on): press the bottom of the tile and keep holding while the fill rises. Hold it to the end for +2 bonus points. Letting go early is safe but scores less.
6. The game ends if you tap a white area or let a black tile scroll past the bottom. It gets faster as your score rises.

Your best score and chosen song are remembered in your browser.

## Playing on a phone

Serve the folder from your computer and open it on a phone on the same Wi-Fi:

```bash
python3 -m http.server 8000
```

Then visit `http://<your-computer's-local-IP>:8000` on the phone.

## Adding songs

Songs live in the `SONGS` section at the top of the script in `index.html`, as note names separated by spaces (e.g. `'E5 D#5 E5 B4'`), one note per tap.
