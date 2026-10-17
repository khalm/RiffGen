# RiffGen

Generates new, original riffs for guitar, bass or synth — right in the browser. Free, no account, no server.

**Version:** 1.5.0 (shown on the front page)

## Features
- Guitar, bass or synth, each with its own tones (clean/crunch/high gain, fingers/pick/fuzz, saw/pluck/acid)
- Tuning and transpose are separate: pick a tuning (Standard, Drop D, DADGAD, Open G/D/E, 7-string, bass 4/5/6-string or custom) and transpose it from 0 down to −12 semitones, or up to +2. The actual tuning is shown (e.g. DGCFAD, C#G#C#F#A#D#) and the tab follows it.
- Key (all 12) and 12 scales/modes
- Time signature: 4/4, 3/4, 2/4, 6/8, 12/8, 5/4, 7/8, 5/8, 9/8, 7/4, 2/2 or custom (1–15 beats over 2, 4, 8 or 16, with optional accent groups like 3+2+2). Rhythm, accents, drums, tab counting, editor and AI all follow it.
- Length (1, 2, 4 or 8 bars) and tempo (60–220 BPM, tap tempo)
- **Dissonance** slider: from roots and power chords to tritones and minor-second clusters
- **Complexity** slider: from repeating, simple riffs to odd accents, wide leaps and more varied bars
- **AI riffs:** uses Google Magenta's free melody model (trained on real music, runs on the phone). "AI riff" writes a new riff; "AI: finish from bar 1" keeps your first bar and lets the AI write the rest. Key, dissonance, complexity and busyness still shape the result. The model is cached after the first load so it works offline.
- Busyness, swing, drums and loop
- Audio playback (Web Audio, plucked-string synthesis), piano roll, and guitar/bass tab with palm-mute marks
- **Note editor:** tap the piano roll or the tab to add notes, tap a note to select it, then move it, change pitch or length, add a fifth, palm-mute or delete it
- Undo / redo for every change; changing the key transposes your edits
- New riff / new notes / new rhythm, save riffs, share riff codes, copy tab as text

## Install as an app
Open the GitHub Pages link in Chrome on your phone and tap **Install app** at the top (or ⋮ → Install app). Once installed it opens full screen and works offline.

## Run
Open `index.html`, or turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).
