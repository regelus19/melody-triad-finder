# Melody Triad Finder

A frictionless songwriting helper for guitarists: play a single-note melody into the microphone and the browser detects the pitch, maps that note across a standard-tuned guitar fretboard, and suggests major/minor triads containing the landing note.

## V1
- Browser microphone input
- Monophonic pitch detection
- Live detected note and frequency
- Standard E A D G B E fretboard through fret 15
- Matching pitch highlighted across the neck
- Major/minor triads containing the detected pitch
- Freeze a landing note while exploring options
- Runs entirely in the browser; no audio is uploaded

## Run
Open `index.html` through an HTTPS web host (GitHub Pages is suitable). Microphone access generally requires HTTPS or localhost.

## Product direction
V1 deliberately stays narrow. Future iterations can rank triad *voicings* by physical distance from the detected fretboard position, infer key/phrase context, distinguish intentional landing notes, add seventh/suspended chords, and support piano/MIDI input.