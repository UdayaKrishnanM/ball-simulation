# Ball Derby Arena

A 3D football "ball battle" simulation for YouTube Shorts and Instagram Reels. Two balls, one per team, bounce around a glowing neon ring. A goal net slides around the edge of the ring, and a ball that hits it scores. The clock runs from 0' to 90' and every match is random.

## Run it

No install, API keys or accounts needed. Download `index.html` and open it in **Chrome or Edge**. An internet connection is needed for the 3D engine (three.js) and fonts.

## This branch: v2

Everything in v1, plus:

- **Built-in Shorts recorder.** Records only the 9:16 arena (1080x1920, 60 fps) with game sound when you press Kick off, stops a few seconds after full time and downloads the video (MP4 or WebM).
- Scoreboard, banners and branding are drawn on a canvas so they appear inside the recorded video.
- Settings: auto-record, 1080p or 720p, 60 or 30 fps, seconds to keep recording after full time, auto-download.

## Versions

Each version lives on its own branch; `main` is the latest (v4).

| Branch | What it adds |
|---|---|
| `v1` | The 3D simulation, teams, logo upload, channel branding |
| `v2` | Built-in 9:16 Shorts recorder |
| `v3` | Built-in club crests and national flags, full 2026-27 leagues |
| `v4` / `main` | Automatic saving into a folder per matchup, smoother performance |
