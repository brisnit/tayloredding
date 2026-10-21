# Lost Frequencies — experience notes

## The hunt
A persistent “something is transmitting” beacon opens the field notes. Five numbered signal marks are scattered through the hero, latest record, archive, artist section, and contact section. Each reveals a word and a short reflective message. Visitors can collect them in any order; clues provide anchor links without immediately collecting the item. Progress survives reload in localStorage, with an in-memory fallback when storage is blocked.

1. Hero / antenna: KEEP — Every transmission begins with a little curiosity.
2. Latest record / echo: THE — A song is a place you can return to.
3. Archive / cloud: STRANGE — Different days leave different frequencies behind.
4. Artist / human: SIGNAL — The imperfections are part of the signal.
5. Contact / return: ALIVE — The end is another beginning.

The complete phrase is KEEP THE STRANGE SIGNAL ALIVE. Completing the hunt unlocks Secret Signal mode: lavender cosmic atmosphere and three-way prism shots. The reward is playable immediately; there is no invented unreleased music or promised download. Reset clears hunt progress without deleting the arcade high score.

## Arcade
Original canvas space shooter with vector enemies, formations, diving attackers, rising waves, three lives, scoring, a persistent high score, and an energy shield. Move with left/right arrows or A/D, hold Space to fire, P to pause. On touch devices drag the ship with automatic firing. Pause/Resume and Restart buttons are available. Scrolling the canvas out of view or hiding the tab pauses gameplay; music continues. The hunt dialog also pauses gameplay.

## Music
Bandcamp is embedded alongside the game, never auto-played. The atmosphere selector loads one of the three real Dramatic tracks and changes an explicitly labeled designed rhythm. The third-party iframe does not expose audio samples, so this mode does not claim real beat detection.

For real audio reactivity, the visitor can select an audio file from their device and press play. A Web Audio analyser reads bass energy, which changes the background waveform, shot speed/firing interval, and shield recharge. No upload occurs. Playback errors and unavailable analysis have visible fallback messages. Remove local song releases its object URL. Visitors are reminded to pause Bandcamp to avoid overlapping playback.

## Verification
Browser checked: five-fragment collection, assembled phrase, secret unlock/activation, reload persistence, reset, game start, pause/resume, keyboard input path, and rendered Bandcamp embed. Source checked: JavaScript syntax, unique HTML IDs, five fragments, asset references. Real-song local analysis and physical-phone touch controls still require device testing.
