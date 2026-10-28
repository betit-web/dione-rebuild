# Security policy

Dione Rebuild is an unofficial, non-commercial fan project.

## Reporting a vulnerability

Please report security issues **privately** through GitHub: *Security* tab → *Report a vulnerability* (private vulnerability reporting is enabled on this repository). Do not open a public issue for security problems.

Include what you found, how to reproduce it, and the version of the launcher/game (shown in the launcher).

## Scope

- The launcher (`DioneLauncher.exe`) and the game build published in the releases of this repository.
- The account and friends backend rules (Firebase).

Out of scope: the original *Ring of Elysium* game files, which are never distributed here.

## What we never do

- We never distribute game files: data is extracted locally from your own Steam copy.
- Passwords are never stored in plain text (Windows DPAPI) and never logged.
- Releases are immutable and every download is verified by SHA-256.
