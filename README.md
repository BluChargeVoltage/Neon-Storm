# Neon Storm FFA v2

A browser-based multiplayer free-for-all FPS prototype built for Railway.

## What changed in v2
- Fixed movement/spawn collision bug from v1
- 5 distinct weapons: assault rifle, SMG, shotgun, DMR, sniper
- Weapon switching with 1-5
- Server-side weapon damage/rate validation
- Larger, denser neon city arena
- Central plaza, metro entrance, construction zone, elevated walkway, cars and street cover
- Sprint, jump and slide movement
- Rain, puddles, lightning, fog, emissive signage and improved lighting
- 6 bots so the game is playable immediately

## Controls
- WASD: move
- Mouse: aim
- Left click: fire
- Shift: sprint
- Space: jump
- C: slide
- R: reload
- 1-5: switch weapon
- Esc: release mouse

## Railway
Deploy the repository root. Railway can build with the included Dockerfile and injects `PORT` automatically.

Health check: `/health`

## Notes
This is a WebGL browser prototype. It aims for a much richer cinematic look than v1, but true AAA photorealism requires production assets, PBR texture sets, character animation, audio production and a larger engine/content pipeline.
