# Fretboard Lab

An interactive guitar learning web app — a single self-contained HTML file with everything baked in: SVG fretboard, scale overlays, pentatonic boxes, diatonic chords, circle of fifths, ear training, and a metronome.

**Live demo:** _coming soon — hosted on GitHub Pages_

## Features

- **Interactive SVG fretboard** — 22 frets with realistic spacing, hover to highlight octaves, click to hear the note
- **13 scales** — major, natural/harmonic/melodic minor, pentatonics, blues, dorian, phrygian, lydian, mixolydian, locrian, whole tone
- **Pentatonic & scale box positions** — 5 fretboard positions for any scale, color-coded
- **Diatonic chord viewer** — see the I–vii° chords for any key
- **Circle of fifths** — clickable, syncs with the rest of the app
- **Display modes** — dots, note names, or interval labels
- **Layer mode** — stack multiple scales in different colors
- **Tunings** — Standard, Drop D, Drop C
- **Metronome** — adjustable BPM, time signatures, plus a "Click" mode for a straight pulse
- **Ear training** — interval and chord recognition
- **Guitar-like audio** — multi-harmonic synthesis with a lowpass filter sweep so it sounds like a plucked string, not a beep

## Running locally

It's one HTML file. Just open it.

```
open index.html
```

Or serve it with anything that serves static files:

```
npx serve .
```

## Tech

- Pure HTML/CSS/JS, no build step, no dependencies
- Web Audio API for sound synthesis
- SVG for the fretboard
- ~3,700 lines, ~115 KB

## License

Personal project — built for my own practice. Use it however you want.
