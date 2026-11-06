# DrumTrig

**DrumTrig** turns an Android phone into a live drum trigger. A mic on a drum (or an audio interface) goes in, and the phone plays the sound you chose, with as little delay as the phone can manage.

![The live screen: the input and output meters either side, and the graph of the last hit in the middle](screenshots/live.png)

## What it does

- **Triggers from any mic.** Set the threshold (THR) on the input meter and a trigger filter on the graph, so only your drum fires the sound and the rest of the kit doesn't.
- **Set by hitting.** Leave the drum alone for a moment, hit it a few times, and DrumTrig suggests the threshold, the filter and the hold time for you.
- **Plays the sound you choose.** Bundled sounds, recorded drum kits (a free download inside the app), or your own samples. Each sample has its own EQ.
- **Shows its delay.** The latency of every hit is measured and shown, with settings to bring it down.
- **Made for the stage.** A big-type Stage view, Lock so nothing changes mid-song by accident, Mute, and a light and a dark look.

| | |
|---|---|
| ![The Trigger menu: filter, hold, delay, response](screenshots/trigger-menu.png) | ![Set by hitting, showing the threshold, filter and hold it found](screenshots/set-by-hitting.png) |
| **Trigger menu**: when a hit counts and how it plays, kept per instrument. | **Set by hitting**: the threshold, filter and hold, found from the drum itself. |
| ![The EQ on the graph, with four bands over the sample's spectrum](screenshots/eq.png) | ![The Stage view: the instrument, the input meter, a big latency figure](screenshots/stage.png) |
| **EQ**: up to seven bands per sample, drawn over its sound. | **Stage**: what matters mid-song, readable from behind the kit. |

![The live screen in the light look](screenshots/live-light.png)

## Install or update DrumTrig

1. On your phone, open the **[latest release](https://github.com/fubulatu-lang/DrumTrig-Releases/releases/latest)**.
2. Download `DrumTrig-<version>.apk` and open it.
3. If Android asks, allow your browser or file manager to install apps.

Every release is signed with the same key, so a new version installs straight over the old one. Your instruments, samples, EQs and settings are kept.

DrumTrig also tells you when a new version is out. It checks this page each time it opens and sends nothing about you or your phone. When there is one, it asks as you open the app: **Update** downloads it and Android asks you to install it; **Ignore** skips that version. You can also check any time in **Settings › App › About & help**.

## Recorded drum sounds

The **sounds-…** releases hold the recorded drum sound pack. You don't need to download it here; DrumTrig fetches it when you tap **Download** in **Settings › Sound › Sound packs**. The app checks the file's fingerprint (SHA-256) before using it, so a changed or damaged file is refused.

The recorded sounds come from the DrumGizmo kits DRSKit, MuldjordKit and CrocellKit by the DrumGizmo team and Lars Muldjord ([drumgizmo.org](https://drumgizmo.org)). They are licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), and were mixed to mono and trimmed for DrumTrig.

## What you need

- An Android phone or tablet running Android 8.0 or newer.
- A microphone or trigger: the phone's own mic works for trying it out. A USB audio interface, for both the mic and the sound out, gives the lowest delay.
