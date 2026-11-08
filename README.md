# Sacrifice

A portrait-mode 2.5D zombie horror shooter for phones, built in a single HTML file.

You play a night-shift survivor at St. Aldric General. Walk the dark wards in first person, open doors, find the red keycard and reach the stairwell exit while illustrated zombies close in.

## Play

Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main`, root) and open the link on your phone.

## Controls

- **Left stick** walks forward/back and turns
- **Drag the screen** to look around
- **Fire** shoots (hold for repeat fire)
- **Open** opens doors, unlocks the red door and uses the exit
- **Swap** switches between the sidearm and the shotgun
- Keyboard: WASD or arrows, Space to fire, E to open, Q to swap, Esc to pause

## Main menu

- **Story** — three chapters: Ward 13, The Morgue and Roof Access. Clearing one unlocks the next.
- **Collection** — survivors with perks, gun finishes and a zombie bestiary.
- **Gacha** — the Pharmacy cabinet. Spend tokens earned from kills and clears on survivors and gun finishes.
- **Online** — live players and leaderboards. These run on claude.ai's artifact runtime, so they only work in the Claude-hosted version; in a plain browser the game saves progress locally and the Online tab shows as unavailable.

## Tech

Plain HTML, CSS and JavaScript with no build step. A software raycaster draws the walls, floor and ceiling. Zombies, weapons, pickups, survivor portraits and wall textures are game-style renders generated with Higgsfield and embedded in the page as image atlases. Sound is synthesized with the Web Audio API.
