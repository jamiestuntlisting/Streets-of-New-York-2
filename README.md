# Streets of New York 2 🏀🥊

A 16-bit-style side-scrolling beat-'em-up parody of *Streets of Rage 2* — but it's the
streets of NYC and you're brawling rival ballers block by block. Built as a single,
dependency-free HTML5 canvas game, tuned for phones with on-screen touch controls.

## Play

Open `index.html` in any modern browser, or visit the deployed Vercel URL on your phone.

### Controls
- **Phone:** left thumbstick to move, **PUNCH / KICK / JUMP** buttons on the right.
- **Keyboard:** `WASD` / arrows to move, `J` punch, `K` kick, `L` / `Space` jump.

Clear every wave of rivals on a block to advance. Survive 3 blocks to own the streets.

## Tech
- Pure HTML/CSS/JS — no build step, no dependencies, no external assets.
- All characters and the NYC street are drawn procedurally on `<canvas>`.
- Sound is generated live with the WebAudio API.

## Deploy
Static site. On Vercel, just import the repo (no framework / build command needed) —
`index.html` at the root is served as-is.
