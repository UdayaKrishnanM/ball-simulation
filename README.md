# Ball Derby Arena

A 3D football "ball battle" simulation for YouTube Shorts and Instagram Reels. Two balls, one per team, bounce around a glowing neon ring. A goal net slides around the edge of the ring, and a ball that hits it scores. The clock runs from 0' to 90' and every match is random.

## Run it

No install, API keys or accounts needed. Download `index.html` and open it in **Chrome or Edge**. An internet connection is needed for the 3D engine (three.js) and fonts.

## This branch: v3

Everything in v2, plus:

- **Logos built in.** 184 club crests (from the Club_Crests 2026-27 pack) and the flags of all 211 FIFA national teams load automatically when a team is picked.
- Full 2026-27 squads for the Premier League, LaLiga, Serie A and Ligue 1; national teams grouped by confederation.
- Search by short names too ("Man City", "PSG", "Inter").
- "Upload your own logo" still overrides the built-in one; "Use built-in logo" switches back.
- Crests are centred and fully inside the ball and scoreboard; flags fill the ball.
- Bigger balls, sharper crests and larger, high-contrast text for phone screens.

National flags: [flag-icons](https://github.com/lipis/flag-icons) (MIT licence).

## Versions

Each version lives on its own branch; `main` is the latest (v4).

| Branch | What it adds |
|---|---|
| `v1` | The 3D simulation, teams, logo upload, channel branding |
| `v2` | Built-in 9:16 Shorts recorder |
| `v3` | Built-in club crests and national flags, full 2026-27 leagues |
| `v4` / `main` | Automatic saving into a folder per matchup, smoother performance |
