# Project Confluence · M1 combat sandbox (playtest build)

This repo holds the playable M1 combat sandbox for Project Confluence playtests: a single-player browser build that checks whether every enemy attack reads in time, and whether facing, cursor and target aiming each feel responsive and fair.

- **Play:** https://bibidi-thegent.github.io/confluence-m1-playtest/
- **Tester guide:** https://bibidi-thegent.github.io/confluence-m1-playtest/guide.html (also linked from the game's start screen)
- **Roster preview** (unfinished classes, not part of the M1 playtest): https://bibidi-thegent.github.io/confluence-m1-playtest/preview/
- **Build:** a5f7398 · 2026-10-11 (project commit `a5f7398`, published 2026-10-11 UTC). The same stamp shows on the start screen, in the in-game Help (H), and in every telemetry file.

Play in Chrome or Edge on a desktop or laptop, with a mouse that has a right button. Set aside about 45 minutes; the tester guide walks you through the script, the controls, and how to save and send your telemetry files.

## Files

- `index.html`: the game (the whole build is this one file; it loads Three.js from cdnjs).
- `guide.html`: the tester guide.
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

The design documents and source history are private; this repo only holds published builds.
