# Ball Derby Arena

A 3D football "ball battle" simulation for YouTube Shorts and Instagram Reels. Two balls, one per team, bounce around a glowing neon ring. A goal net slides around the edge of the ring, and a ball that hits it scores. The clock runs from 0' to 90' and every match is random.

## Run it

No install, API keys or accounts needed. Download `index.html` and open it in **Chrome or Edge**. An internet connection is needed for the 3D engine (three.js) and fonts.

## This branch: v4 (main)

Everything in v3, plus:

- **Every match saves itself into a folder.** No recording buttons. Press Kick off once to choose a folder (Chrome or Edge), and each match is saved automatically in a sub-folder named after the matchup:

```
Your folder/
└── Manchester City vs Real Madrid/
    └── Manchester City 2-1 Real Madrid (2026-11-20 17-06-32).mp4
```

- Browsers that cannot pick a folder (Firefox, Safari) download the video instead.
- Smoother play while saving: no resize at kick-off, lighter glow effect, scoreboard redrawn only when it changes.
- If it still lags, set the frame rate to 30 fps or the video size to 720 x 1280 in "Match videos".

National flags: [flag-icons](https://github.com/lipis/flag-icons) (MIT licence).

## Versions

Each version lives on its own branch; `main` is the latest (v4).

| Branch | What it adds |
|---|---|
| `v1` | The 3D simulation, teams, logo upload, channel branding |
| `v2` | Built-in 9:16 Shorts recorder |
| `v3` | Built-in club crests and national flags, full 2026-27 leagues |
| `v4` / `main` | Automatic saving into a folder per matchup, smoother performance |
