# Beardy's Music Player

A CD player in the browser, built from a Figma design. It is one self-contained HTML file (`index.html`) with no dependencies.

## Features

- **Spinning CD.** The disc spins up to discman speed (about 400 rpm) and blurs into rings at full speed. It spins down when you pause or stop.
- **Transport controls.**
  - Back to the start or the previous track
  - Rewind and fast-forward: click to skip 10 seconds, hold to scan
  - Play/pause
  - Stop
  - Next track
- **CD changer.** The current disc sinks into the player and the next one slides in.
- **Parametric equalizer.** A blue screen above the display shows four bands (low shelf, two bells, high shelf), the total curve and a live spectrum. Drag a point to change frequency and gain, scroll to change Q, or use the FREQ, GAIN and Q knobs. Double-click a point or knob to reset it.
- **Mixer fader for volume.** It has a dB scale and a round LED level meter that goes from green through orange to red.
- **Dot-matrix LCD.** A yellow-green character display shows "ARTIST - TITLE" scrolling back and forth, the time remaining, a progress bar and the track length.
- **Brushed aluminium housing** with screws in the corners.

The music is generated live in the browser with the Web Audio API. No audio files are included, and the track names are examples.

## Keyboard shortcuts

| Key | Action |
|---|---|
| Space | Play/pause |
| ← / → | Skip 10 s |
| ↑ / ↓ | Volume |
| N / P | Next / previous track |
| C | Change CD |

## Usage

Open `index.html` in a browser. To publish it with GitHub Pages, go to **Settings → Pages**, select the `main` branch and the `/ (root)` folder, and save.
