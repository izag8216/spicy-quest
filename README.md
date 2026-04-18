<p align="center">
  <img src="banner.svg" width="100%" alt="Spicy Quest">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Game-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Dependencies-None-27AE60?style=flat-square" alt="No Dependencies">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/Status-Playable-FF6B6B?style=flat-square" alt="Playable">
</p>

---

## About

**Spicy Quest** is a lightweight, retro Dragon Quest-style RPG built entirely in a single HTML file with zero dependencies. Play as **Chili**, a brave chili pepper knight on a quest to defeat the **Frost King** and restore flavor to the Spice Kingdom!

## Features

- **Turn-Based Combat** -- Classic Dragon Quest-style battle system with Fight, Magic, Items, and Run commands
- **Pixel Art Sprites** -- Hand-crafted pixel art characters drawn entirely with Canvas API
- **Retro Sound Effects** -- Web Audio API generates authentic 8-bit sound effects
- **3 Maps** -- Explore Spice Village, Spicy Forest, and Frost Castle
- **NPC Dialog System** -- Talk to villagers, merchants, and healers
- **Level Up System** -- Gain EXP, level up (1-5), learn new spells
- **3 Spells** -- Fire Breath, Chili Storm, and Spice Heal
- **Boss Fight** -- Face the Frost King in an epic battle
- **Save/Load** -- Progress saved to localStorage automatically
- **Zero Dependencies** -- Single HTML file, no build tools, no frameworks

## How to Play

1. **Download** `index.html`
2. **Open** in any modern browser
3. **Play!**

### Controls

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move |
| Enter / Z / Space | Confirm / Interact |
| Escape / X | Cancel / Menu |

### Gameplay Tips

- Talk to the **Elder** in Spice Village to learn your quest
- Visit the **Healer** to restore HP and MP for free
- Explore the **Spicy Forest** for items and EXP
- Reach **LV 3+** before challenging the Frost King
- **Chili Storm** spell (learned at LV 2) deals heavy damage

## Game World

| Location | Description |
|----------|-------------|
| Spice Village | Safe starting town with NPCs |
| Spicy Forest | Wilderness with random encounters |
| Frost Castle | Dangerous dungeon, boss at the top |

## Technical Details

- **Engine:** HTML5 Canvas API
- **Resolution:** 320x240 (scaled with `image-rendering: pixelated`)
- **Audio:** Web Audio API (oscillator-based retro sounds)
- **Storage:** localStorage for save data
- **Size:** ~25KB single file

## Project Structure

```
spicy-quest/
  index.html          -- Complete game (single file)
  banner.svg          -- Title screen artwork
  README.md           -- This file
  README.ja.md        -- Japanese README
  LICENSE             -- MIT License
```

## Credits

Designed and built with Claude Code.

## License

[MIT](LICENSE) -- Free to use, modify, and distribute.
