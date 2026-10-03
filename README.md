# Tile Tunes

A small piano-tiles style game. Tap the black tiles as they scroll down, and each one plays the next note of a song.

## Play on any device

**▶ Play now: https://tejas28599-ship-it.github.io/tile-tunes/**

You don't need to install anything. Tile Tunes runs in your browser on any device: phone, tablet or computer.

1. Open the Tile Tunes link above.
2. It opens in any browser on your phone, tablet or computer.
3. Start playing! 🎵

On iPhone, turn silent mode off to hear the music.

**Play offline too:** after you've opened the game once, it works even without internet. Add it to your home screen (Share → *Add to Home Screen* on iPhone, or the browser menu → *Add to Home screen* on Android) to get an app icon that opens full-screen.

## Features

**Play anywhere**
- 📱 **No download needed:** open the link and play in any browser.
- 💻 **Works on every device:** phone, tablet or computer.
- ✈️ **Plays offline:** after your first visit, it works without internet.
- 🏠 **Add to home screen:** get an app icon that opens full-screen, just like an app.
- 🆓 **Free:** no sign-up and no ads.

**Music**
- 🎹 **Every tap plays a note:** play a real song, one tile at a time.
- 🎵 **6 songs:** Ode to Joy, Für Elise, Twinkle Twinkle Little Star, Jingle Bells, Happy Birthday and Canon in D.
- 🎶 **Hold tiles that follow the music:** long tiles appear on the song's long notes, so holding feels like playing it.

**Fun and rewarding**
- ✨ **Tap effects:** a ring and a little ♪ burst from your finger on every correct tap, with a gentle vibration on supported phones.
- 🌅 **New looks as you score:** Sunrise at 25, Ocean at 50, Forest at 100, Twilight at 150 and Golden at 200, each with a confetti burst.
- 🏁 **"Song complete!"** when you play a whole song through.
- ⭐ **Stars:** earn up to 3 per game, at 25, 50 and 100 points.
- 🏆 **Best scores:** your overall best and your best for each song are saved on your device.
- 📤 **Share your score:** send it to friends with a link so they can try to beat you.
- ⚡ **Gets faster as you go:** easy to start, genuinely hard by 100 points.

## How to play

1. Tap the black **Start** tile at the bottom.
2. Tap each black tile in order, starting with the lowest one. Every tap plays the next note of the song.
3. **Hold tiles** (tall tiles with an arrow) appear later: press the bottom and keep holding while it fills up. Hold to the end for +2 bonus points.
4. The game ends if you tap a white space or miss a black tile. It gets faster as your score goes up.

Want a different song? Tap **Change** on the start screen and pick from Ode to Joy, Für Elise, Twinkle Twinkle Little Star, Jingle Bells, Happy Birthday or Canon in D. Earn up to 3 stars per song: 25, 50 and 100 points.

Your best score and song choice are saved on your device.

## What's new

See [CHANGELOG.md](CHANGELOG.md) for the updates in each version. The latest is **version 1.1**.

## For developers

The game is plain HTML, CSS and JavaScript in `index.html`, with no frameworks, build tools or audio files. All sounds are generated with the Web Audio API. `sw.js` (service worker) and `manifest.webmanifest`, with the icon PNGs, make it installable and playable offline.

Songs live in the `SONGS` section at the top of the script in `index.html`, as note names separated by spaces (e.g. `'E5 D#5 E5 B4'`), one note per tile. Add `:2` or `:3` to a note to make it a long note (e.g. `'G5:2'`); long notes become hold tiles of that height.
