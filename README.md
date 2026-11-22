# BrickTape Sampler

**A 64-pad sampler with a 4-band multiband effects engine, chopping, on-device stem separation and classic-sampler colour, for the TrimUI Brick.**

Load or record samples, chop them, split songs into vocals / drums / bass / other, play them on the Brick's face buttons through deep effects, and render the results to WAV or MP3. One native program, nothing else to install.

> **Requires Knulli.** BrickTape Sampler runs only on a TrimUI Brick with the **Knulli** firmware installed, from Knulli's *Ports* menu. It does not run on the stock TrimUI OS.

## Download

**[BrickTape Sampler v1.6.4 beta](https://github.com/Bhang01/bricktape-sampler/releases/tag/v1.6.4-beta)**: get `BrickTape_Sampler_v1.6.4-beta_Knulli_TrimUI_Brick.zip` from the release's Assets. All releases are on the [Releases page](https://github.com/Bhang01/bricktape-sampler/releases).

## Install

1. Unzip the release on your computer.
2. Copy its `roms` folder onto the SD card's share partition (the one with the `roms` folder).
3. On the Brick, open **Ports → BrickTape Sampler**. If it isn't listed: *Main menu → Game settings → Update gamelists*.
4. Press each button once on the first-launch setup screen, then put your samples in `roms/ports/bricktape/samples/`.

Quit with **SELECT + START**, the START menu, or HOTKEY + START.

## Highlights

- 64 pads in 8 banks, played on the D-pad and A / B / X / Y
- Grid, threshold, lazy and manual chopping, with chops sent to a bank in one press
- Stem separation on the Brick itself (Deezer's Spleeter 4-stems model, MIT)
- Repitch, time-stretch and tempo-following warp; tap tempo and BPM detection
- 4-band multiband FX: per-band speed, beat repeat, granular, drive, bitcrush, compression, auto pan, delay, reverb
- Amp sims and cabinets, phaser, flanger, chorus, rotary, ring mod, resonator, trance gate, noise textures, multimode filter
- VERB: a big shimmer reverb with freeze
- Classic-sampler character, SP-404-style Lo-Fi and Tape, master EQ, compressor, clipper and limiter
- Clean mic recording, USB audio in and out, projects, rendering and master recording, audio-reactive visuals

## Manual

The full manual is attached to each release as `MANUAL.md`, and ships inside the app folder as `README.md`.

## Problems?

Open an issue and attach `roms/ports/bricktape/log.txt`.

## Licence

BrickTape Sampler is MIT licensed. Third-party components (Spleeter model, shine MP3 encoder, dr_libs, fonts, SDL2) and their licences are listed in the source zip attached to each release.
