# RAGEX — THE ULTIMATE RAGE RUN
### Commercial-Quality 3D Hardcore Rage Platformer

**RAGEX** is a fast-paced, addictive, hardcore 3D rage parkour platformer built from the ground up for modern desktop and mobile browsers.

---

## ⚡ Key Highlights

- **100% Offline Single-Player**: Zero backend dependencies, zero external network downloads, zero telemetry.
- **Pure WebGL 3D Powered by Three.js**: Bundled locally (`lib/three.min.js`), runs directly from the filesystem (`file:///...`) or any local HTTP server.
- **Dynamic Web Audio Synthesizer**: Procedural 16-step synthwave music generator with dynamic tempo shifts, paired with punchy procedural sound effects for jumps, double jumps, laser zaps, slidings, checkpoints, death explosions, and triumphant fanfares.
- **12 Handcrafted Levels**:
  1. *Beginner's Nightmare* — Teaches momentum, sliding under low lasers, moving platforms, and fake platform surprises.
  2. *Jump of Death* — High-velocity bounce pad launch across bottomless spike pits and vertical drops.
  3. *Invisible Platforms* — Holographic tiles that crumble 0.5s after contact, plus crushing stompers.
  4. *Laser Madness* — Pulsing tripwires, sweeping curtains, and low beams requiring slide maneuvers.
  5. *Spinning Hell* — Slicing sawblades on rails and rotating circular saws.
  6. *Falling Floor* — High-speed sprint across collapsing tiles where hesitation is fatal.
  7. *Speed Demon* — Mach-speed parkour with rapid descending pistons and bounce launches.
  8. *Impossible Bridge* — Razor-thin balance beams, swinging blades, and a devious fake checkpoint trap.
  9. *Trap Kingdom* — Multi-hazard gauntlet combining crushers, lasers, moving platforms, and bounce pads.
  10. *Ultimate Rage* — Grand multi-tier finale with vertical ascension and summit victory portal.
  11. *The Glitch Dimension (Secret Level)* — Matrix green aesthetic with surreal geometry.
  12. *Neon Overdrive (Bonus Master Level)* — Rhythm-based moving platform parkour.
- **Ghost Replay System**: Automatically records your fastest run trajectory and projects a translucent neon ghost for you to race against your Personal Best.
- **6 Unlockable Runner Skins**:
  - *Neon Striker* (Cyan & Charcoal)
  - *Blood Runner* (Crimson & Black — unlock by dying 10 times)
  - *Cyber Ninja* (Ultraviolet & Gold — unlock by clearing Level 3)
  - *Void Ghost* (Translucent Ethereal Silver — unlock by completing a Flawless Run)
  - *Gold Champion* (Shimmering Metallic Gold — unlock by beating Level 10)
  - *Matrix Glitch* (Digital Cyber Green — unlock by clearing Secret Level 11)
- **8 In-Game Achievements**: Real-time pop-in toast banners with progress saving.
- **Speedrun Auto-Sprint Mode**: Toggle in Settings for non-stop full velocity runs.

---

## 🎮 Controls

### Desktop Keyboard
| Key | Action |
| --- | --- |
| **W / S** or **Up / Down** | Run Forward / Backward |
| **A / D** or **Left / Right** | Strafe Left / Right |
| **Space** | Jump & Double Jump (mid-air flip) |
| **Shift** | Sprint (Speed boost, dynamic FOV, neon particle trail) |
| **C / Ctrl** | Slide (Duck under high lasers, spark friction) |
| **R** | Instant Respawn at Checkpoint |
| **Esc / P** | Pause Menu |

### Mobile & Touch Screens
- **Left / Right Touch Buttons**: Strafe movement
- **Jump Button**: Large touch button with double-jump detection
- **Sprint Button**: Fast run toggle
- **Slide Button**: Duck and slide on ground

---

## 🚀 How to Run

1. Simply double-click `index.html` or open it in any modern browser:
   ```
   file:///C:/Users/amar%20nath%20sahu/.gemini/antigravity/scratch/ragex/index.html
   ```
2. Or serve it via any static HTTP server:
   ```bash
   # Using Node (if installed)
   npx serve .
   
   # Or using Python (if installed)
   python -m http.server 8080
   ```
3. That's it! Everything is 100% self-contained and ready to play.
