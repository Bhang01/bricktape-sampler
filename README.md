# BrickTape Sampler

**A groovebox and sampler for the TrimUI Brick: an 8-track step sequencer, 16 performance effects, 9 kits, a 4-band multiband effects engine, chopping and on-device stem separation.**

Program beats with 6 pages and song mode, play them live through 16 performance effects, load or record samples, chop them, split songs into vocals / drums / bass / other, and render the results to WAV or MP3. One native program, nothing else to install.

> **Requires Knulli.** BrickTape Sampler runs only on a TrimUI Brick with the **Knulli** firmware installed, from Knulli's *Ports* menu. It does not run on the stock TrimUI OS.

## Download

**[BrickTape Sampler v1.12.0 beta](https://github.com/Bhang01/bricktape-sampler/releases/tag/v1.12.0-beta)** (latest): get `BrickTape_Sampler_v1.12.0-beta_Knulli_TrimUI_Brick.zip` from the release's Assets. All releases are on the [Releases page](https://github.com/Bhang01/bricktape-sampler/releases).

## Install

1. Unzip the release on your computer.
2. Copy its `roms` folder onto the SD card's share partition (the one with the `roms` folder), merging folders. Your projects, recordings, presets and own samples are kept.
3. On the Brick, open **Ports → BrickTape Sampler**. If it isn't listed: *Main menu → Game settings → Update gamelists*.
4. Press each button once on the first-launch setup screen (and the PLAY button when asked), then put your samples in `roms/ports/bricktape/samples/My Sounds/`.

Quit with **SELECT + START**, the START menu, or HOTKEY + START.

## Highlights

- **New in 1.12:** an 8-track step sequencer with 6 pages (A–F), song mode and named songs, randomize from real dance rhythms, mute / solo per pad
- **PLAY FX:** 16 performance effects on Y X A B — glitch, repeat, stutter roll, reverse, scratch, tape stop, backspin, DJ filters, talk box, gater, bitcrush, jet flanger, pitch delay, reverb throw, noise riser — playable on the VISUAL page too
- **9 kits made for BrickTape** (Techno, Ambient, Lo-Fi, House, Trap, Drum & Bass, Synthwave, Jungle, Breakbeat) and a KITS page with sound preview
- Parameter locks on any step, effects on every pad, a mixer, presets and a DELAY tab with 15 kinds of echo
- 64 pads in 8 banks, played on the D-pad and A / B / X / Y; USB MIDI keyboard support
- Grid, threshold, lazy and manual chopping, with chops sent to a bank in one press
- Stem separation on the Brick itself (Deezer's Spleeter 4-stems model, MIT)
- Repitch, time-stretch and tempo-following warp; tap tempo and BPM detection
- 4-band multiband FX: per-band speed, beat repeat, granular, drive, bitcrush, compression, auto pan, delay, reverb
- Amp sims and cabinets, phaser, flanger, chorus, rotary, ring mod, resonator, trance gate, noise textures, multimode filter
- VERB: a big shimmer reverb with freeze
- Classic-sampler character, SP-404-style Lo-Fi and Tape, master EQ, compressor, clipper and limiter
- Clean mic recording, USB audio in and out (low latency), projects, rendering and master recording, audio-reactive visuals

## Manual

The full manual ships inside the app folder as `roms/ports/bricktape/README.md`; its *What's new* sections cover every version.

## Problems?

Open an issue and attach `roms/ports/bricktape/log.txt`.

## Licence

BrickTape Sampler is MIT licensed. Third-party components (Spleeter model, shine MP3 encoder, dr_libs, fonts, SDL2) and their licences are listed in the source zip attached to each release.
