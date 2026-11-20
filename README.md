# Ball Derby Arena

A 3D football "ball battle" simulation for YouTube Shorts and Instagram Reels. Two balls, one per team, bounce around a glowing neon ring. A goal net slides around the edge of the ring, and a ball that hits it scores. The clock runs from 0' to 90' and every match is random.

## Run it

No install, API keys or accounts needed. Download `index.html` and open it in **Chrome or Edge**. An internet connection is needed for the 3D engine (three.js) and fonts.

## This branch: v1

- 3D arena built with three.js: neon ring that changes colour, glow (bloom), comet trails, sparks, camera shake.
- A moving 3D goal net on the ring. Hitting it scores, with slow motion, a GOAL! burst, horn and crowd sound.
- 90-minute clock (15 to 90 seconds on screen), then FULL TIME with the winner and confetti.
- 238 built-in clubs and national teams, searchable, and any custom team can be typed in.
- Upload a logo per team (fills the ball and the scoreboard crest).
- Channel branding: channel name, YouTube and Instagram handles, subscribe pop-up, sub goal bar.
- Studio mode: full-screen 9:16 arena for screen recording.

## Versions

Each version lives on its own branch; `main` is the latest (v4).

| Branch | What it adds |
|---|---|
| `v1` | The 3D simulation, teams, logo upload, channel branding |
| `v2` | Built-in 9:16 Shorts recorder |
| `v3` | Built-in club crests and national flags, full 2026-27 leagues |
| `v4` / `main` | Automatic saving into a folder per matchup, smoother performance |
