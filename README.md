# Dione Rebuild — launcher

**Unofficial fan project — requires your own Steam copy of the game.**

A non-commercial recreation of the Mt Dione map from *Ring of Elysium*, built with Godot 4. Not affiliated with the game's publisher or developer.

## Download

**[DioneLauncher.exe](https://github.com/betit-web/dione-rebuild/releases/latest/download/DioneLauncher.exe)** — Windows 10/11, 64-bit, about 200 KB.

## Community

Discord: https://discord.gg/sMjWmdjXA2

## Requirements

- **Ring of Elysium installed in your Steam library.** No game files are distributed here: the game data is extracted on your PC from your own copy (read-only, nothing is modified).
- About 6 GB of free disk space.

## What the launcher does

1. Creates your account (email + password, email verification).
2. Finds Ring of Elysium in Steam and checks its version.
3. Downloads our code and the required engines (Godot, Python), all verified by SHA-256.
4. Extracts the game data locally (10–20 minutes the first time).
5. PLAY opens the main menu, signed in to your account (your friend ID is tied to your account).

Updates are automatic. Language: English by default; French and the original game languages can be selected in the settings (gear icon).

The executable is not code-signed, so Windows SmartScreen may show a warning: "More info" → "Run anyway".
